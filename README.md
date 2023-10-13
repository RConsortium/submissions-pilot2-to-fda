> Do not include `README.md` and `.gitignore` files into the final submission. 

## Overview

The objective of the R Consortium R submission Pilot 2 Project is to test the concept that a Shiny application created with the R-language can be bundled into a submission package and transferred successfully to FDA reviewers. The application was built using the source data sets and analyses contained in the R submission Pilot 1 Project, with materials available on the [RConsortium/submissions-pilot1](https://github.com/RConsortium/submissions-pilot1) repository, All submission materials and communications from this pilot are publicly available, with the aim of providing a working example for future R language based FDA submissions. This is a FDA-industry collaboration through the non-profit organization R consortium.

While the intent of the project is to enable execution of the Shiny application in a reviewer's local R environment, a deployed version of the application is available in open access through the Shinyapps.io service at [rconsortium.shinyapps.io/submissions-pilot2](https://rconsortium.shinyapps.io/submissions-pilot2/).

The [RConsortium/submissions-pilot1-to-fda](https://github.com/RConsortium/submissions-pilot1-to-fda)
repository demonstrates the eCTD submission package based on the [RConsortium/submissions-pilot1](https://github.com/RConsortium/submissions-pilot1) repo.  

The [RConsortium/submissions-pilot1](https://github.com/RConsortium/submissions-pilot1) repository demonstrates an approach to organize internal developed R function and 
table, listing, figure generation program using an R package. 

The [RConsortium/submissions-pilot2](https://github.com/RConsortium/submissions-pilot2) repository demonstrates an approach to organize a Shiny application as an R package.

To learn more about other pilots, visit [the R consortium R submission working group website](https://rconsortium.github.io/submissions-wg/) and the [R consortium working group page](https://www.r-consortium.org/projects/isc-working-groups).

## FDA Response 

- Initial submission

  + version: [v0.1.0](https://github.com/RConsortium/submissions-pilot2-to-fda/releases/tag/v0.1.0)
  + [Cover letter](https://github.com/RConsortium/submissions-pilot2-to-fda/blob/main/m1/us/cover-letter.pdf)
 
- [FDA response letter](https://github.com/RConsortium/submissions-wg/blob/0f1dc5c30985d413f75d196c2b6caa96231b26ee/_Documents/Summary_R_Pilot2_Submission%2027SEP2023.pdf)

  
## Run Shiny Application

To run the Pilot 2 Shiny application, you can follow the steps described in the
[ADRG document](https://github.com/RConsortium/submissions-pilot2-to-fda/blob/main/m5/datasets/rconsortiumpilot2/analysis/adam/datasets/adrg.pdf) based on the
[program saved in the module 5](https://github.com/RConsortium/submissions-pilot2-to-fda/tree/main/m5/datasets/rconsortiumpilot2/analysis/adam/programs). A web version of the ADRG is also available at <http://rsubmission-draft.website-us-east-1.linodeobjects.com/>.

The application is also available online at [rconsortium.shinyapps.io/submissions-pilot2](https://rconsortium.shinyapps.io/submissions-pilot2/).

## Folder Structure 

The folder is organized as a demo eCTD package following ICH guidance. 

eCTD package: 

- `m1/`: module 1 of the eCTD package

```
m1
└── us
    ├── cover-letter.pdf  # Submission cover letter
```

- `m5/`: module 5 of the eCTD package

```
m5
└── datasets
    └── rconsortiumpilot2
        └── analysis
            └── adam
                ├── datasets              # ADaM datasets in XPT format
                │   ├── adadas.xpt
                │   ├── adlbc.xpt
                │   ├── adrg.pdf          # Analysis Data Reviewer's Guide
                │   ├── adsl.xpt
                │   ├── adtte.xpt
                │   ├── define.xml        # ADaM data define file
                │   └── define2-0-0.xsl
                └── programs
                    ├── r1pkg.txt         # Application R package in txt format
```
Other files: (**Do not include in eCTD package**)

- `.gitignore`: git ignore file
- `README.md`: readme file for github repo

## News

## Questions 

Report issues in <https://github.com/RConsortium/submissions-pilot2-to-fda/issues>

