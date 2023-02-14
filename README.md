# jj_ojjdp_va
This is the R repository for the OJJDP Virginia Project.

## Project Purpose
Assess statewide referral and diversion policies and practices, and identify opportunities to align DJJ diversion policies, practices, and resource allocation strategies with what research shows works to improve public safety and youth outcomes.  

## Assigned Research Staff
Becky Cohen and Andrew Byrum 

## Teams/SharePoint Project Folder
Sharepoint path to JC Resarch folder for overall OJJDP Project (see "VA" folder for state-specific data and background): https://csgorg.sharepoint.com/:f:/s/Team-JC-Research/EqTB3O7P2iVIo0D4I1qb68MBzHy5vZlq394OjsFWUVdxRA?e=fdfBnI

## Netlify Site
Here's the path to the Netlify-hosted site, which will be updated with data diagrams, codebooks, and code for analytic file creation throughout the project: https://va-ojjdp.netlify.app/

The password is csgjc_va

## Repository Structure

```
│   ├── _freeze/ # folder with frozen copies of entire repo; using 'auto' freeze option to "denote that documents only be re-rendered when their source file change"
│   ├── _site/ # folder with knitted html files that is hosted by netlify site
|   |    ├── data_cleaning/ # copy for site
|   |    ├── data_diagram/ # copy for site
|   |    ├── img/ # folder with files/packages for respective html (b/c rmd is not self contained)
│   │    |   ├── csg-logo.png
│   │    |   ├── favicon.png
│   │    |   ├── ojjdp_va_data_diagram.png
|   |    ├── ojjdp_va_data_codebooks_file/figure-html/ # folder with files/packages for respective html (b/c rmd is not self contained)
|   |    ├── site_libs/ # folder with files/packages for respective html (b/c rmd is not self contained)
|   |    ├── index.html/ # knitted landing page html for site
|   |    ├── ojjdp_va_create_analytic_files.html/ # knitted html for site
|   |    ├── ojjdp_va_create_analytic_files.html/ # knitted html for site
|   |    ├── ojjdp_va_data_codebooks.html/ # knitted html for site
|   |    ├── ojjdp_va_data_diagram.html/ # knitted html for site
|   |    ├── ojjdp_va_data_diagram_viz.html/ # knitted html for site
|   |    ├── ojjdp_va_questions_updates.html/ # knitted html for site
|   |    ├── ojjdp_va_preliminary_descriptives.html/ # knitted html for site
|   |    ├── search.json
|   |    ├── style.css
│   ├── data_cleaning/
│   │    |   ├──  ojjdp_va_exploration_import_clean.Rmd/ # initial cleaning file for import and basic data prep
│   ├── data_diagram/
│   │    |   ├──  ojjdp_va_data_diagram_build.qmd/ # file to create data diagram for project
│   ├── img/           
│   │    |   ├── csg-logo.png
│   │    |   ├── favicon.png
│   │    |   ├── ojjdp_va_data_diagram.png
|
├── index.qmd/ # landing page to knit for site
├── ojjdp_va_create_analytic_files.qmd/ # html to knit for site; QMD builds any analytic files -- pushing to site for QA with team
├── ojjdp_va_data_codebooks.qmd/ # html to knit for site -- creates codebooks for each file
├── ojjdp_va_data_diagram_viz.qmd/ # html to knit for site -- renders data diagram
├── ojjdp_va_questions_updates.qmd/ # html to knit for site -- running list of questions and communication with Dallas County
├── ojjdp_va_preliminary_descriptives.qmd/ # html to knit for site -- basic descriptives for files and variables of interest
├── .gitignore
├── .nojekyll
├── README.md
├── _quarto.yml/ # netlify site structure
└── theme.css
```
