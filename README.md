#Country Code To Emoji Flag 🇦🇺🇦🇱🇧🇪🇫🇷🇩🇰🇵🇱🇺🇦🇬🇧🇺🇸
Converts string of country codes to string of emoji flags. As an argument use a single 2-letter country code or a string of multiple codes.

##Why Emoji
Emoji symbol is a replacement for an image file. The image file is already present at your intended destination (a person's device), so why would you transmit the image to them again and again? -- Use emoji!

##♻ Green Technology ♻
An image file equivalent to an emoji symbol may be tens, hundreds of kilobytes in size, while an emoji symbol is only several bytes. That's a bandwidth saving of around 10,000 times. If you use emoji instead of image files, you reduce your carbon footprint.

##Plain Text Is Now 😎 Faux Rich Text
Now you can include emoji in plain text files, even in plain text emails, making them sharp, colourful and rich looking. You can put emoji flags into your database too!

##Emoji Support
Not every platform (hardware + OS) supports emoji. Therefore, use with caution! To my knowledge, iOS, macOS, Android are capable of displaying emoji. Additionally, some platforms may not be able to display certain flags. If unsure, use this as a reference and easy way to test your platform: <http://unicode.org/emoji/charts/full-emoji-list.html>

```php
require 'flagmaster.class.php';

# Single flag
echo flagMaster::emojiFlag('uk'); # 🇬🇧

# String of multiple flags
echo flagMaster::emojiFlag('ukcwsxap'); # 🇬🇧🇳🇱🇳🇱🏴

```

##Bonus Gift 🎁 -- SQL Emoji Flags
Use the extra file `update-table-flags.sql` to insert emoji flags into your SQL table. Make sure to use the following settings:

```php

$link = mysqli_connect($HOSTNAME, $USERNAME, $PASSWORD, $DBNAME);

mysqli_set_charset($link, "utf8mb4");

```