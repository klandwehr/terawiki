<!-- TITLE: (2010) Version 4.4.5 -->
<!-- SUBTITLE: A quick summary of Version 4.4.5 -->

# Version 4.4.5
## Scope
* This release is patch release.  Mainly bug fixes but some features are added.

## Main feature or support that are prioritized for AQi
* Workflow improvements (multiple WFT import, re-order, additional default, workflow access log)
* EP lab workflow
* Option to use Min/Max instead of WW/WL
* Option to change date format to date/month/year
* Help function (English Manual) is available with "Fr-ca"
* Capture all in one 
* DICOM send sub-series
* Option not to update the patient list after retrieve
* Save as movie from output panel

### Flythtough 
*    Image quality improvement on VP1000 (needs APS)
*    Usablity and real-time updates of views improvements
*    Fast review mode (Skip segmentation and path edit, need APS results)
*    400-degree Flat view with overlay
*    Threshold setting for stool removal
*    Background color change on edit path mode
*    Flight path manual generation
*    Save movie as DICOM
*    CAD marker on perspective view (BETA)

### Measurement protocol 
*    AIM and Radlex support
*    Jump to location (Sagittal and coronal support)

### EVAR 
*    Measurement summary on sMPR/main view 
*    Vessel Outerwall - Plugin improvement

### SAT 
*    Shape compactness (BETA)
*    Smoother contour - plugin improvement

### TVA 
   Colored motion (BETA)
  3D polar map (outside Japan)

### TDA
*    Capture maps for all levels
*    Ability to show/hide curves in the graph
*    Adjust ROI templates to current maps

## ThinClient new features
### PET/CT improvement
*    SUV measurement formal release
*    Min/Max setting and preset for PET 
*    Spinning man and 2x2 layouts
*    SUV measurement on fused image
*    SUV with LBM and BSA
### Breast MR 
*    BIRADS report
*    Biopsy measurement

## APS new features
* Ability to add private tag
* Auto anonymizer improvements (BETA)
### Clinical protocols
*    TDA 
*    Deformable CT-CTA (BETA)
### Processor new/improvements
*    Dual Energy Virtual Non Contrast (BETA)
*    Colon data converter (for image quality improvement) 
*    Head and neck bone removal
*    Deformable registration (BETA)

## Others
* Security dicom uploader 
* Large database support
* Compressed MG support (DICOM send/receive/store)
* Anonymize - Ability to keep original patient ID
* Windows 2008 support
* Internet explorer 8 support
* Windows 7 support
* Emulator support for EVAR workflow with VLI4
* Temporary user account

### Job manager improvements
*    Email notification when certain queue's got too long or failed repeatedly

### Commandline
*    Load data with workflow template or element

---

# 4.4.5 Beta Features
## S4370 [TVA] Colored Motion

## "S3173 [CPR] Improvement for root definition
>Request to have better root definition to avoid the looping carotid issue. "
{.is-info}
## "S4331 [SAT] Add surface area - Shape Compactness 
>Request to have surface area by MUSC.  Instead of having surface area, shape index is added.  The value is normalized from 0 to 100. Value 100 means perfect sphere. "
{.is-info}
## S4308 [FT] Display CAD marker on perspective view (beta)


