<!-- TITLE: Version 4.4.12 -->
<!-- SUBTITLE: A quick summary of Version 4.4.12 -->

# Version 4.4.12
## Scope
Major maintenance release for iNtuition

## AQI/Plugin New Features
### Cardiac MR TVA
- Short/long axis view with reference lines
- 3 click input to define left ventricle
- Export polar map values
- Normalized volume

### Cardiac MR Flow
- Baseline correction by ROI

### Cardiac MR Delayed Enhancement
- RSNA version required Aquarius CMR but with this release no license is checked, but will be licensed from patch1 
- Reuse LV contour from TVA
- Lesion selection by threshold including mean + xSD method to provide volume
- Text, polar map output by capture
- Whole or customizable layer analysis in myocardium (up to 3)

### Cardiac MR Perfusion
- BETA release
- RSNA version required Aquarius CMR but with this release no license is checked.  
- Side-by-side loading only (no graphs and maps!)

### Multi-modality Fusion 
- Improvements for CT/PET mainly
- 2 time points support
- ThinClient layout support with Spinning man

### Multi-Modality Fusion (MMF) for CT/SPECT
- CT/SPECT fusion and analysis for myocardium analysis
- Need new license “Aquarius Multi-Modality Fusion”
- For non-JP, Licenser will add this key with “Fusion”, For JP, separate package
- Polar map results for reversibility and wash out rate

### Ca scoring
-Capture and reporting improvements

### Multi-KV
- Hardware removal

### TAVR
- Embedded geometry by configurable template for different sizes

### LD2
- Margin around the lesion and risk analysis 

### Flythough 
- More layout and configurable label

### TDA 
- 3x3 layout and capture all in one option
- Left/Right Hemisphere Classification map 

### Findings Workflow
- BFA support
- Workflow oriented criteria 

### Dynamic Volume Fusion
- Need new license “Aquarius Dynamic Volume Fusion”
- Real time Multi-modality fusion provides better image quality

### Portrait Monitor support

## Thin Client new features 
- Option to load with/without auto tilt/rotate

## iReview new features
- Mirrored ROI measurement
- Real world mapping support

## APS new features
- Plug and play - CTA related clinical protocol support
- Whole chest bone removal

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
- Auto Configurations of VPCUDA & VLI

---

# Version 4.4.12 Beta

## S4331 [SAT] Add surface area - Shape Compactness 
> Request to have surface area by MUSC.  Instead of having surface area, shape index is added.  The value is normalized from 0 to 100.  Value 100 means perfect sphere. 
{.is-info}

- Load a lung study.
- Open SAT tool panel, click on "New" button, choose "single click" and "nodule" mode, "shift"+click on a nodule seed point.
- After the segmentation is done, measurement result will display.
- Right click on measurement and select “show/hide details.”
- Check to add “Shape Compactness” and click OK.
- Beta message will be displayed.

## S3238 [TDA] Body CT Perfusion
- In "C:\AQi\Config\AQi.cfg, add "EnableBetaFunction = True"
- Load body CT perfusion data into TDA (Body) workflow

## Histogram beta for MR
- In "C:\AQi\Config\AQi.cfg, add "EnableHistogramForMR = True"

## iReview - AqLOC
- In "C:\AQNetConfig, add "EnableBeta = 1" 
>BETA can be configured globally in this file, or by machine name. To configure BETA per machine, a section in the format [PC-NAME] must be created in the config file.
{.is-info}

## iReview - Non-validated mammo CAD
- In "C:\AQNetConfig, add "EnableBeta = 1" 
> BETA can be configured globally in this file, or by machine name. To configure BETA per machine, a section in the format [PC-NAME] must be created in the config file.
{.is-info}

## TA2895 TDA MR support non-validated manufacturer 
- In "C:\AQi\Config\AQi.cfg, add "EnableBetaFunction = True"

## TDA-Flow non-validated flow data
- In "C:\AQi\Config\AQi.cfg, add "AllowToUseFlowAnyData= True"

## Toshiba MR flow - S8381
- In "C:\AQi\Config\AQi.cfg, add "SupportToshibaMRFlow=True"

