<!-- TITLE: Version 4.4.11 -->
<!-- SUBTITLE: A quick summary of Version 4.4.11 -->

# Version 4.4.11 Patch5/iNteract+1.2
## Scope
- Hyland iEMV integration support
- Tokushima consolidated patient list for multiple remote AqNet Servers with iReview (federated query part1)
- AQi memory fix for 3D lab deployment
- Folder UUID support for Teramedica
- Findings workflow evaluation improvement
- Merge AQi fix from 4.4.12 for install base customers
- Fix for Permanent license expiry on 2015/12/31 issue


## AQI/Plugin New Features
### TDA
- 3x3 layout for single level
- Capture all-in-one maps
### TVA (CT/MR)
- Normalized Volumes
### Findings Workflow
- non-target lesion to be PD if base is available
## Thin Client new features 
> N/A
{.is-danger}

## iReview new features
- C-find list merge to local - ability to show remote data in different color

## APS new features
> N/A
{.is-danger}

## iEMV/Web viewer (non-diagnostic viewer when used on mobile)
- Manual import for non-DICOM files
- 3x3 layout
- Hyland integration with authentication and color scheme support (bluegray) 
- Folder UUID support for TeraMedica


## PACS integration
> N/A
{.is-danger}

## Uploader / Cloud / iShare
> N/A
{.is-danger}

## Others
-Fix for Permanent license expiry on 2015/12/31 issue

# Version 4.4.11 Patch4a/iNteract+1.1
## Scope
* Address findings workflow RECIST 1.1 bug
* Batch file to disable use of AQi Ca
* Batch file to disable measurement on web viewer and iNtuitionMobile

## AQI/Plugin New Features
> N/A
{.is-danger}

## Thin Client new features 
> N/A
{.is-danger}

## iReview new features
> N/A
{.is-danger}

## APS new features
> N/A
{.is-danger}

## iEMV/Web viewer (non-diagnostic viewer when used on mobile)
> N/A
{.is-danger}

## PACS integration
> N/A
{.is-danger}

## Uploader / Cloud / iShare
> N/A
{.is-danger}

## Others
> N/A
{.is-danger}

# Version 4.4.11 Patch4/iNteract+1.1
## Scope
* iNteract+ 1.1
* iEMV usability improvement - maximize viewing area
* iEMV 2 color scheme support
* MINT support with TeraMedica
* Non-DICOM integrated viewer support for iReview and iEMV
* iEMV/Web viewer rebranding for TeraMedica

## AQI/Plugin New Features
- Load balance based on volume loading to support 3D, 4D data loading and call plugins properly

## Thin Client new features 
> N/A
{.is-danger}

## iReview new features
- Ability to set default filter for remote nodes

## APS new features
> N/A
{.is-danger}

## iEMV/Web viewer (non-diagnostic viewer when used on mobile)
* Maximize viewing area 
* Ability to take default filter set for remote nodes on iReview
* Color scheme support - greengray & aquagray
* Rebranding for Teramedica

## PACS integration
> N/A
{.is-danger}

## Uploader / Cloud / iShare
- Ability to edit two private tages in the dicom data uploaded

## Others
* One box to set hostname/ip for dicom node 
* Checksum tool to check integrity of the binaries during transmission and storage
* Tokushima ATNA log output support

# Version 4.4.11 Patch3/iNteract+1.0
## Scope
* Release of LD2 semi auto lobular decomposition
* iEMV launch from EMR link with authentication

## AQI/Plugin New Features
* LD2 - semi-auto lobular decomposition
* TVA MR - contour detection improvements
* Web-based report (limited support) & default off

## Thin Client new features 
* More 2D color templates by default

## iReview new features
* Display protocols by default
* iReview launch from web browser
* Default sort order
* Mouse cursor color mode option

## APS new features
> N/A
{.is-danger}

## iEMV/Web viewer (non-diagnostic viewer when used on mobile)
* Diagnostic use on web browser
* iEMV launch from EMR link with authentication

## PACS integration
* Agility fusion launch support

