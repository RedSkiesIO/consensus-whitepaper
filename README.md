# Technical White Paper 

This is the full technical whitepaper for the Catalyst network, within which are a blueprint for the consensus and transaction mechanisms, as well as other elements of the overall project needed for the functionality of the network. It aims to describe the full technical structure of Catalyst as well as addressing security considerations and providing benchmarking results. 

## Getting Started

The pdf file is accessible from the Catalyst Technical Paper folder. The pdf should be up to date however to ensure this, open the Catalyst Technical Paper.tex and run in any LaTeX editor. Within the Catalyst Technical Paper folder the excel spreadsheet describes the file structure and file paths. When making any changes to the file structure, ensure that this excel is also updated. Each chapter and section of the paper should have its own .tex file. Subsections will be integrated into their parent section (Unless the subsection is unusually long).

### Prerequisites

For running and editing LaTeX files you can use TexWorks - https://sourceforge.net/projects/texworks.mirror/ for MacOS, Windows and Linux. Other editors are available.

Texworks does not contain a spell checker built in. To install:

* Take both en_GD files from Dictionary folder in repository 
* In Texworks click help dropdown, followed by settings and resources 
* Click hyperlink to take you to relevant folder. If there is no 'dictionaries' folder create the folder
* Add both en_GB files to 'dictionaries' folder 
* In Texworks select Edit dropdown then preferences, under Editor tab Spell-check language should be set to English - UnitedKingdom (en_GB)

### File Structure 

The files are structured according to the excel file Folder Structure. The primary .tex file is under Catalyst Technical Paper.tex. The pdf should be compiled from here. All changes to the text in the document should be made to the relevant .tex file within Paper_Tex_Files. Graphs and graphics should be added to the Figures folder. When linking new figures from a .tex document, the main file Catalyst Technical Paper.tex should be considered the root. 

## Contribution Requirements 

* File System must be in tact and documented of excel table 
* All figures must be held within the relevant figures folder 
* Pdf must automatically generate when used on LaTeX editor
* Sources must be correctly cited. For a reference generator use https://www.harvardgenerator.com/

## Compiling the tex file

Generate a new Pdf file after editing a tex file, modifying a figure, or adding a reference in the bib file. 

Using Texworks, either run (twice) in pdfLatex mode on the main tex file catalyst-technical-paper.tex. If modifying the bibliography file, first run (twice) in Biber mode. 

## Versioning

Versioning will be controlled through pull requests and peer review from other authors before being accepted to master document. 

## Authors

* **Dr. Pauline Bernat** - [PaulineBernat](https://github.com/PaulineBernat)
* **Joseph Kearney** - [kearneyjj1](https://github.com/kearneyjj1)
* **Francesca Sage-Ling** - [franssl](https://github.com/franssl)
* **James Kirby** - [nshCore](https://github.com/nshCore)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments
