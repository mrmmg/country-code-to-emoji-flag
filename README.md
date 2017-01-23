#Country Code To Emoji Flag
Converts string of country codes to string of emoji flags. As an argument use a single 2-letter country code or a string of multiple codes.

##Green Technology
Emoji symbol is a replacement for an image file. An image file equivalent to an emoji symbol may be tens, hundreds of kilobytes in size, while an emoji symbol is only several bytes. That's a bandwidth saving around 10,000 times! If you use emoji instead of image files, you reduce your carbon footprint!

```php
require 'flagmaster.class.php';

# Single flag
echo flagMaster::emojiFlag('uk'); # 🇬🇧

# String of multiple flags
echo flagMaster::emojiFlag('ukcwsxap'); # 🇬🇧🇳🇱🇳🇱🏴

```