
# Windows EU-Intl Keyboard

A keyboard layout definition adding most European characters to a US-Intl keyboard layout.


## Purpose

Having only used the US Intl keyboard layout and trying to keep a database of my music collection which included many East-European album and song titles, I needed an easier way to type in all those characters so I set out to make a keyboard definition for that.

After I switched to Linux, where this was so much easier to do, I forgot about it. But now I am working with Windows again and living in Sweden, using a language that has a lot of `ä`-s, `ö`-s, and `å`-s, I had to dig up these definitions again.

Besides some accented letters I added some other UTF8 characters I sometimes need, like n-dash and m-dash, degrees sign, bullet, some mathematical signs.

Some different accents are combined under a single key, for example ç, ȩ, and ņ are all done with the comma.


## Dead Keys

All combinations are made using the right `Alt` key, also known as `AltGr` or `Alt-Ctrl`.


## Overview

| accent | description       | dead key         | key       | letters                                     |
| ------ | ----------------- | ---------------- | --------- | ------------------------------------------- |
| ´      | acute accent      | ' (apostrophe)   | a-z       | á é í ĺ ń ó ŕ ś ú ý ź Á É Í Ĺ Ń Ó Ŕ Ś Ú Ý Ź |
| `      | grave accent      | ` (back tick)    | a-z       | à è ì ǹ ò ù ẁ ỳ À È Ì Ǹ Ò Ù Ẁ Ỳ             |
| ̈       | umlaut, diaeresis | " (quote)        | a-z       | ä ë ï ö ü ẅ ÿ Ä Ë Ï Ö Ü Ẅ Ÿ                 |
| ˜      | tilde accent      | ~ (tilde)        | a-z       | ã ĩ ñ õ ũ Ã Ĩ Ñ Õ Ũ                         |
| ¸ ˛    | cedilla, ogonek   | , (comma)        | a-z       | ç ķ ņ ŗ ş ţ Ç Ģ Ķ Ļ Ņ Ŗ Ş Ţ ȩ Ȩ             |
| ˙ •    | dot above, bullet | . (period)       | a-z .     | ċ ė ġ ż Ċ Ė Ġ Ż •                           |
| / -    | dash, strike      | / (slash)        | a-z       | ł ø Ł Ø đ Đ ħ Ħ ŧ Ŧ                         |
| -      | currencies        | - (dash)         | e l y s c | € £ ¥ $ ¢                                   |
|        | dashes            | - (dash)         | n m       | – —                                         |
| =      | mathematical      | = (equals sign)  | / x +     | ÷ × ±                                       |
| &      | compounds         | &                | a o i     | æ Æ œ Œ ĳ Ĳ                                 |
| o      | ring              | o (small letter) | a u       | å ů Å Ů                                     |
|        | circle            | o (small letter) | c r p t   | © ® ℗ ™                                     |
|        |                   | o (small letter) | %         | ‰                                           |
| ^      |                   | ^                |           | â ĉ ê ĝ ĥ î ĵ ô ŝ û ŵ Â Ĉ Ê Ĝ Ĥ Î Ĵ Ô Ŝ Û Ŵ |
| +      | superscript signs | + (plus sign)    | o         | °                                           |

## Installation

The `EU-Intl.klc` file is the file to open with Microsoft Keyboard Layout Creator.

The `EU-Intl` directory contains the compiled DLLs and also the `msi` files to install the definitions.



## To Do

### Bugs

Dead key `&` is set to `7` (forgot to add Shift state).



### New

I'd like to add the following:

| character                            | dead key | key    |
| ------------------------------------ | -------- | ------ |
| ≈ (approximately equal)              | =        | =      |
| ≥                                    | =        | >      |
| ≤                                    | =        | <      |
| 1 as superscript (and other numbers) | +        | 1      |
| ˝ (double acute)                     | :        | letter |

