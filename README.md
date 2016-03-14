# xml2js-cli
xml2js command line interface version

## Description

Simple XML to JavaScript object converter. Uses [node-xml2js](https://github.com/Leonidas-from-XIV/node-xml2js).

### Usage:
````sh
Usage:
xml2js [-h]
options:
        -h print this help
````

### Sample
````sh
echo '<a><nested>Hello</nested><b>world</b></a>' | xml2js

{
 "a": {
  "nested": "Hello",
  "b": "world"
 }
}
````