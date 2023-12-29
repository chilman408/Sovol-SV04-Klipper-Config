# Sovol-SV04-Klipper-Config
This Klipper Config for Sovol SV04 Relies on Specific Modified Hardware YMMV

Specifically-
1.  Extruders are converted to E3D Hemera XS Revo
2.  Custom extruder mounts are needed to support the x-axis bed size
3.  Y-axis end stop is modified to get a few extra mm of space.
4.  Each axis (x1, x2 and y) have its own accelerometer which is Fysetc PIS
5.  The default DGUS screen that came with the SV04 is trashed; now uses a cheap GPIO screen with Klipperscreen

Much of the config found here is based on https://github.com/Bully85/Sovol-SV04-Klipper

Installation of Klipper is based on the main branch.