## Uploader / Cloud / iShare
* User rights “Restrict rights to file upload only” should not be able to access to web admin 

## Others
* AqNetHL7 service (sending of publish/unpublish message only)


# Version 4.4.11 Patch2
## Scope
* Better CMR 
* Findings Wrokflow improvements
* AGFA Agility integration support
* Lesion Specific Analysis (LSA)
## AQI/Plugin New Features
* Better CMR
* ~~Delayed enhancement (BETA)~~
* Lesion Specific Analysis, LSA
* 3 direction batch 2D
* Workflow template categorization
* PET & SUV support
* Multi-modality fusion (1st phase) - limited layout/features compare to ThinClient
* LowAtt Area measurement (LAA)
* FT usability improvements
* Finding workflow improvements
* ~~Auto lobe segmentation (Liver, Lung) (BETA)~~
* ~~Vertebral / rib cage labeling (BETA)~~
* ~~CT/SPECT fusion (BETA)~~
* ~~LAA scoring (BETA)~~
* ~~Embedded Geometry (BETA)~~
* ~~Multi-touch support & Shift+Ctrl GUI (BETA)~~
* ~~Finding workflow - Measurement on follow up (simple, candidates) (BETA)~~
* ~~Color candidate marker (BETA)~~
* ~~Multi-mask - exclude masks (BETA)~~
* ~~EF measurement (BETA)~~
* ~~Web base report (BETA)~~

## Thin Client new features 
> N/A
{.is-danger}

## iReview new features
* Usability improvements

## APS new features
* TDA-PE: Save artery/vein locations, series description to add # of phases
* Volume filter options for view image vs generate PE results
* ADC map (BETA)
* DTI (BETA)

## iEMV/Web viewer (non-diagnostic viewer when used on mobile)
* iEMV non-DICOM file import
* iEMV multi-selection retrieve
* iEMV integration related support (i.e. iNteract+)
* Web Viewer- 2D viewer
* http option (both iEMV and AqWeb/web viewer)

## PACS integration
* AGFA Agility integration support

## Uploader / Cloud / iShare
> N/A
{.is-danger}

## Others
* VPCuda support 
* Patent link and CE mark 
* DICOM Query

# Version 4.4.11 Patch1

## Scope
* Integrated CMR 
* Findings Wrokflow improvements
* Transcatheter Aortic Valve Implementation (TAVI) Workflow support
* ~~Lesion Specific Analysis (LSA) - BETA ~~
* AGFA Agility integration support
* FDA warning support

## AQI/Plugin New Features
### CMR
*    Launch iReview from WFE
*    ~~Delayed enhancement (BETA)~~
*    Conrour edit usability improvements
*    Phase sort from patient list
*    Color-coded speed overlay on flow

### Findings Workflow
*    RECIST criteria check for QC
*    Volume histogram support
### TAVI Workflow
*    TAVI workflow template
*    3 landmarks to set orientation
*    Measurement protocol support

### TDA MR
- GE Data Support

### ~~Lesion Specific Analysis (LSA) - BETA~~
### BFA 3D (out of beta)
### LD2
* Auto segmentation engine options 
* Option to select territory within cut or segmenataion

## Thin Client new features 
### CT/PET
* SUV ratio on Fusion mode and bug fixes

## iReview new features
* Merge 4.4.8 p1 items to 4.4.11 p1

## APS new features
* ~~ADC map (BETA)~~
* Parametric map PE to take subtracted data
* TDA PE - 4 in 1 map 
* Auto body centerline - more vessels (e.g. celiac, sma)
* Rigid Registration improvement

## iEMV/Web viewer (non-diagnostic viewer when used on mobile)
* Merge 4.4.8 p1 items to 4.4.11 p1 


## PACS integration
* AGFA Agility integration support
* Bug fixes

## Uploader / Cloud / iShare
> N/A
{.is-danger}

## Others
* More pop up dialogs (notes and warnings)
* SWL merge (4.4.6 SWL 2 - 4.4.6.117)
