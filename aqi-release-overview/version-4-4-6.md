<!-- TITLE: (2010) Version 4.4.6 -->
<!-- SUBTITLE: A quick summary of Version 4.4.6 -->

# Version 4.4.6
## Scope
* This release is patch release.  Mainly bug fixes but some features are added.

## Aqi new features
* Plaque analysis
* Body fat analysis
* 3D setting usability improvements
* ~~iGentle low dose support~~
* Registration improvement
* Lock/Unlock cross hair
* Option to delete images on output panel after DICOM transfer is completed
* Ability to anonymize from Patient list without login to Web admin
* Invert WW/WL
* Original slice
* Option to display the original date on secondary capture
* Display patient info for imported data
* Ability to scroll through batch scout and results on patient list preview (separated to sub-series)
* Query improvements
* Option to load APS resutls by drag and drop
* Switch user group option at login
* Add table position (location) - 4.4.5 patch
* Ability to launch 3rd party application from AQi
* LD - Lubular Decomposition

### Measurement Protocol 
*    Ca, TVA, Stenosis support
*    Stenosis grade

### TDA
*    GE shuttle mode support
*    Import/export template
*    Color map improvement
*    Ability to process 320 TDA data without APS (TimeSeriesGenerator added to AqNET server)

### CPR
*    Vessel track improvement (color map, tangent view centerline, rendering mode)
*    Improved orientation on internal/external carotid arteries and renal arteries
*    Nudge tool on perpendicular MPR
*    Change sMPR profile range
*    Smooth centerline
*    ~~CCSA (BETA)~~

### EVAR
*    Overlay of thrombus on 3D

### Head and Neck bone removal
*    Head mount removal

### FT
*    Display CAD marker on perspective view
*    Show stool in different color
*    Usability improvements

### TVA
*    Automatic (all phases) option

### Workflow
*    WFE to remember render options for 3 basic windows
*    Copy validated WFEs to another workflow
*    Name Workflow Scene

### Batch 2D
*    Batch with half slab
*    Option to capture with scout image
*    Save as avi
*    Usability improvement to save as derived series
*    Server side capture (speed up batch)

### Measurement
*   Option to add initial and scanning date
*   Option to display all measurement tools and continuous use


## ThinClient new features
* Volume measurement
* Add table position (location) - 4.4.5 patch
### CT/PET improvement
*    3 time point
### Batch
*    Server side capture (speed up batch)

## APS new features
* Default clinical protocol updated
* [APS-ParametricMap] Handle the scan which includes both non-subtracted and subtracted data
* Auto anonymizer - Formal release
* Anonymize and download ability to open with free viewer for standalone APS
### Processor new/improvements
*    Volume Filter for (Noise Treatment with Less Exposure)
*    [iCAD] VeraLook v1.1 support 
*    Head mount removal
*   Auto body centerline improvement

## Web viewer (non-diagnostic viewer)
* Add table position (location)

## PACS integration
* Ability to load user settings after login with shared/shared (AQi)
* McKesson color scheme fix (AQi)

## AqGate
* AqGate fail over support
* Round-robin push (S4844 - Not tested yet 12/14/2010)
* Backup mode

## Others
* Multiple LDAP server configuration through web admin page  
* Export / Import user settings
* Ability to reclaim disk space
* Published link authentication exemption based on hostname or IP addresses
* Data deletion improvement (faster and safer)
* VCC support
* VMWare support
* Windows 2000 support as server backend
* Standalone web server (DMZ) - beta
### Multi-Language support
*    Portuguese support (AQi, ThinClient, AqNET Webadmin, Web viewer)
*    Chinese support for AqNET
*    German support for AqNET
*    French support for Free Viewer (non-diagnostic viewer) 
### iUploader
*    Compression
*    Standard SSL through https instead of custom encryption
### License
*    Standalone concurrent
*    Grace period reduced from 24 hrs to 2 hrs
*    License expiration date "permanent" instead of 12/31/2015"

---

# 4.4.6 Beta Features
## S4370 [TVA] Colored Motion
* "In ""C:\AQi\Bin\AQi.exe.config"", change ""EnableColoredMotion"" from ""False"" to ""True"".
* Load 4D data into Cardiac workflow. Do ""EF"".
* Confirm that ""Motion"" button is on the Result tab of control panel when calculation is done.
* Press ""Motion"". Confirm that ""Colored Motion"" dialog box pops up. Images play cine automatically until color map is displayed for systolic motion.
* Click on ""Diastolic"" radio button. Confirm that images play cine automatically until color map is displayed for diastolic motion."					

## "S4331 [SAT] Add surface area - Shape Compactness 
* "Load a lung study.
* Open SAT tool panel, click on ""New"" button, choose ""single click"" and ""nodule"" mode, ""shift""+click on a nodule seed point. 
* After the segmentation is done, measurement result will display. 
* Right click on measurement and select “show/hide details” 
* Check to add “Shape Compactness” and click OK
* Beta message will be displayed."					


## S3238 [TDA] Body CT Perfusion - BETA
* "In ""C:\AQi\Config\AQi.cfg, add ""EnableBetaFunction = True""
* Load body CT perfusion data into TDA (Body) workflow"					

## BFA 3D - BETA




