### Unicode - encoding characters to numbers
Unicode assigns each character unique code point.

> Unicode - is a name of a standard

> code point - a number assigned to each character

Unicode code points are divided into 17 planes of 2^16 characters.

> BMP - Basic Multilingual Plane, code points from U+0000 to U+FFFF

### Unicode vs ISO/IEC 10646

That pretty much explains everything: http://en.wikipedia.org/wiki/Universal_Character_Set#Differences_between_ISO_10646_and_Unicode

### UTF, UCS etc.
UTF, UCS etc. assign Unicode code points to a binary representation.

> UTF - Unicode Transformation Format (Unicode standard) or UCS transformation format (ISO/IEC 10646 standard)

UTF is defined by Unicode and ISO/IEC 10646 standards (with some diffetences).

|Encoding|Unit size|No of units|Is variable length?|Byte order|Other|
|:------:|:-------:|:---------:|:-----------------:|:--------:|:---:|
|UTF-8|8 bits|1-4|Y|N/A||
|UTF-16|16 bits|1-2|Y|BOM||
|UTF-16BE|16 bits|1-2|Y|big-endian||
|UTF-16LE|16 bits|1-2|Y|little-endian||
|UTF-32|32 bits|1|N|BOM||
|UTF-32BE|32 bits|1|N|big-endian||
|UTF-32LE|32 bits|1|N|little-endian||
|UCS-2|16 bits|1|N||Replaced by UTF-16 in Unicode 2.0|
|UCS-4|32 bits|1|N|||

### Usages
|Operating system|Default encoding|
|:-:|:-:|
|Windows 2000/XP/2003/Vista/7/8/CE|UTF-16|
|Java 5+|UTF-16|
