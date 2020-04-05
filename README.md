wak-exif
========

Wakanda EXIF Module.

About
-----

The module includes [libexif](http://libexif.sourceforge.net) 0.6.21 executable for Mac and Windows x64, and Linux x64.

![obsolete-word-black-frame-word-obsolete-word-black-frame-d-rendering-123942590](https://user-images.githubusercontent.com/1725068/78463940-29122280-771e-11ea-8be8-a7830725403e.jpg)

Old Wakanda.

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
