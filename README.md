# Datasets

This repo contains data sets that are required in order to perform the applications and exercises we will cover in this course. 

## Data import with Python



## Data import with R

 1) Navigate to the dataset 
 2) Select the `Raw` button 
 3) Copy the URL from the browser
 4) Paste the URL in your code (see below) 
 
Example: URL for the dataset `height` is `https://raw.githubusercontent.com/kirenz/datasets/master/height.csv`

```{r}
library(RCurl)
df <-  getURL("https://raw.githubusercontent.com/kirenz/datasets/master/height.csv")
dataset_oecd <- read.csv(text = dataset_oecd_raw)

```


## List of further data resources

- [Awesome public datasets](https://github.com/awesomedata/awesome-public-datasets)
- [FiveThirtyEight](https://data.fivethirtyeight.com)
