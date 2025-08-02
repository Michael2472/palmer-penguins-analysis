# Palmer Penguins: Size Analysis by Species and Sex

This project explores the relationship between penguin body mass and flipper length using the Palmer Penguins dataset. The analysis investigates whether species and sex significantly influence body size and evaluates model fit using statistical diagnostics.

## 🐧 Summary

- **Dataset**: `palmerpenguins::penguins`
- **Tools**: R, tidyverse, ggplot2, lm(), skimr, janitor
- **Techniques**: Data cleaning, exploratory visualization, linear modeling with indicator variables, diagnostic testing
- **Goal**: Determine how well flipper length predicts body mass, and whether species/sex significantly impact the model

## 📊 Key Findings

- Body mass increases with flipper length
- Gentoo penguins are significantly heavier than Adelie and Chinstrap
- Males are consistently heavier than females
- Model explains ~86% of the variance in body mass

## 📁 Files

- `Palmer_Penguins_Analysis.Rmd`: Full R Markdown source
- `Palmer_Penguins_Analysis.html`: Rendered HTML report (viewable in browser)
- `images/`: Optional preview or diagnostic plots

## 📌 How to Run

1. Clone or download this repo
2. Open `Palmer_Penguins_Analysis.Rmd` in RStudio
3. Install required packages:
    ```r
    install.packages(c("palmerpenguins", "tidyverse", "skimr", "janitor"))
    ```
4. Knit the RMarkdown to HTML or PDF

## ✅ Author

Nikkole Carlson  
[LinkedIn](https://www.linkedin.com/in/nikkole-carlson-20a58046/)  
