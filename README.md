# Project Title

Check the project requirements for what should go into this file.

# Project 03 - Malaria Experts

## 1. What is this GitHub repository about?

This repository contains the code, analysis, and deliverables for **Project 03: Malaria Experts**.  
The project focuses on **analyzing global malaria cases and deaths over time and across regions based on WHO data** using R and Quarto.  
It includes all the scripts, the final report, and presentation slides.

## 2. Software Requirements

To successfully run the code in this repository, please ensure the following software and versions are installed:

- **R version 4.4.3** or later
- **RStudio version 2024.12.1 Build 563** or later
- **Quarto version 1.4.553** or later
- **Git** (for version control and publishing)

Required R packages (with suggested versions):

- `tidyverse` (>= 2.0.0)
- `knitr` (>= 1.45)
- `readr`
- `dplyr`
- `ggplot2`
- `quarto`

You can install missing packages with:

```r
install.packages(c("tidyverse", "knitr", "readr", "dplyr", "ggplot2"))
```

## 3. Steps to Run the Code

1. Clone this GitHub repository to your local machine:

```bash
git clone 
```

2. Open the project folder in **RStudio**.

3. Install all required R packages if not already installed.

4. Open the main `.qmd` file (e.g., `project-03-malaria_experts.qmd`) in RStudio.

5. Render the Quarto document by clicking the **Render** button, or by running:

```r
quarto::quarto_render("project-03-malaria_experts.qmd")
```

6. (Optional) To publish the project to GitHub Pages, open Terminal in RStudio and type:

```bash
quarto publish gh-pages --no-browser
```

## 4. Expected Output

The rendered Quarto website should include:

- A main report describing the data cleaning, modeling, and final results.
- Visualizations such as:
  - **A bar plot showing feature importance.**
  - **A confusion matrix heatmap.**
- A summary of model performance and key findings.

Example Screenshot:

![Example Main Page](screenshots/main_page.png)

(If screenshots are not available, you can remove or comment out this section.)

---

## Deliverables Structure

- `/code/` — All R scripts and Quarto source files
- `/report/` — Rendered final report
- `/presentation/` — Slide deck for final presentation
- `/video/` — Final project video walkthrough (or a link to the video)

---
