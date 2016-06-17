# OctoPrint-FilamentPause
An OctoPrint plugin to use a 3D printed part and a switch to pause the machine when the filament runs out
OctoGlow Plugin
===============

This is a plugin for pause [OctoPrint](http://octoprint.org/) based upon input from an external filament switch


Requirements
------------
* Raspberry Pi or BeagleBoneBlack
* [Thingiverse thing # XXXXX](http://thingiverse.com)
* OctoPi 1.2.0+

Acknowledgements
----------------
FilamentPause uses Adafruit's [Adafruit_Python_GPIO module](https://github.com/adafruit/Adafruit_Python_GPIO)

Installing the Plugin
---------------------
Install the plugin like you would install any regular Python package from source:

``` bash
pip install https://github.com/dmalec/OctoPrint-FilamentPause/archive/master.zip
```

Make sure you use the same Python environment that you installed OctoPrint under, otherwise the plugin won't be able to satisfy its dependencies.

