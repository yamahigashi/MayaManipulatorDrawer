# Manipurator drawer for Autodesk Maya

What is this?
-------------
Custom render override plugin for drawing manipulator even during playback for Autodesk Maya.
![XSI Man](https://raw.githubusercontent.com/yamahigashi/MayaManipulatorDrawer/master/doc/ss.gif)

### Limitation

Maya2017+, VP2.0 needed.

Install
-------

### before maya launch

* [Download Source code (zip)](https://github.com/yamahigashi/MayaManipulatorDrawer/releases/latest) from release page and extract .zip to (e.g. C:\someplace\MayaManipulatorDrawer)
* Edit maya.env and add MAYA_MODULE_PATH with this module like below or append this extracted folder to `MAYA_MODULE_PATH`.

```file:bat
MAYA_MODULE_PATH=C:\someplace\MayaManipulatorDrawer
```

or

```bat
MAYA_MODULE_PATH=some\great\module;C:\someplace\MayaManipulatorDrawer
```


### after launch maya
* Activate sceneRenderOverride.py in the `Plug-in Manager` window.
* Switch viewport Renderer to `Manipulator drawer` to take effect.


### Notice
Manipulators size of all viewport will be applied to the current active one.

### You may also like...
* https://github.com/ShikouYamaue/SISideBar
* https://github.com/mochio326/SiShelf
* https://redglasses67.jimdo.com/2017/04/16/maya-displayselectedname/
* https://github.com/yamahigashi/MayaStickySupraTool

---

## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)
