# Country Code To Emoji Flag 🇬🇧

[![Downloads](https://img.shields.io/packagist/dt/peterkahl/country-code-to-emoji-flag.svg)](https://packagist.org/packages/peterkahl/country-code-to-emoji-flag)
[![Download per Month](https://img.shields.io/packagist/dm/peterkahl/country-code-to-emoji-flag.svg)](https://packagist.org/packages/peterkahl/country-code-to-emoji-flag)
[![License](http://img.shields.io/:license-apache-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)
[![If this project has business value for you then don't hesitate to support me with a small donation.](https://img.shields.io/badge/Donations-via%20Paypal-blue.svg)](https://www.paypal.me/PeterK93)

Converts string of country codes to string of emoji flags. As an argument use a single 2-letter country code or a string of multiple codes.

## Example in action: Screenshot of emoji flags inside phpmyadmin table.
![image](https://github.com/peterkahl/country-code-to-emoji-flag/blob/master/screenshot-phpmyadmin-flags.png "Screenshot of emoji flags inside phpmyadmin table.")

## Example in action: Screenshot of a terminal window displaying a plain text log file.
![image](https://github.com/peterkahl/country-code-to-emoji-flag/blob/master/logfile-example.png "Screenshot of a terminal window displaying a plain text log file.")

## Why Emoji
Emoji symbol is a textual replacement for a graphic image file while having the benefits of a graphic image. The image file is already present at your intended destination (a person's device), so why would you transmit the image to them again and again? -- Use emoji!

## ♻ Green Technology ♻
An image file equivalent to an emoji symbol may be tens, hundreds of kilobytes in size, while an emoji symbol is only several bytes. That's a bandwidth saving of around 10,000 times. If you use emoji instead of image files, you reduce your carbon footprint.

## Plain Text Is Now 😎 Faux Rich Text
Now you can include emoji in plain text files, even in plain text emails, making them sharp, colourful and rich looking. You can put emoji flags into your database too!

## Emoji Support
Not every platform (hardware + OS) supports emoji. Therefore, use with caution! To my knowledge, iOS, macOS, Android are capable of displaying emoji. Additionally, some platforms may not be able to display certain flags. If unsure, use this as a reference and easy way to test your platform: <http://unicode.org/emoji/charts/full-emoji-list.html>

```php
use peterkahl\flagMaster\flagMaster;

echo flagMaster::emojiFlag('uk');    # 🇬🇧
echo flagMaster::emojiFlag('gbwls'); # 🏴󠁧󠁢󠁷󠁬󠁳󠁿
echo flagMaster::emojiFlag('gbsct'); # 🏴󠁧󠁢󠁳󠁣󠁴󠁿
echo flagMaster::emojiFlag('gbeng'); # 🏴󠁧󠁢󠁥󠁮󠁧󠁿

```
