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
* Goodrich / Sensors Unlimited
* Xenics
* Allied Vision Technologies


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
- **PIoNIR** InGaAs 2D camera for 400-1700nm 640x512px. PIoNIR employs powerful, thermoelectric (TE) peltier cooler (Air or Liquid assisted) for up to -90C cooling to reduce dark current. This is done without the use of liquid nitrogen for maintenance-free operation. Output format: Gigabit Ethernet (GigE), controlled by LightField software or Picam SDK. This model is, indeed, a focal plane array (FPA) a 2D photodiode array, 640x512 InGaAs focal plane array camera for visible and SWIR.


## Hamamatsu
- [**C5840**](http://sales.hamamatsu.com/en/products/system-division/cameras/part-c5840-10.php ) is a DISCONTINUED PRODUCT. covers 400-1600nm, but it is an analogic camera (analogic output): we will need a capturer card (frame grabber) to make measurements
- [**C10633-13**/**C10633-23**](http://sales.hamamatsu.com/index.php?id=13223961) is a 320x256px camera, with pixels of 30um size, without cooling, 900-1520nm. Datasheet is not very clear aboutoutput format: it has USB2.0 connector but also analogic output. Needs an external controller and frame-grabber??
- [**C10633-34**](http://sales.hamamatsu.com/en/products/system-division/systems-for-solar-cell-evaluation/si-ingot-inspection/part-c10633-34.php) covers 40-1520nm. It has more pixels (640x512px), but does not have USB, it has RS-232, and very low frame rate (1.6fps). Requires external controller and frame grabber. Requieres cooling peltier and water.

Hamamatsu catalog about these models are not very clear. It it not clear about controlling software. Comes free with camera? Can be LabView controlled?.


## Goodrich / Sensors Unlimited
[Web](http://www.sensorsinc.com/cameras.html) 640x512 focal plane array (FPA) InGaAs

SUI Image Analysis software is included on the support CD shipped with Goodrich cameras. Works with National Instruments frame-grabber cards via the LabVIEW® Run-time Engine when NI IMAQ imaging software driver is installed



## Xenics
Suggested cameras for laser beam profiling are:
- [**XS-1.7-320**](http://www.xenics.com/en/infrared_camera/visnir-nir_camera_-visual_near_and_near_infrared_cameras_-_ingaas/xs_near_ir_camera_-_ingaas_fpa.asp) 900-1700nm InGaAs FPA 320x256px, 30x30um pixel size, uncooled. Output by USB2.0, 60fps. Includes software _Xcontrol_ (which provides simple measurements, CVS output array, histograms...). Xeneth API/SDK includes Labview controls, but it is not clear id this software is included with camera. This camera is outdated.
- [**Bobcat-1.7-320**](http://www.xenics.com/en/infrared_camera/visnir-nir_camera_-visual_near_and_near_infrared_cameras_-_ingaas/bobcat_smart_nir_camera_-_ingaas_detector.asp) has similar specifications (900-1700nm InGaAs FPA 320x256px, uncooled), but small pixel (20x20um), embedded DSP.

Other cameras
- [**XEVA-1.7-320**](http://www.xenics.com/en/infrared_camera/visnir-nir_camera_-visual_near_and_near_infrared_cameras_-_ingaas/xeva_near_ir_night_vision_camera_-_thermo-electrically_te_cooled_ingaas_fpa.asp) 900-1700nm InGaAs FPA 320x256px, 30x30um pixel sixe, TEC cooled for super low dark current. Two gain modes. Output can be USB2.0 (100fps maximum) or CameraLink (350fps). Camera is delivered with a graphical user interface _X-Control_, which offers direct access to various camera settings such as exposure time and operating temperature. 
- [**XEVA-1.7-640**](http://www.xenics.com/en/infrared_camera/visnir-nir_camera_-visual_near_and_near_infrared_cameras_-_ingaas/xeva_near_ir_camera_-_high-res_-_ingaas_fpa.asp) provides more pixels but lower frame rate: 900-1700nm InGaAs FPA 640x512px, 20x20um pixel size, TEC cooled for super low dark current. Weight: 1.8kg. Four gain modes. Outputs: USB2.0 or CameraLink. Includes software Xcontrol.
- [**Cheetah-640CL**](http://www.xenics.com/en/infrared_camera/visnir-nir_camera_-visual_near_and_near_infrared_cameras_-_ingaas/cheetah_near_ir_camera_-_ingaas_fpa_camera_link.asp) 900-1700nm InGaAs 640x512px, cooling by Peltier. Special for high framerates: 1730fps with double channel CameraLink.

Xenics tiene distribuidor en España: (Infaimon)[http://www.infaimon.com/catalogo-industria/camaras-vision-artificial/camaras-infrarrojas-termicas-674.html]. Además, Infaimon alquila cámaras IR.


## Allied Vision Technologies
- Goldeye [**P-032 SWIR**](http://www.alliedvisiontec.com/emea/products/cameras/gigabit-ethernet/goldeye/p-032-swir.html) camera is a 900-1700nm InGaAs 636x508px, 25x25um, 30fps, peltier cooling. Outputs GigE, CameraLink as option.
- Goldeye [**P-008 SWIR**](http://www.alliedvisiontec.com/emea/products/cameras/gigabit-ethernet/goldeye/p-008-swir.html) camera is a 900-1700nm InGaAs 320x256px, 30x30um, 100fps, peltier cooling. Outputs GigE, CameraLink as option.

[Software](http://www.alliedvisiontec.com/emea/support/downloads/software.html) can be downloaded free of charge, but [no LabView drivers are provided](http://www.alliedvisiontec.com/fileadmin/content/PDF/Software/AVT_software/AVT_software_stuff/QuickSelector/AVTWindowsSDKComparision_v2.1.0.pdf).



## National Instruments
This [link](http://sine.ni.com/apps/utf8/nipc.specs?action=search&asid=1102) provides a list of tested cameras. CameraLink compatible cameras need a [file](http://digital.ni.com/public.nsf/allkb/05DCE3868362783586256FC8004F123C) with camera and [framegrabber](http://digital.ni.com/public.nsf/allkb/E16D3364AD5D8C1C862576160075AF93?OpenDocument) parameters. A [software](http://sine.ni.com/nips/cds/view/p/lang/en/nid/201791) is available to generate this file. A [FTP](ftp://ftp.ni.com/support/imaq/camera_support/camera_files/digital/) with generated files is available.

[Link a google](http://www.google.com)
