# Buying an IR camera for 1300 and 1550nm range

This is a list of camera manufacturers:
* Thorlabs
* Newport
* DataRay
* EdmundOptics
* Spiricom
* ElectroPhysics
* BaySpec
* Andor Technology
* Princenton Instruments
* Hamamatsu


## Thorlabs
CCD and CMOS cameras from [Thorlabs](http://www.thorlabs.com) are only for VIS-NIR range (400-900nm typical, some reach 1100nm).


## Newport
Only one model covers required ranges: **LBP4** beam profiler. Manufacturer declares that camera covers 350-1310 & 1550nm range. It is a CCD camera with an additional conversion coating (conversion phosphor?) sensible at 1550nm+/-50nm.

## DataRay
Dataray cameras are available at three ranges: standard (350-1150nm), -1310 model (350-1350nm) and -NIR model (1480-1680nm uses covnersion phosphor).
Study this models: WinCamD-UCD12-NIR, WinCamD-UCD23-NIR, WinCamD-UHR-NIR, TaperCamD-UCD12-NIR, TaperCamD20-15-UCD23-NIR

## EdmundOptics
Edmund has two approaches for desired range.
- Using a standard VIS CCD camera, Edmund sells an High REsolution 1550nm converter (**NT56-764**), it is a NIS-to-visible conversion phosphor layer
- An specific camera for 1550nm only.

## Spiricom
Spiricom sells model **SP-1550M**, for 1550nm only (phosphor layer).

## ElectroPhysics
- **IRE-320S** for 800-2500nm range, with digital output
- **MicroViewer** for 400-1900nm

## BaySpec
**Nuvanut** series, cooled InGaAs camera, three models: 900-1700nm, 1100-2200nm, 1250-2500nm


## Andor Technology
**iDus** InGaAs linear photodetector array (PDA) is not a 2D-camera. For 800-2200nm needs cooling (Water or TEC). It has a 512 or 1024 elements. Designed for spectroscopy.


## Princenton Instruments
Has two possible solutions:
- **OMAV** linear array or discrete photodiodes (PDA), for 1000-2000nm spectroscopy
- **PIoNIR** InGaAs 2D camera for 400-1700nm 640x512px. PIoNIR employs powerful, thermoelectric (TE) peltier cooler (Air or Liquid assisted) for up to -90C cooling to reduce dark current. This is done without the use of liquid nitrogen for maintenance-free operation. Output format: Gigabit Ethernet (GigE), controlled by LightField software or Picam SDK. This model is, indeed, a focal plane array (FPA) a 2D photodiode array.


## Hamamatsu
- **C5840* covers 400-1600nm, but it is an analogic camera (analogic output): we will need a capturer card (frame grabber) to make measurements
- **C10633-13**/**C10633-23** is a 320x256px camera, with pixels of 30um size, without cooling, 900-1520nm. Datasheet is not very clear aboutoutput format: it has USB2.0 connector but also analogic output. Needs an external controller and frame-grabber??
- **C10633-34** covers 40-1520nm. It has more pixels (640x512px), but does not have USB, it has RS-232, and very low frame rate (1.6fps). Requires external controller and frame grabber. Requieres cooling peltier and water.

Hamamatsu catalog about these models are not very clear. It it not clear about controlling software. Comes free with camera? Can be LabView controlled?.



[Link a google](http://www.google.com)