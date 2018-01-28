# Mushroom Categories

#### Created by: Teddy Haley

[Link to Personal repository](https://github.com/TedHaley)  
[Link to v1.0 Release](https://github.com/TedHaley/mushroom_categories/releases)  

## About
The goal of this project is to determine which features are relevant or irrelevant when determining the toxicity of a mushroom with a particular set of features.

## Usage
To run the project:

1. Clone the github repository to a location on your local machine: `git clone https://github.com/TedHaley/mushroom_categories.git`
2. Change directory to the root of the downloaded repository: `cd Path-To-Local-Repo/mushroom_categories`
3. Run the `analysis.ipynb` jupyter notebook in the `src` extension.

## File Structure

![](Makefile.png) 

## Data
The datasets used in this analysis is provided by the UCI Machine Learning Repository Open data. The dataset can be found here: [Mushroom Dataset](http://archive.ics.uci.edu/ml/machine-learning-databases/mushroom/agaricus-lepiota.data).

The data taken from the UCI Machine Learning Repository includes:  
`agaricus-lepiota.data` which is then wrangled into a `agaricus-lepiota.csv` file. 

## Hypothesis
To determine which features are relevant or irrelevant when determining the toxicity of a mushroom with a particular set of features.

## Analysis
Using the mushroom dataset provided by the UCI Machine Learning Repository, this analysis will test what features of mushrooms are significant when determining the toxicity of a particular mushroom. There are 23 features, as well as over 8000 observations within the mushroom dataset.  

## Sub-Modules
There are 4 modules in the root directory. They include data, doc, results, and src.

`data` contains all the raw data taken from the UCI Machine Learning Repository website. 

`doc` contains the compiled report with all generated graphics and analyses.

`results`: contains the cleaned data, all of the plots, and analysis performed.   

`src`: contains all of the analysis script which performs the import, cleaning, and analysis of the data. 


