# Project 03 - Malaria Experts

## 1. What is this GitHub repository about?

This GitHub repository contains the code, data, analysis, and final deliverables for **Project 03: Malaria Experts**.
The project analyzes global malaria cases and deaths from 2000 to 2017 using WHO data.
Our goal is to understand:

-   Global and regional trends in malaria incidence and mortality
-   Spatial distribution of malaria burden using choropleth maps
-   Correlations between case counts and death counts over time

The analysis is conducted using **R**, **RStudio**, and **Quarto**.
The repo includes: - Cleaned datasets - R code and Quarto files - Final rendered report - Presentation slides

## 2. Team Members

-   Riley Karatas
-   Amy Yang
-   Aisling Li
-   Zora Shi

## 3. Software Requirements

To successfully run the code in this repository, please ensure the following software and versions are installed:

-   To successfully run this project, ensure the following software is installed:
    -   [**R**](https://cran.r-project.org/) version **4.4.3** or later
    -   [**RStudio**](https://posit.co/download/rstudio-desktop/) version **2024.12.1 Build 563** or later
    -   [**Quarto**](https://quarto.org/docs/get-started/) version **1.4.553** or later
    -   [**Git**](https://git-scm.com/) (for version control and publishing)

Required R packages (install on first run):

```{r}
install.packages(c("tidyverse", "lubridate", "here", "sf", "rnaturalearth", "rnaturalearthdata", "mosaic"))

```
