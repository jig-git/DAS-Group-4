# An In-Depth Insight into BMI in Scotland from 2008-2012

This repository contains our group project (for our Data Analysis course). 
In the report, we analysed BMI trends in Scotland between 2008 and 2012 using the Scottish Health Survey (DAProject8.csv dataset), focusing primarily on the impacts of socio-economic and lifestyle factors.

## Group Members
- 2772011M
- 2840466A
- 2782951G
- 2662654J

## Our Repository Structure
- `src/Group_4_Analysis.qmd`: This contains our main Quarto file with all R code and narrative for the analysis.
- `figures/`: This folder contains all of our generated plots (e.g., histograms, boxplots), that were created during rendering.
- `data/DAProject8.csv`: This is the dataset from the Scottish Health Survey (2008-2012) that we used to from our analysis.
- `output/Group_4_Analysis.html`: This contains our full rendered HTML report, and is included for reference.
- `.gitignore`: We use this file to exclude unnecessary files (e.g., `.RData`, `.Rhistory`, `.DS_Store`).
- `README.md`: This file.
- `Group_4_Analysis_files`: This contains all of Quarto's necessary files for rendering.

## How to Use
To replicate our analysis, follow the following steps:
1. Install R, RStudio, and Quarto.
2. Clone this repository: use `git clone https://github.com/jig-git/DAS-Group-4.git`.
3. Open the source code contained in `src/Group_4_Analysis.qmd` in RStudio.
4. Render to HTML to generate the full report and all figures.

Alternatively, you can view the pre-rendered report in `output/Group_4_Analysis.html`, which is located in this repository.

## Tools We Used
- R (v4.4.2)
- Quarto (v1.6.40)
- Libraries: tidymodels, readr, tidyverse, gt, ggplot2, MASS, moderndive, broom, knitr, dplyr

## GitHub Practices
Throughout the entirety of the project, we used GitHub collaboratively to manage our project, following the best, common practices:
- **Branches:** Each member of the group worked on their own individual branch (e.g. Abby worked on the "Abby" branch, etc.), before merging into `main`.
- **Commits:** For each commit, we used meaningful messages, to ensure tracking of our work and review was straightforward — see "Commits" tab.
- **Reviews:** Commented on each other’s commits (though most communication for our Commits was done in person, so these comments are generally limited throughout) — see "Commits" tab.
- **Organisation:** We structured files into `src/` (source code), `figures/` (plot outputs), `data/` (input data), and `output/` (rendered report) for clarity, and ease of finding.
- **`.gitignore`:** Excludes temporary files (e.g., `.RData`, `.Rhistory`, `.DS_Store`) and other generated outputs (except `output/*.html`). We ensured legacy files were removed after adding `.gitignore` to keep the repository tidy.
