# Spoonacular-Recipe-Nutrients-Dataset
API web scrape of Spoonacular Recipe Nutrients into a dataset


This repository contains a dataset of 211 recipes and basic nutrient information about them from the Spoonacular website. The dataset is not all the way cleaned yet and contains jpg images that can be removed. It can be used for practice on using APIs and creating visualizations.

The dataset was made from the Spoonacular API. The code for how the data was pulled is included for reference and further use. 


# Table of Contents
[Installation](#Installation)
[Data](#Data)
[Contents](#Contents)


## Installation
For this project you will need the following libraries:
* pandas
* numpy
* requests
* re
* csv 
* config

## Data
The data contains recipes that have atleast 15g of protein in them and anywhere between 0-100 carbs as well  all per serving size. It was retrieved in three parts with the first 100 points of 0-30 carbs, the second 100 having 30-50 carbs, and the last 100 having 50-95 carbs. The three sets were then merged together outputting the following variables:

* ID- The recipe id corresponding with the Spoonacular Website
* Title- Title of the recipe
* Image- image of the recipe
* ImageType- the formate of the recipe image
* Calories- number of calories
* Protein- amount of protein in grams
* Fat- amount of fat in grams
* Carbs- amount of carbs in grams

## Contents 
This repository contains an ipynb contains the code used and a csv of the data exported from python.

