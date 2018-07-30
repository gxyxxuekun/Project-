---
title: "Exploring the BRFSS data"
output: 
  html_document: 
    fig_height: 4
    highlight: pygments
    theme: spacelab
---

## Setup

### Load packages

```{r load-packages, message = FALSE}
library('ggplot2')    # library to create plots
library('plyr')       # data manipulation
library('dplyr')      # data manipulation
library('gridExtra')  # supports the layout functionality with ggplot
library('ggmap')      # visualize maps 
library('knitr')      # required to apply knitr options 
library('gtable')     # used to overlay plots in ggplot
library('grid')       # used to overlay plots in ggplot

# apply general knitr options
knitr::opts_chunk$set(comment=NA, fig.align='center')
```

### Load data

Make sure your data and R Markdown files are in the same directory. When loaded
your data file will be called `brfss2013`. Delete this note when before you submit 
your work. 

```{r load-data}
# ============================================================================================================
# Download and extract Data and load file
# ============================================================================================================

# load the data set 
load(file = 'Data/brfss2013.RData')
```



* * *

## Part 1: Data


* * *

## Part 2: Research questions

**Research quesion 1:**

**Research quesion 2:**

**Research quesion 3:**


* * *

## Part 3: Exploratory data analysis

NOTE: Insert code chunks as needed by clicking on the "Insert a new code chunk" 
button (green button with orange arrow) above. Make sure that your code is visible
in the project you submit. Delete this note when before you submit your work.

**Research quesion 1:**

```{r}

```



**Research quesion 2:**

```{r}

```



**Research quesion 3:**

```{r}

```
