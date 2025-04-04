# Data for "Cultural Analytics in R: A Tidy Approach"

This repository contains the datasets used in the book *Cultural Analytics in R: A Tidy Approach* (SpringerLink) by Nabeel Siddiqui.

## Download Options

You have two options to download the data:

### Option 1: Download All Data (Recommended)
1. Download the `data.zip` file from this repository
2. Unzip the file to create a `data` folder containing all datasets
3. Place this `data` folder in the same directory as your R script

### Option 2: Download Individual Files
1. Navigate to the `data` folder in this repository
2. Download only the CSV files you need for your work
3. Create a `data` folder in your working directory
4. Place the downloaded files in this `data` folder

## Data Organization

The datasets are organized by chapter:

- `ch1_olympics.csv`: Data for Chapter 1
- `ch2_films_1960s.csv`, `ch2_films_1970s.csv`, etc.: Data for Chapter 2
- `ch3_muse.csv`: Data for Chapter 3
- `ch4_books.csv`: Data for Chapter 4
- `ch5_battles.csv`, `ch5_pokemon.csv`: Data for Chapter 5
- `ch6_race_films.csv`: Data for Chapter 6
- `ch7_artists.csv`: Data for Chapter 7

## Usage

### Base R
```r
# For example, to load Chapter 1 data:
olympics <- read.csv("data/ch1_olympics.csv")
```

### Tidyverse 
```r
library(tidyverse)
# For example, to load Chapter 1 data:
olympics <- read_csv("data/ch1_olympics.csv")
```
Please ensure the `data` folder is in your working directory before running your scripts.
