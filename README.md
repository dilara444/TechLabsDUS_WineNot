# TechLabsDUS_WineNot?
Nov2023-March2024

Welcome to our 'WineNot?' GitHub Repository! This project serves as an educational resource for individuals interested in learning fundamental coding concepts using Python. Whether you’re a beginner or an experienced programmer, this repository aims to provide clarity on some data science structures and strategies. Therefore, an implemented dataset was selected, to help unterstanding and improving. 
> GitHub Link
https://github.com/dilara444/TechLabsDUS_WineNot.git

> For inspiration and motivation: https://open.spotify.com/track/4uOKFydzAejjSFqYbv1XPt?si=6a240536f0de4cdc

## Objective:

Our journey startet first with a dataset of physiochemical quality description and prediction of red wines in portugal, which we had to dismiss due to the complexity of the dataset. We initally wanted to combine this with another dataset, the wine review dataset (mentioned below), but concluded that it would be better to continue with this one only, instead. The main reason was, that we could analyze more with the other dataset and had more variables to research on. This allowed us to explore our creativity in our skills and even try new approaches to begin with. 

We've started to work on the wine reviews dataset to uncover insights about wine quality, regional preferences, and pricing trends. It helped us to build a deeper understanding on which characteristics define a wine as high-quality and tasty and many other factors given in this dataset. Therefore, we visualizated various factors that distinguish corresponding wine characteristics. 

## Project Scope
We use Wine Reviews Data 
> https://www.kaggle.com/datasets/zynicide/wine-reviews

The scope of this project was to get an insight about some characteristics of different wine types all over the world. 
From there for our analysis we took Country, Description, Points, Price, and Variety as main variables of interest. This dataset showed interests of different insides to wine types from different countries. Besides the very obvious connection between wine origin and respective rating of this, other characteristics such as taste desription and price did contribute to a deeper understanding of both economical and physiological composition of wines. 

## Goals
When starting newly to code, the amount of numbers and variables in a dataset can be pretty overwhelming. Allow yourself to look into the dataset first before running a few commands. The understanding of certain structures in a dataset helps to form first ideas of analysis and connect some crucial points. 
After getting familiar with the project, we defined our goals for this dataset as following:
- Identifying popular wine varieties and their characteristics.
- Analyzing the relationship between wine quality ratings and prices.
- Assessing the extent to which the price correlates with the quality of the wine.
- Examining wine quality for each country and defining locations of best wines.
- Understanding how wine descriptions depending on good or (relatively) bad wines are observed.

## Approach
We initially generated and collected our initial thoughts and ideas. Subsequently, we proceeded to apply specific techniques related to plotting, putting our theoretical knowledge into practical use. During this process, we identified a potential source of confusion in our subsequent ideas. Consequently, we modified the country name descriptions for those regions not previously defined in the ‘geopandas’ library. The corrected dataset served as input for our analysis, where we employed the following approaches:

- Exploratory data analysis (EDA) to understand the structure and patterns in the data.
- Various approaches were implemented to demonstrate the connections and outstanding characteristics for some wine types.
- Statistical analysis to uncover relationships and correlations between price and points.
- Data visualization techniques (plots, mapping, wordcloud) to underline certain connections and relations.
- In most plots we consider best wines to have points >= 95.
- The worst wines presented in this dataset have points >= 80 and <=85.
- For more detailed analysis of wine characteristics in specific countries we took Europe as object of study, but for main plots we considered the wine data of the whole world (as far as the dataset allowed us to do so).

## Used Libraries
#### Pandas
- Purpose: Pandas is a powerful data manipulation library that provides data structures (such as DataFrames and Series) for efficient handling of structured data. It is widely used for data cleaning, transformation, and analysis.
- Usage: For this project, Pandas was used to load data from various sources (CSV files, databases, etc.) into a Pandas DataFrame, perform operations like filtering, aggregation, and join tables, and then visualize or analyze the data.

  > import pandas as pd
  
#### Geopandas
- Purpose: Geopandas extends Pandas to handle geospatial data. It allows you to work with geographic shapes (e.g., polygons, points, lines) and perform spatial operations (e.g., spatial joins, buffering).
- Usage: This library was used to create maps or analyze spatial relationships.

  > import geopandas as gpd

#### Matplotlib
- Purpose: Matplotlib is a versatile plotting library for creating static, animated, or interactive visualizations. It provides a wide range of customizable plots (line plots, scatter plots, bar charts, etc.).
- Usage: Matplotlib helped us to create histograms, scatter plots, heatmaps, and more. The provided code snippet imports necessary modules and sets up the plotting environment:
  
  > import matplotlib.pyplot as plt
  
  > from matplotlib.colors import Normalize
  
  > from matplotlib import cm
  
  > import matplotlib.patches as mpatches

