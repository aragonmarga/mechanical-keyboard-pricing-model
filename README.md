# mechanical-keyboard-pricing-model
Statistical analysis of mechanical keyboard pricing using a 2018 dataset. Includes feature-based price modeling with multiple linear regression and simulated economic impacts from U.S.-China tariffs and inflation.

# Mechanical Keyboard Pricing Model

This project uses a 2018 dataset of mechanical keyboards scraped from MechanicalKeyboards.com to model and predict keyboard prices. The analysis employs multiple linear regression techniques and simulates the impact of U.S.-China tariffs and inflation on predicted prices.

## 📊 Project Objectives
1. Identify which product features (e.g., brand, switch type, dimensions) significantly influence keyboard price.
2. Estimate price increases resulting from a 145% import tariff and 27.4% inflation rate, as proposed in trade policy scenarios.

## 📁 Repository Structure
- `kb_mlr432.pdf`: Main analysis report (EDA, modeling, diagnostics, and simulation)
- `keyboard_analysis_report_outline.pdf`: Report outline used for planning
- `data/`: Raw and cleaned CSV files of keyboard data
- `notebooks/`: R code for cleaning, EDA, regression modeling, and simulation
- `figures/`: Visualizations and diagnostic plots

## 🧪 Methods
- Data wrangling in R (`dplyr`, `tidyr`)
- Exploratory Data Analysis (EDA) using `ggplot2`
- Feature engineering and power transformations
- Model selection via AIC/BIC and stepwise regression
- Diagnostics: residual plots, leverage detection
- Price simulation under policy changes

## 📈 Key Results
- Physical dimensions, brand, switch type, and LED features were significant predictors of price.
- A representative keyboard (e.g., Ducky, RGB, Cherry MX Red) had a predicted price of ~$127.
- Under tariffs + inflation, the same keyboard’s estimated price rose to ~$400.

## 📚 References
- Siyuan Li. (2018). *Mechanical Keyboards Dataset*. GitHub repository: https://github.com/siyuanligit/mk

## ✍️ Author Note
Marga Aragon, Department of Statistics, California State Univeristy, East Bay, Hayward, CA

No changes in affiliation. This project was completed as part of a statistical modeling course. Thanks to Dr. Jiyoun Myung for feedback and guidance.

Contact: margafaragon@gmail.com

## 📝 License
This repository is for educational and academic use. Data used is publicly available for non-commercial purposes.
