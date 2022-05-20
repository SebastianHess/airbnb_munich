## Data Science: Airbnb Munich - Machine Learning Analysis.

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)


## Installation <a name="installation"></a>

Everything will run with a Python 3.x version.
It is necessary to install the following libraries to run the code in Anaconda. 

* OS a python module which priveds functions for interacting with the operating system OS.
* Numpy a Python library for working with arrays.
* Pandas a Python library for data manipulating and analysis.
* pd.pandas.set_option( ) a Pandas option to visualise all of the columns in a data frame.
* folium a Pandas library to visualise interactive maps.
* Matplotlib a Python library for data visualizations.
* %matplotlib inline a magic function for inline plotting of graphs.
* sklearn.linear_model a class of the sklearn module containing different functions for performing machine learning with linear models.
* sklearn.model_selection a class of the sklearn module splitting the data in train and test data.
* sklearn.metrics a class of the sklearn metrics to use with any continous response variable.
* Seaborn a Python library for data visuallization based on matplotlib.
* sns.set_style to define the seaborn figure aesthetic as "darkgrid".
* dataframe_image to save pictures of data frames.


## Project Motivation<a name="motivation"></a>

I live in Munich and when I travel to other places and countries, I mostly use the Airbnb platform. I guess each one of you knows what I am talking about. Therefore, I would like to answer these questions for my hometown Munich based on a data set provided by Insideairbnb.com.

1. Will I quickly find a suitable apartment in Munich?
2. Which district is the most chosen one based on the best ratings?
3. Which apartments are not attractive at all in Munich?
4. What features are contributing to estimate the price of an apartment?

Data Source Date Compiled: 24 December, 2021


## File Descriptions <a name="files"></a>

MY Github repository: [here](https://github.com/SebastianHess/airbnb_munich)

* 02_Project_airbnb_munich_Seb_Hess.ipynb
* README.md
* listings.csv

> Data Source (Date Compiled: 24 December, 2021): [here](http://data.insideairbnb.com/germany/bv/munich/2021-12-24/visualisations/listings.csv)


## Results<a name="results"></a>

Based on the analysis, when visiting Munich and renting an apartment on Airbnb you should:

1. Book your apartment with adequate time upfront.

2. Consider the following districts first to find an good quality apartment:
* Ludwigsvorstadt-Isarvorstadt
* Au-Haidhausen
* Schwabing-West

3. Design your own preferences: Choose an apartment you feel comfortable with.


  Most expensive districts:
* Altstadt-Lehel
* Schwanthalerhöhe
* Ludwigvorstadt-Isarvorstadt

  Least expensive districts:
* Aubing-Lochhausen-Langwied
* Milbertshofen-Am Hart

  Higher priced room type:
* Entire home / Entire apartment
* Hotel room

  Lower priced room type:
* Private room
* Share room

  Biggest price ranged room type:
* Entire home / Entire apartment
* Private room

This is a basic analysis to show the possibilities of a machine learning model. Further and more in-depth analysis and projects could examine the user rating rating to find out how truthful the ratings are.

My Medium Blog: [here](https://medium.com/@sebastian.sh.hess/data-science-airbnb-munich-machine-learning-analysis-755761031699)


## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Thanks to Inside Airbnb for the free available data set.
Thanks to Udacity for the amazing Data Scientist Nanodegree Programm.