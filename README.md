# Solitaire-UT
Klondike Solitaire for Mobile devices

This is a slight modification of the Ubuntu Touch version intended for use on Plasma Mobile, Phosh, etc.

## Usage
So long as QtMultimedia and QtQuick are installed, and the "qml6" or "qml-qt6" binaries are accessible, the game can be launched with:

```
$ qml6 qml/main.qml
```

A solitaire.desktop file is provided, though it will likely require tailoring depending on platform.

Of course, this can also be launched on a regular Xorg/Wayland DE, but the scaling is intended for high DPI mobile devices.
