# AllRecipes Data Analysis Project by Cooks

## Overview
This repository contains the code and analysis for our group project exploring the TidyTuesday AllRecipes dataset. Our primary research objective is to identify the actionable zone for home cooks. By analysing variables such as total cooking time, serving sizes, and the number of ingredients, we seek to understand how recipe complexity and effort influence both community engagement (total ratings) and overall satisfaction (average rating).

## Repository Contents
* `main_project.ipynb`: The primary Jupyter Notebook containing the full data pipeline, including data cleaning, summary statistics, visualisations, and our final synthesised discussion.
* `main_project.html`: An exported HTML version of the notebook for easy viewing in any standard web browser without needing to run the code.
* `requirements.txt`: The list of Python dependencies required to execute the notebook.

## Key Findings
Across roughly 14,000 recipes, cooking time has almost no relationship with rating (r = 0.006) and ingredient count only a weak one (r = 0.10), so quick recipes are not rated worse than slow ones. Simpler is not better, though: recipes with 1 to 5 ingredients score lowest in almost every time bracket, and the highest-rated group is under 15 minutes with 11 to 15 ingredients (average 4.63). Highly rated recipes in the 15 to 60 minute range also keep medium to high nutrient density, so speed, rating and nutrition can coexist.

## Setup and Installation
To run this analysis on your local machine, ensure you have Python installed and follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Capacesse/NUS-Allrecipes-DataAnalysis-2026.git
   cd NUS-Allrecipes-DataAnalysis-2026
