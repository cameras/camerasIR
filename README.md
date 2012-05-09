# Buying an NIR-SWIR camera for 1300 and 1550nm wavelengths

This is a list of camera manufacturers:
* Thorlabs
* Newport
* DataRay
* EdmundOptics
* Ophir Optronics / Spiricon
* FLIR Systems
* Princenton Instruments
* Hamamatsu
* Goodrich / Sensors Unlimited
* Xenics
* Allied Vision Technologies


## Thorlabs
CCD and CMOS cameras from [Thorlabs](http://www.thorlabs.com/navigation.cfm?guide_ID=2025) are only for VIS-NIR range (400-900nm typical, some reach 1100nm).


## EdmundOptics
Edmund only has products for VIS, and some solutions for 1550nm:
- Using a standard VIS CCD camera, Edmund sells an High REsolution 1550nm converter [**NT56-764**](http://www.edmundoptics.com/lasers/laser-measurement/infrared-ir-ultraviolet-uv-viewers/high-resolution-1550nm-converter-for-ccd-cameras/2418), it is a NIS-to-visible conversion phosphor layer
- An specific camera for 1550nm only.



## Newport
Only one model covers required ranges: [**LBP4** beam profiler](http://www.newport.com/Laser-Beam-Profiler/318103/1033/info.aspx). Manufacturer declares that camera covers 350-1310 & 1550nm range. It is a CCD camera with an additional conversion coating (conversion phosphor?) sensible at 1550nm+/-50nm.


## DataRay
Dataray cameras are available at three ranges:
-  standard (350-1150nm)
- -1310 model (350-1350nm)
- -NIR model (1480-1680nm, uses conversion phosphor).
Indeed, _-NIR_ model is only useable in 1550nm window!.

[WinCamD](http://www.dataray.com/index.php?cPath=2_9), [BladeCam](http://www.dataray.com/index.php?cPath=2_11) and [TaperCamD](http://www.dataray.com/index.php?cPath=2_27) are USB2.0 powered cameras with CCD & CMOS array sensors.

DataRay software can interface with [third-party software](http://www.dataray.com/support10.php).
LabVIEW software is [free available](http://www.dataray.com/UserFiles/file/WinCamVi.zip) for WinCamD.



## Ophir Optronics / Spiricom
Spiricom sells model [**SP-1550M**](http://www.ophiropt.com/laser-measurement-instruments/beam-profilers/products/industrial-applications/the-cameras/sp-1550m), for 1550nm only (phosphor layer).



## FLIR Systems
- [**Alpha NIR**](http://www.flir.com/uploadedFiles/CVS/Markets/Legacy/Documents/Alpha%20NIR%20Indigo.pdf) OBSOLETED InGaAs focal plane array (FPA), 320x256px, 30x30um pixel, 900-1700nm. Peltier stabilization to 0ºC. Output: 12 bit parallel._Alpha NIR_ camera is designed to use with National Instruments digital image acquisition board (IMAQ). FLIR provides software and hardware in the form of a LabVIEW virtual instrument (aka __IRvista__), IMAQ board and diital cable interface. Virtual instrument controls integration time setting, gain and other sensor parameters. The system allows the user to acquire and display 12-bit digital image data, change camera settings, calibrate camera and analyze the acquired data. FLIR also offers a comprehensive LabVIEW toolkit for users who wish to develop custom applications with **Alpha NIR**.
- [**Tau SWIR**](http://www.flir.com/cvs/cores/view/?id=51890) http://www.flir.com/cvs/cores/view/?id=51890&collectionid=602&col=51889 para montadores OEM. 640x512px.




## Princenton Instruments
Has two possible solutions:
- **OMAV** linear array or discrete photodiodes (PDA), for 1000-2000nm spectroscopy
- [**PIoNIR**](http://www.princetoninstruments.com/products/imcam/pionir/) InGaAs 2D camera for 400-1700nm 640x512px. PIoNIR employs powerful, thermoelectric (TE) peltier cooler (Air or Liquid assisted) for up to -90C cooling to reduce dark current. This is done without the use of liquid nitrogen for maintenance-free operation. Output format: Gigabit Ethernet (GigE), controlled by LightField software or Picam SDK. This model is, indeed, a focal plane array (FPA) a 2D photodiode array, 640x512 InGaAs focal plane array camera for visible and SWIR.


## Hamamatsu
- [**C5840**](http://sales.hamamatsu.com/en/products/system-division/cameras/part-c5840-10.php ) is a DISCONTINUED PRODUCT. covers 400-1600nm, but it is an analogic camera (analogic output): we will need a capturer card (frame grabber) to make measurements
- [**C10633-13**/**C10633-23**](http://sales.hamamatsu.com/index.php?id=13223961) is a 320x256px camera, with pixels of 30um size, without cooling, 900-1520nm. Datasheet is not very clear aboutoutput format: it has USB2.0 connector but also analogic output. Needs an external controller and frame-grabber??
- [**C10633-34**](http://sales.hamamatsu.com/en/products/system-division/systems-for-solar-cell-evaluation/si-ingot-inspection/part-c10633-34.php) covers 40-1520nm. It has more pixels (640x512px), but does not have USB, it has RS-232, and very low frame rate (1.6fps). Requires external controller and frame grabber. Requieres cooling peltier and water.

Hamamatsu catalog about these models are not very clear. It it not clear about controlling software. Comes free with camera? Can be LabView controlled?.





## Goodrich / Sensors Unlimited
Have many submodels in [website](http://www.sensorsinc.com/cameras.html)

Sus productos pueden presentar [restricciones a la exportación](http://www.sensorsinc.com/downloads/notes_ITAR_restrictions.pdf).

#### KT-Family
- [**SU640KTSX-1.7RT**](). [**SU640KTS-1.7RT**](http://www.sensorsinc.com/downloads/SU640KTS.pdf) meets CE requirements, AGC and NUC corrections, 30fps, EIA170, CameraLink 12bits and RS232 for commands and controls. Both 640x512px, 900-1700nm, 25um, for laser beam profiling. M42x1 mount with FD adaptor and C-mount lens included. 16mmx12.8mm
- for pulses events [**SU320KTS-1.7RT**](http://www.sensorsinc.com/downloads/SU320KTS-SU320KTSVIS.pdf) and [**SU320KTSVis**](http://www.sensorsinc.com/downloads/SU320KTS-SU320KTSVIS.pdf). 320px
- Windowing Camera for very high framerate [SU320KTSW-1.7RT and SU320KTSWVis](http://www.sensorsinc.com/downloads/SU320KTSW-SU320KTSWVis.pdf)
- for high sensitivity [**SU320KTSX-1.7RT**](http://www.sensorsinc.com/downloads/SU320KTSX.pdf). 900-1700nm, 320x256px, 25um, wide dynamic range.
- for high sensitivity for passive surveillance and use with lasers [**SU320KTX-1.7RT**](http://www.sensorsinc.com/downloads/SU320KTX.pdf)

#### SD-Family
-  High sensitivity [**SU640SDX-1.7RT**](http://www.sensorsinc.com/downloads/SU640SDX.pdf) 640x512px, AGC and NUC.
- Windowing Camera high frame rate [**SU640SDWH-1.7RT** and -Vis](http://www.sensorsinc.com/downloads/SU640SDWH.pdf) 15000fps with four ports.
- Area Camera [**SU640SDV-1.7RT** and -Vis](http://www.sensorsinc.com/downloads/SU640SDV-SU640SDVVis.pdf)

#### J-Family
- Military Rugged [**GA1280J**](http://www.sensorsinc.com/downloads/4110-0273%20GA1280J-15B%204_27_12.pdf) 1280x1024px, 15umpitch, 30fps, 900 to 1700nm or 700 to 1700nm. AGC and NUC. CameraLink 12bits (3M SDR26 connector). M42x1 mount lens. 19x15mm active area
- Military Rugged [**GA640C-15**](http://www.sensorsinc.com/downloads/4110-0289%20GA640C%204_27_12.pdf) 640x512px 15um pitch CameraLink 12bits, 900 to 1700nm or 700 to 1700nm Lens mount M15x0.5. 9.6x7.7mm active area.

#### H-Family [**SU640HSX-1.7RT**](http://www.sensorsinc.com/downloads/4110-0252%20640HSX%204_27_12.pdf) 640x512px. [**SU320HX-1.7RT**](http://www.sensorsinc.com/downloads/4110-0246%20320HX%20Sales%20Sheet.pdf) 320x240px, 40um. Both uncooled, Mil-Hardened, surveillance and maritime applications. AGC, NUC, Simultaneous RS170 analog and CameraLink 12bit. M42-1 to C-mount adapter.




SUI Image Analysis software is included on the support CD shipped with Goodrich cameras. Works with National Instruments frame-grabber cards via the LabVIEW® Run-time Engine when NI IMAQ imaging software driver is installed

SU320-1.7RT supported in [National Instruments website](http://sine.ni.com/apps/utf8/nipc.product?pid=2062&asid=1102).





## Xenics
Suggested cameras for laser beam profiling are:
- [**XS-1.7-320**](http://www.xenics.com/en/infrared_camera/visnir-nir_camera_-visual_near_and_near_infrared_cameras_-_ingaas/xs_near_ir_camera_-_ingaas_fpa.asp) 900-1700nm InGaAs FPA 320x256px, 30x30um pixel size, uncooled. Output by USB2.0, 60fps. Includes software _Xcontrol_ (which provides simple measurements, CVS output array, histograms...). Xeneth API/SDK includes Labview controls, but it is not clear id this software is included with camera. This camera is outdated.
- [**Bobcat-1.7-320**](http://www.xenics.com/en/infrared_camera/visnir-nir_camera_-visual_near_and_near_infrared_cameras_-_ingaas/bobcat_smart_nir_camera_-_ingaas_detector.asp) has similar specifications (900-1700nm InGaAs FPA 320x256px, uncooled), but small pixel (20x20um), embedded DSP. Output: ethernet or CameraLink.

Other cameras
- [**XEVA-1.7-320**](http://www.xenics.com/en/infrared_camera/visnir-nir_camera_-visual_near_and_near_infrared_cameras_-_ingaas/xeva_near_ir_night_vision_camera_-_thermo-electrically_te_cooled_ingaas_fpa.asp) 900-1700nm InGaAs FPA 320x256px, 30x30um pixel sixe, TEC cooled for super low dark current. Two gain modes. Output can be USB2.0 (100fps maximum) or CameraLink (350fps). Camera is delivered with a graphical user interface _X-Control_, which offers direct access to various camera settings such as exposure time and operating temperature. 
- [**XEVA-1.7-640**](http://www.xenics.com/en/infrared_camera/visnir-nir_camera_-visual_near_and_near_infrared_cameras_-_ingaas/xeva_near_ir_camera_-_high-res_-_ingaas_fpa.asp) provides more pixels but lower frame rate: 900-1700nm InGaAs FPA 640x512px, 20x20um pixel size, TEC cooled for super low dark current. Weight: 1.8kg. Four gain modes. Outputs: USB2.0 or CameraLink. Includes software Xcontrol.
- [**Cheetah-640CL**](http://www.xenics.com/en/infrared_camera/visnir-nir_camera_-visual_near_and_near_infrared_cameras_-_ingaas/cheetah_near_ir_camera_-_ingaas_fpa_camera_link.asp) 900-1700nm InGaAs 640x512px, cooling by Peltier. Special for high framerates: 1730fps with double channel CameraLink.

Xenics tiene distribuidor en España: [Infaimon](http://www.infaimon.com/catalogo-industria/camaras-vision-artificial/camaras-infrarrojas-termicas-674.html). Además, Infaimon [alquila cámaras IR](http://www.infaimon.com/catalogo-ciencia/camaras-para-entornos-cientificos/camaras-infrarrojas-termicas/alquiler-camaras-infrarrojas-744.html).



## Allied Vision Technologies
- Goldeye [**P-032 SWIR**](http://www.alliedvisiontec.com/emea/products/cameras/gigabit-ethernet/goldeye/p-032-swir.html) camera is a 900-1700nm InGaAs 636x508px, 25x25um, 30fps, peltier cooling. Outputs GigE, CameraLink as option.
- Goldeye [**P-008 SWIR**](http://www.alliedvisiontec.com/emea/products/cameras/gigabit-ethernet/goldeye/p-008-swir.html) camera is a 900-1700nm InGaAs 320x256px, 30x30um, 100fps, peltier cooling. Outputs GigE, CameraLink as option.

[Software](http://www.alliedvisiontec.com/emea/support/downloads/software.html) can be downloaded free of charge, but [no LabView drivers are provided](http://www.alliedvisiontec.com/fileadmin/content/PDF/Software/AVT_software/AVT_software_stuff/QuickSelector/AVTWindowsSDKComparision_v2.1.0.pdf).




## National Instruments
This [link](http://sine.ni.com/apps/utf8/nipc.specs?action=search&asid=1102) provides a list of tested cameras. CameraLink compatible cameras need a [file](http://digital.ni.com/public.nsf/allkb/05DCE3868362783586256FC8004F123C) with camera and [framegrabber](http://digital.ni.com/public.nsf/allkb/E16D3364AD5D8C1C862576160075AF93?OpenDocument) parameters. A [software](http://sine.ni.com/nips/cds/view/p/lang/en/nid/201791) is available to generate this file. A [FTP](ftp://ftp.ni.com/support/imaq/camera_support/camera_files/digital/) with generated files is available.


