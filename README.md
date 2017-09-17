This is a fork of https://github.com/nirbheek/youtube-ass with bug fixed

## Download the youtube annotation xml
```sh
youtube-dl --write-annotations <VIDEO_URL>
```

## Convert xml to ass subtitle
```sh
./youtube-xml2ass.py YOUR_XML_FILE.xml
```

Bug fixed of the fork
======
* Python2/3 supported
* UTF-8 characters supported
* Using '16777215' as white color instead of '1'
* Escape '\n' in the  xml text area
* Format floating number to two decimal points
