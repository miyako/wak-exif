wak-exif
========

Wakanda EXIF Module.

About
-----

The module includes [libexif](http://libexif.sourceforge.net) 0.6.21 executable for Mac and Windows x64, and Linux x64.

Example
-------
![](https://github.com/miyako/wak-exif/blob/master/images/1.png)

```js
var path = getFolder().path + 'Resources/' + 'Thailand.jpeg';
var modulesFolder = FileSystemSync('Modules');
var exif = require(modulesFolder.path + "exif");

exif.getXML(path);
```

**Note**: For other commands, consult --help of the exif tool.
