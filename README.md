# ChanceCalc
### What is ChanceCalc?
ChanceCalc+ is an Excel add-in that creates models that use the Data Table function to simulate uncertain outcomes either by reading Stochastic Libraries or performing Monte Carlo simulation.

The models created with ChanceCalc do not require the add-in to run and may be shared with any Excel user. 

### Why does it exist?
Many Excel users represent uncertain assumptions as single average inputs. This leads to a set of systematic errors known as the [Flaw of Averages.](https://www.flawofaverages.com/) Models built with ChanceCalc+ can cure these errors, leading to better decisions in the face of uncertainty.

### Who should use it?
Anyone using Excel who is uncertain about their input assumptions.

### Quick video demo
See the Introduction to ChanceCalc video at the [ProbabilityManagement YouTube channel.](https://www.youtube.com/channel/UCn9qBDt8E1l3z9PX_D1eZgg)

## Requirements

Microsoft Excel

## Brief Explanation of files in src\ folder:

- ChanceCalc_Plus.xlam
  - the core addin

- ELDMetalogs_v11.xlsx
ELDMetalogs_v11_multi.xlsx
Metalogs_v11.xlsx
  - used with the Metalog tab to create metalog formulas to fit given data sets
        
- help_SPT_column.jpg
help_SPT_row.jpg
  - help images displayed by Monte Carlo | Generate Distribution | SPT Metalog | Help

- horizontal 1-line layout template.xlsx
vertical 1-col layout template.xlsx
  - hold formulas for SPT Metalog that can be copied down or across.
    Used by Monte Carlo | Generate Distribution | SPT Metalog
        
- Metalog Sum of IID Triangulars and Lognormals.xlsx
  - Used by Monte Carlo | Generate Distribution | Triangular, SUM Multple IIDs checkbox and
Monte Carlo | Generate Distribution | Lognormal (Percentile)
Monte Carlo | Generate Distribution | Lognormal (Mean and Stdev)
Monte Carlo | Generate Distribution | Lognormal (True Mean and Stdev), Sum Multiply IIDs checkbox

- Palette.xlsx
  - Used by Settings dialog

## Installation

- Download the ZIP archive with the current version of ChanceCalc from [here](https://github.com/probability-management/ChanceCalc/releases/)
- Unzip the archive to any convenient folder
- Activate the ChanceCalc add-in as follows:
    - Start Excel
    - Open the Excel Add-ins manager 
        - On Windows
            - Open or create an Excel workbook
            - Press Alt-T-I
        - On Macintosh
            - Click Tools on the menu
            - Click Excel Add-ins... on the Tools sub-menu
    - The Add-ins manager displays a list of available and installed add-ins
    - Remove any existing ChanceCalc or SIPmath add-ins 
        - if any add-ins in the list named ChanceCalc or SIPmath are checked, uncheck them
    - Press the Browse... button
        - Browse to the folder where the ChanceCalc files were installed
        - Find and select the file ChanceCalc_Plus.xlam
        - Press OK to close the Browse dialog
    - The ChanceCalc add-in should now be checked in the list of available add-ins
    - Press OK to close the add-ins manager.

## FAQ

 - I get the error “Compile error: method or data member not found”, what should I do?
    - Make sure ActiveX controls are enabled as described [here.](https://www.probabilitymanagement.org/troubleshooting-excel)

- ChanceCalc worked once, but now it has stopped working.
    - Make sure that the ChanceCalc add-in (XLAM) file is "unblocked". To do so:
        - Quit Excel, making sure all open excel files are closed.
        - Find the ChanceCalc add-in (XLAM) file in Windows Explorer
        - Right-click on the add-in file to open the context menu
        - Select the "Properties" menu item to open the "Properties" dialog.
        - Look for a check box named "Unblock" At the bottom of the "Properties" dialog; check it on.
            - If there is no check box, then the file is already unblocked.
        - Press OK.




## Using ChanceCalc

![Title](<imgs/Slide1.JPG>)

![Contents](<imgs/Slide2.JPG>)

![Introduction](<imgs/Slide3.JPG>)

## ChanceCalc Tab

![ChanceCalc Ribbon](<imgs/Slide4.JPG>)

![SIP Input dialog](<imgs/Slide5.JPG>)

![Graphs](<imgs/Slide6.JPG>)

![Chance of Whatever](<imgs/Slide7.JPG>)

![Average, Std Dev, Percent](<imgs/Slide8.JPG>)

![Tail Risk](<imgs/Slide9.JPG>)

![Save as CSV](<imgs/Slide10.JPG>)

![Trial Info](<imgs/Slide11.JPG>)

![Settings | Simulation](<imgs/Slide12.JPG>)

![Settings | Formatting & Diagnostic](<imgs/Slide13.JPG>)

![Settings | Advanced](<imgs/Slide14.JPG>)

## Metalog Tab

![Metalog Ribbon](<imgs/Slide15.JPG>)

![Metalog Interface](<imgs/Slide16.JPG>)

![Metalog Interface - cont'd](<imgs/Slide17.JPG>)

![SIPmath mode, to Clipboard button](<imgs/Slide18.JPG>)

![SIPmath mode, to File button](<imgs/Slide19.JPG>)

![to Excel mode, Paste to Excel](<imgs/Slide20.JPG>)

![to Excel mode, Link to Excel](<imgs/Slide21.JPG>)

## Monte Carlo Tab

![Monte Carlo Ribbon](<imgs/Slide22.JPG>)

![Appendix 1: Troubleshooting](<imgs/Slide23.JPG>)

![Appendix 2: Lambda Functions](<imgs/Slide24.JPG>)

![Lambda Functions, cont'd](<imgs/Slide25.JPG>)

![HDR and M.SPT_u functions](<imgs/Slide26.JPG>)

## License

This project is licensed under the [MIT License](https://github.com/probability-management/ChanceCalc/blob/main/LICENSE)

