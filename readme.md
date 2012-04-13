###Base64.js -- A simple Base64 encode & decode

####Install

`npm install base64js`

####API

#####**decode**( base64String, fileName, next )

* `base64String`: the string you want to decode
* `filename`: the filename you want to save
* `next`: the callback when decoding is finished, The callback will be given one argument ( `err` )
#####**encode**( filename, next )  

`filename`: the name of the file you want to encode
`next`: the callback when encoding is finished. The callback will be given two arguments ( `err`, `base64String` ), where `base64String` is the encoded string. 