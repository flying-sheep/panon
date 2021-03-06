# Panon

A Different Audio Spectrum Analyzer

![](../../wiki/plasmoid/preview.png)

[Previews](../../wiki/Previews).

Dependencies
==
python-numpy python-pyaudio python-websockets qt5-websockets qt5-3d 

Installation
===========
```
python setup.py install --user
cd kde
kpackagetool5 -t Plasma/Applet --install plasmoid
```

Running
===
1. Start panon server.
```
python -m panon.server
```
2. Drag panon widget to your panel (eg. [latte-dock](https://github.com/psifidotos/Latte-Dock)).
![](../../wiki/plasmoid/step1.png)
![](../../wiki/plasmoid/step2.png)

Credits
======
Some code parts are adapted from [PyVisualizer](https://github.com/ajalt/PyVisualizer).
