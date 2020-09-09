
# Windows EU-Intl Keyboard

A keyboard layout definition adding most European characters to a US-Intl keyboard layout.


## Purpose

Having only used the US Intl keyboard layout and trying to keep a database of my music collection which included many East-European album and song titles, I needed an easier way to type in all those characters so I set out to make a keyboard definition for that.

After I switched to Linux, where this was so much easier to do, I forgot about it. But now I am working with Windows again and also living in Sweden, using a language that has a lot of `ä`-s, `ö`-s, and `å`-s, I had to dig up these definitions again.

Besides some accented letters I added some other UTF8 characters I sometimes need, like n-dash and m-dash, degrees sign, bullet, some mathematical signs.

Some different accents are combined under a single key, for example ç, ȩ, and ņ are all done with the comma.


## Dead Keys

All combinations are made using the right `Alt` key, also known as `AltGr` or `Alt-Ctrl`. When you use this and press one of the defined keys, that key becomes a dead key. It doesn't do anything right away but it modifies the key that follows.

Normally, when you type an apostrophe, you get an apostrophe. When you press and hold the `AltGr`, press the `'`, and then release the `AltGr` key, the apostrophe has turned into a dead key. The key that you press after this will become modified, provided a modification has been defined.

So to type `á`, you type the dead key `'` and then the `a`. This means: you press and hold the `AltGr`, press the `'`, and then you let go of the `AltGr` key. Then you press the `a` key.


## Overview

| accent | description       | dead key         | key       | letters                                     |
| ------ | ----------------- | ---------------- | --------- | ------------------------------------------- |
| ´      | acute accent      | ' (apostrophe)   | a-z       | á é í ĺ ń ó ŕ ś ú ý ź<br />Á É Í Ĺ Ń Ó Ŕ Ś Ú Ý Ź |
| `  | grave accent | ` (back tick) |a-z|à è ì ǹ ò ù ẁ ỳ<br />À È Ì Ǹ Ò Ù Ẁ Ỳ|
| ̈       | umlaut, diaeresis | " (quote)        | a-z       | ä ë ï ö ü ẅ ÿ Ä Ë Ï Ö Ü Ẅ Ÿ                 |
| ˜      | tilde accent      | ~ (tilde)        | a-z       | ã ĩ ñ õ ũ Ã Ĩ Ñ Õ Ũ                         |
| ¸ ˛    | cedilla, ogonek   | , (comma)        | a-z       | ç ķ ņ ŗ ş ţ Ç Ģ Ķ Ļ Ņ Ŗ Ş Ţ ȩ Ȩ             |
| ˙    | dot above | . (period)       | a-z     | ċ ė ġ ż Ċ Ė Ġ Ż                           |
| • | bullet | . (period) | . | • |
| / -    | dash, strike      | / (slash)        | a-z       | ł ø Ł Ø đ Đ ħ Ħ ŧ Ŧ                         |
| -      | currencies        | - (dash)         | e l y s c | € £ ¥ $ ¢                                   |
|        | dashes            | - (dash)         | n m       | – —                                         |
| =      | mathematical      | =  | / x +     | ÷ × ±                                       |
| &      | compounds         | &                | a o i     | æ Æ œ Œ ĳ Ĳ                                 |
| o      | ring              | o (small letter) | a u       | å ů Å Ů                                     |
|        | circle            | o (small letter) | c r p t   | © ® ℗ ™                                     |
|        |                   | o (small letter) | %         | ‰                                           |
| ^      |                   | ^                |           | â ĉ ê ĝ ĥ î ĵ ô ŝ û ŵ<br />Â Ĉ Ê Ĝ Ĥ Î Ĵ Ô Ŝ Û Ŵ |
| +      | superscript signs | + (plus sign)    | o         | °                                           |

Because in Swedish, the ä, ö, and å are very common, I added extra shortcuts for these:

| character | dead key | key  | shortcut combination |
| --------- | -------- | ---- | -------------------- |
| ä         | "        | a    | `AltGr` `j`          |
| ö         | "        | o    | `AltGr` `k`          |
| å         | o        | a    | `AltGr` `l`          |



## Installation

The `EU-Intl.klc` file is the file to open with Microsoft Keyboard Layout Creator. From there you can compile the DLLs and installation files yourself.

The `EU-Intl` directory contains the compiled DLLs and also the `msi` files to install the definitions.



## To Do

### Bugs

~~Dead key `&` is set to `7` (forgot to add Shift state).~~



### New

I'd like to add the following:

| character                            | dead key | key    |
| ------------------------------------ | -------- | ------ |
| ≈ (approximately equal)              | =        | =      |
| ≥                                    | =        | >      |
| ≤                                    | =        | <      |
| 1 as superscript (and other numbers) | +        | 1      |
| ˝ (double acute)                     | :        | letter |

