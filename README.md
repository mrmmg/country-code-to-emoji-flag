# Country Code To Emoji Flag
Converts string of country codes to string of emoji flags. As an argument use a single 2-letter country code or a string of multiple codes.

```php
require 'flagmaster.class.php';

# Single flag
echo flagMaster::emojiFlag('uk'); # 🇬🇧

# String of multiple flags
echo flagMaster::emojiFlag('ukcwsxap'); # 🇬🇧🇳🇱🇳🇱🏴

```