#### Numpy
- Purpose: Numpy is a fundamental library for numerical computing in Python. It provides support for large, multi-dimensional arrays and matrices, along with mathematical functions.
- Usage: The Numpy library was useful for sorting and calculating values. The library itself is essential for scientific computing, linear algebra, and statistical operations. It’s commonly used for array manipulation and mathematical computations.

   > import numpy as np

#### Seaborn
- Purpose: Seaborn is a statistical data visualization library built on top of Matplotlib. It simplifies creating attractive and informative statistical plots.
- Usage: For data vizualisation besindes basic histograms, barplots etc, we used Seaborn. It can generate beautiful visualizations for exploring relationships between variables, distribution plots, and regression plots.

  > import seaborn as sns

#### SciPy
- Purpose: SciPy is an ecosystem of libraries for scientific and technical computing. It includes modules for optimization, integration, interpolation, and statistical functions.
- Usage Example: You can use SciPy for advanced statistical analysis, hypothesis testing, and solving mathematical problems. The provided code snippet installs SciPy and imports relevant functions.

   > import sys
  
  > !{sys.executable} -m pip install scipy
  
  > from scipy.stats import kurtosis, skew
  
  > from scipy import stats
  
#### Wordcloud
- Purpose: Wordcloud is a library for creating word clouds, which visually represent the frequency of words in a text corpus.
- Usage Example: Given a collection of text data (e.g., reviews, articles), you can generate word clouds to highlight common terms or themes.
  > from wordcloud import WordCloud

## Expected Outcome
- Insights into wine preferences and market peculiarities for wine producers and distributors.
- Recommendations for consumers based on wine price, quality, taste, and country characteristics.
- Contribution to the broader wine community by sharing knowledge and insights gained from the analysis.
- Analysis contributes to understanding of various connections between wine origin, taste, price and so much more.
- For further analysis, predictions on the connection between price, taste and rating of wines can be considered.

## Summary
#### Exploring Wine Reviews: Insights and Discoveries
In our notebook titled “WineNot?”, we present the culmination of our analytical journey. By harnessing our collective ideas, we steered our analysis toward meaningful directions, unlocking new avenues for creativity. As we solved one challenge, it sparked additional inquiries, leading us to explore diverse plotting techniques and uncover connections within the realm of wine characteristics.

### Our Key Achievements
- Heatmaps for Global Wine Prices: We visualized price ranges for various wine varieties worldwide, with a special focus on Europe. Delving deeper, we encountered an interesting issue: the irregularity of country names compared to the predefined list in the ‘geopandas’ library. Our ability to address this discrepancy while maintaining our focus was a dual victory.
- Quality-Price Nexus: Recognizing the inherent link between wine quality and prices, we expanded our analysis to include different wine types. To draw meaningful conclusions, we segmented this investigation by specific countries. Each nation revealed distinct wine characteristics, emphasizing the importance of country-based segmentation.
### Further Insights and Contributions
Our exploration journey yielded valuable insights and contributions to the world of wine:
- Insights into Wine Preferences and Market Peculiarities: For wine producers and distributors, our analysis provides a deeper understanding of consumer preferences and market dynamics. By identifying trends and patterns, we empower stakeholders to make informed decisions.
- Consumer Recommendations: Based on wine price, quality, taste, and country characteristics, we offer personalized recommendations to consumers. Whether it’s selecting the perfect bottle for a special occasion or exploring new flavors, our insights guide wine enthusiasts.
- Community Contribution: Sharing knowledge and insights gained from our analysis, we contribute to the broader wine community. By fostering dialogue and collaboration, we collectively elevate our understanding of this complex and delightful beverage.
- Unraveling Connections: Our analysis contributes to the understanding of various connections between wine origin, taste, and price. From terroir effects to cultural influences, we delve into the intricate web that defines each bottle.

Besides our work so far, we want to raise awareness about predictive possibilities for this dataset. Looking ahead, we consider predictions related to the connection between price, taste, and wine ratings. By leveraging machine learning and statistical models, understanding and guidence of future research can be enhanced.

#### Learning and Growth:
Our journey taught us to apply both fundamental and advanced methods to understand datasets thoroughly. Moreover, our exploration of various libraries enriched our plotting skills and fueled our creative endeavors.

In summary, “WineNot?” encapsulated our pursuit of knowledge, problem-solving progress, and the joy of unraveling wine-related insights. 



