# Datasets

This repo contains data sets that are required in order to perform the applications and exercises we will cover in our course. 

## Data import with Python

 1) Navigate to the dataset 
 2) Select the `Raw` button 
 3) Copy the URL from the browser
 4) Paste the URL in your code (see below) 
 
In this code example we use the URL from the `height`dataset (`https://raw.githubusercontent.com/kirenz/datasets/master/height.csv`) and import the data from GitHub with `pandas`: 

```{python}
import pandas as pd
df = pd.read_csv("https://raw.githubusercontent.com/kirenz/datasets/master/height.csv")
```

## Data import with R

 1) Navigate to the dataset 
 2) Select the `Raw` button 
 3) Copy the URL from the browser
 4) Paste the URL in your code (see below) 
 
In this code example we use the URL from the `height`dataset (`https://raw.githubusercontent.com/kirenz/datasets/master/height.csv`) and import the data from GitHub with the package `readr`: 

```{r}
library(readr)
data <- read_csv("https://raw.githubusercontent.com/kirenz/datasets/master/height.csv")
```

## List of further data resources

- [Awesome public datasets](https://github.com/awesomedata/awesome-public-datasets)
- [FiveThirtyEight](https://data.fivethirtyeight.com)
