# Investigation of Top Grossing Film Characteristics

The goal of this workbook is to analyze top grossing film data, using Jupyter Notebook and datasets from Kaggle. The production method, runtime and genre is inspected for potential predictioon models.

## Required Installation

The _ipynb_ workbook only operates in Jupyter Notebook, and can be installed via [Anaconda](https://www.anaconda.com/products/individual) or via [Jupyter-Lab](https://jupyter.org/install):
`pip install jupyterlab`

The _libraries_ required for this workbook are listed and is included in the Anaconda package:
- Numpy
- Pandas
- Matplotlib
- Seaborn

## Resources

The repo consists of the workbook that describes the analysis, where one can interact with dataframes and functions, and the exported  _png_ figures that are of significance. The two relevant datasets are [Top 1000 Highest Grossing Movies](https://www.kaggle.com/sanjeetsinghnaik/top-1000-highest-grossing-movies) and [Hollywood Synopsis (1995-2021)](https://www.kaggle.com/johnharshith/hollywood-theatrical-market-synopsis-1995-to-2021?select=TopProductionMethods.csv) from Kaggle. The latter contains multiple _csv_ files, where the following is used:

- Annual Ticket Sales
- Highest Grossing

## Results of Analysis

The production method, runtime and genre was inspected throughout the analysis, to identify if the variables can be used for predicting gross andd present any other findings. The production method shows that certain methods show more gross than others but is not the most accurate measure. A production budget would be a more predictable measure. The different runtimes shows weak positive relationship which cannot be used for any moels. Lastly the genre is a complex variables as a film can belong to more than one. For the top 1000 grossing it is difficult to select a majory genre for each film. However, a genre prediction model can be considered for future work. Therefore, the three variables cannot be used for a gross prediction model.

## Licenses
The author of the workbook is solely Christiaan van Eeden (theartifice). The _Top 1000 Highest Grossing Movies_ is a public dataset and the _Hollywood Synopsis (1995-2021)_ are exported from [The Numbers](https://www.the-numbers.com/market/ ) which pertain the North American market. These licenses regarding these datasets are respectively:
1. [CC0: Public Domain](https://creativecommons.org/publicdomain/zero/1.0/)
2. [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
