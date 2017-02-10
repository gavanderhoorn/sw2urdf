# SolidWorks to URDF Exporter #

This repo is forked from Brawner's sw2urdf. Here is the [github](https://github.com/gavanderhoorn/sw2urdf) and [Bitbucket](https://bitbucket.org/brawner/sw2urdf) he contributes to.

## Environment ##

### Windows ###

IDE: Visual Studio 2013 Community

OS: Windows 10

SolidWorks: 2016 x64 Edition

### Xubuntu ###

ROS: ROS Kinetic

## Download ##

[Download Installer](https://github.com/Sayter99/sw2urdf/releases/download/v1.0/sw2urdfSetup.exe)

## Compile Source ##

Three things to be noticed:

1. Add Reference: add references of **SolidWorks.Interop.sldworks.dll**, **SolidWorks.Interop.swconst.dll**, **SolidWorks.Interop.swpublished.dll**, **solidworkstools.dll** from SolidWorks installation path.
2. Check SolidWorks Path: make sure the path of SolidWorks in **Project->properties->Debug->Start external program**.
3. Update Installer: use [inno setup](http://www.jrsoftware.org/isinfo.php) to run **INSTALL/install.iss**.

## Documents ##

Documents on [ROS Wiki](http://wiki.ros.org/sw_urdf_exporter)
