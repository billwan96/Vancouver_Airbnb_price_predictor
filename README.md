# Airbnb Price Predictor

## Overview

The Airbnb Price Predictor project focuses on predicting the price of Airbnb listings by leveraging various features. The comprehensive pipeline includes exploratory data analysis (EDA), preprocessing, feature engineering, model construction, feature selection, hyperparameter optimization, and model testing.

To enhance data comprehension and interactivity, a Tableau dashboard has been created, providing intuitive visualizations.

The detail report can be found in [here](https://billwan96.github.io/Vancouver_Airbnb_price_predictor/airbnb_price_predictor.html).

## Project Structure
- data/: Contains the dataset.
- report/: Holds files related to using Jupyter Book to build an HTML report.
- result/: Stores tables and plots from the analysis.
- analysis.ipynb: Jupyter notebook file for the analysis.
- README.md: Project overview and instructions.

## How to Use
Follow these steps to set up the project environment and run the analysis in the Jupyter Notebook.
1. Clone the Repository:
```
git clone https://github.com/your-username/airbnb-price-predictor.git
cd airbnb-price-predictor
```
2. Download Environment File:
```
conda env create -f environment.yml
conda activate airbnb_price
```
3. Open Jupyter Notebook:
```
jupyter notebook 
```
4. Run the analysis notebook

## Acknowledgments
- Dataset: 
We acknowledge the [Inside Airbnb](http://insideairbnb.com/get-the-data/) platform for providing the dataset

- Libraries and Frameworks:
    - Python
    - Pandas, Scikit-learn, LightGBM, Seaborn ,Altair and Matplotlib
    - Tableau 

## License
This project is licensed under the MIT License.