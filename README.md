# World Happiness Dataset Analysis

Academic projects analyzing the World Happiness Report datasets using multivariate statistical analysis and machine learning techniques.

## About

These projects were developed as final coursework for the Machine Learning and Multivariate Analysis courses of the Master in Innovation and Research in Informatics at UPC (Universitat Politècnica de Catalunya).

The analysis focuses on the World Happiness Report for 2018 and 2019, applying advanced statistical and machine learning methods to understand patterns in global happiness data.

## Dataset

The [World Happiness Report](https://worldhappiness.report/) is a landmark survey that ranks 156 countries by happiness scores based on citizen perceptions. The datasets include features such as:

- **Happiness Score** - Target variable representing perceived happiness
- **GDP per capita** - Economic prosperity indicator
- **Social support** - Availability of social networks
- **Healthy life expectancy** - Health and longevity metrics
- **Freedom to make life choices** - Personal autonomy measures
- **Generosity** - Charitable giving patterns
- **Perceptions of corruption** - Trust in institutions

**Data Sources:**
- [Kaggle - World Happiness Report](https://www.kaggle.com/unsdsn/world-happiness)
- [data.world - World Happiness Report 2019](https://data.world/promptcloud/world-happiness-report-2019)

## Project Structure

- `Machine_Learning.Rmd` - Machine learning analysis including PCA, clustering, and predictive modeling
- `Multivariate_analysis.Rmd` - Multivariate statistical analysis with exploratory data analysis
- `WHR2018.csv` - World Happiness Report 2018 dataset
- `WHR2019.csv` - World Happiness Report 2019 dataset
- `Machine Learning Report.pdf` - Generated report from machine learning analysis
- `Mva_Report.pdf` - Generated report from multivariate analysis

## Methods Applied

### Multivariate Analysis
- Principal Component Analysis (PCA)
- Cluster Analysis (K-means, EM clustering)
- Exploratory Data Analysis
- Dimensionality reduction techniques

### Machine Learning
- Linear regression with regularization
- Decision trees and random forests
- Neural networks
- Cross-validation and model evaluation
- Performance metrics analysis

## Requirements

The analysis is implemented in R and requires the following packages:

```r
# Data manipulation and analysis
library(dplyr)
library(mice)
library(psych)

# Visualization
library(ggplot2)
library(gplots)
library(tableplot)

# Multivariate analysis
library(FactoMineR)
library(factoextra)
library(chemometrics)

# Machine learning
library(caret)
library(randomForest)
library(neuralnet)
library(glmnet)
```

## Usage

1. Open the R Markdown files in RStudio
2. Install required packages if not already available
3. Run the code chunks or knit the entire document to generate reports

```r
# Render the documents
rmarkdown::render("Machine_Learning.Rmd")
rmarkdown::render("Multivariate_analysis.Rmd")
```

## Authors

- Manuel Breve
- Diego Quintana  
- Marcel Pons

## License

This project is part of academic coursework at UPC.

