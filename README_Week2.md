# Week 2 — Data Visualization and Insight Communication using R

## Project
Visual exploration of the Titanic passenger dataset using R and ggplot2.

## Dataset
Public Seaborn Titanic CSV (891 rows in the commonly used version):
https://raw.githubusercontent.com/mwaskom/seaborn-data/master/titanic.csv

## Visualizations
1. Bar chart: survival rate by passenger class.
2. Histogram: passenger age distribution.
3. Scatter plot: age versus ticket fare, coloured by class.
4. Line chart: survival rate across age groups.
5. Box plot: ticket fare distribution by passenger class.

## Run the project
1. Install R and RStudio.
2. Open `week2_titanic_visualization.R`.
3. Run the complete script with internet access for the first CSV download.
4. PNG charts and CSV summary tables are saved to the working directory.

## Methods
The script repeats the documented Week 1 preparation: removes very incomplete/redundant columns, median-imputes age, mode-imputes embarked, and labels passenger class and survival as factors. All charts are created from the downloaded dataset at runtime.

## Interpretation note
Charts in the accompanying report are illustrative previews to show the intended chart types and narrative. Regenerate charts by running the R script and replace preview figures if exact execution evidence is required.
