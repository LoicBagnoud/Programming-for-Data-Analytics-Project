## 1. Introduction

This project analyses mortality statistics in Ireland using data from the Central Statistics Office (CSO) - Namely **Age-Standardised Mortality Rate. [Central Statistics Office (CSO)](https://data.cso.ie/)  
The main goals are:

1. **Data cleaning** – Deal with missing values, inconsistent formats, and outliers.  
2. **Exploratory Data Analysis (EDA)** – find trends over time and differences by sex, age group, cause of death, and region (depending on what the dataset provides).  
3. **Insights / Conclusion** – Try and get some specific insights on the results found.

This notebook is intended to demonstrate the full data analysis workflow, from raw CSV to model and conclusions.

## Table of Contents
- [Packages needed](#Packages-needed)
    - [Numpy](#Numpy)
    - [Pandas](#Pandas)
    - [Seaborn](#Seaborn)
    - [Matplotlib](#Matplotlib)
- [Findings](#Findings)
    - [Git Organisation](#Git-Organisation)
    - [Summarising the Data](#Summarising-the-Data)
- [References](#References)

## Packages needed

To run this project, you'll need Python 3 installed on your machine. You can download the latest version from the official Python website: https://www.python.org/downloads/
>
Please make sure you follow the instructions outlined there. Additionally, this code uses several packages in order to achieve most of the tasks' objectives. It is expected that those are also properly downloaded and installed on your machine.
>
Instrutions are provided in each package below in order to install them but it is advisable to use Anaconda Distribution as it already contains these packages pre-installed. You can download Anaconda Distribution from here: https://www.anaconda.com/download/success

All of the packages required are as follows:
>
- Matplotlib
- Numpy
- Pandas
- Seaborn
>
All of these packages can be imported using the _import_ function. What follows is a list of the different packages and small descriptions alongside links on how to download them and install if you prefer not to use Anaconda Distribution.
>
#### Numpy
>
[Numpy](https://numpy.org/) provides support for large, multi-dimensional arrays and matrices, along with a wide range of mathematical functions to perform operations on them efficiently. It's the foundation for many scientific and data libraries, including Pandas and scikit-learn. For more information on how to install Numpy, please see the following: https://numpy.org/install/
>
#### Pandas
>
[Pandas](https://pandas.pydata.org/docs/index.html) is a powerful and user-friendly Python library for working with structured data. It's especially well-suited for datasets, like the Iris dataset, where each column can hold different data types. With its efficient data structures and analysis tools, Pandas makes it easy to explore and manipulate data with both numerical and categorical values. For more information on how to install Pandas, please see the following: https://pandas.pydata.org/docs/getting_started/install.html
>
#### Matplotlib
>
[Matplotlib](https://matplotlib.org/) is an especially useful package for plotting data in formats like line charts, bar graphs, scatter plots, and more. For more information installing matplotlib, please see the following: https://matplotlib.org/stable/users/getting_started/
>
#### Seaborn
>
As per their website, [Seaborn](https://seaborn.pydata.org/) is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics. For more information installing matplotlib, please see the following: https://seaborn.pydata.org/installing.html

>
For more help in understanding and dealing with each package, please make sure to review and investigate the relevant documentation if anything remains unclear:
>
- [Numpy Documentation](https://numpy.org/doc/stable/)
- [Pandas Documentation](https://pandas.pydata.org/docs/index.html)
- [Matplotlib Documentation](https://matplotlib.org/)
- [Seaborn Documentation](https://seaborn.pydata.org/)

## Findings

### Git Organisation

The following repository was organised in a way that is in line with most data analytics repositories, with separate cleaned data and raw data folders containing the analysed data. The Jupyter Notebook contains all the required information, including explanations of how the code works and how references were used.

### Summarising the Data

Explanations of the data set analysis can also be found in the Jupyter Notebook alongside the code explanations. Code references will be included inside the actual code as comments.
>
Below, you will also find a list of references. These have been included at the end of the Jupyter Notebook as well. Superscript reference numbers are used to indicate where each reference was applied.

### References:

- Eric Ma (n.d.) How to organize your Python data science project. GitHub Gist. Available at: https://gist.github.com/ericmjl/27e50331f24db3e8f957d1fe7bbbe510
 (Accessed: 1 December 2025).

- GeeksforGeeks (2025) Working with missing data in Pandas. Available at: https://www.geeksforgeeks.org/data-analysis/working-with-missing-data-in-pandas/
 (Accessed: 4 December 2025).

- OpenAI (2025a) ChatGPT response to “Clarifying if empty dataframes meant that no duplicates were found”, 4 December. Available at: https://chatgpt.com/share/6931d4c6-1c98-800b-9281-3ad3f9c30654
 (Accessed: 4 December 2025).

- Stack Overflow (n.d.) ‘How to find if a particular column has zero value in a dataframe?’. Available at: https://stackoverflow.com/questions/71989791/how-to-find-if-if-a-particular-column-has-zero-value-in-a-dataframe
 (Accessed: 4 December 2025).

- McNutt, L.-A. (n.d.) Cumulative incidence. Encyclopaedia Britannica. Available at: https://www.britannica.com/science/cumulative-incidence
 (Accessed: 4 December 2025).

- 
    -  World Health Organization Regional Office for Europe (2025) Avoidable mortality, risk factors and policies for tackling noncommunicable diseases – leveraging data for impact: monitoring commitments in the WHO European Region ahead of the Fourth United Nations High-Level Meeting. Copenhagen: WHO Regional Office for Europe. Available at: https://www.drugsandalcohol.ie/43599/1/WHO-EURO-2025-12445-52219-80271.pdf
 (Accessed: 4 December 2025).

    - 6.2 Eurostat (2020) ‘Two-thirds of deaths under 75 could have been avoided’, Eurostat News, 14 August. Available at: https://ec.europa.eu/eurostat/web/products-eurostat-news/-/ddn-20200814-1
 (Accessed: 4 December 2025).

- Hey Amit (2025) ‘Understanding isin with ~ (NOT) in Pandas’, Medium, 20 February. Available at: https://medium.com/@heyamit10/understanding-isin-with-not-in-pandas-b20099c4ed63
 (Accessed: 4 December 2025).

- Towards Data Science (n.d.) How to replace values in Pandas. Available at: https://towardsdatascience.com/how-to-replace-values-in-pandas-609ba7a031c9/
 (Accessed: 4 December 2025).

- LeanScape (n.d.) Demystifying standard deviation: a beginner’s guide. Available at: https://leanscape.io/demystifying-standard-deviation-a-beginners-guide/
 (Accessed: 12 December 2025).

- Luzmo (n.d.) Chart types. Available at: https://www.luzmo.com/blog/chart-types
 (Accessed: 14 December 2025).

- Central Statistics Office (n.d.) Deaths 2022. Vital Statistics Annual Report 2022. Available at: https://www.cso.ie/en/releasesandpublications/ep/p-vsar/vitalstatisticsannualreport2022/deaths2022/
 (Accessed: 4 December 2025).

- Matplotlib (n.d.) Bar chart. Available at: https://matplotlib.org/stable/gallery/lines_bars_and_markers/barchart.html
 (Accessed: 14 December 2025).

- OpenAI (2025b) ChatGPT discussion on grouped bar chart code, 14 December. Available at: https://chatgpt.com/share/693ef4f5-a7f4-800b-bdab-b6d656453acc
 (Accessed: 14 December 2025).

- Medium (n.d.) ‘7 visualizations with Python to handle multivariate categorical data’. Available at: https://medium.com/data-science/7-visualizations-with-python-to-handle-multivariate-categorical-data-63158db0911d
 (Accessed: 15 December 2025).

- OpenAI (2025c) ChatGPT discussion on best plot for sex and age visualisation, 15 December. Available at: https://chatgpt.com/share/694059f0-a354-800b-8a67-4a61ea91a801
 (Accessed: 15 December 2025).

- GeeksforGeeks (n.d.) Create a stacked bar plot in Matplotlib. Available at: https://www.geeksforgeeks.org/python/create-a-stacked-bar-plot-in-matplotlib/
 (Accessed: 16 December 2025).

- World Health Organization (2016) ICD-10 Version: 2016. Available at: https://icd.who.int/browse10/2016/en#/XVII
 (Accessed: 19 December 2025).

- OpenAI (2025d) ChatGPT discussion on organising causes of death, 19 December. Available at: https://chatgpt.com/share/694597d9-6330-800b-b5f9-b4652f2c947a
 (Accessed: 19 December 2025).

- CoderzColumn (n.d.) Population pyramid chart using Matplotlib. Available at: https://coderzcolumn.com/tutorials/data-science/population-pyramid-chart-using-matplotlib
 (Accessed: 23 December 2025).

- Mental Health Ireland (2025) Research: key findings. Available at: https://www.mentalhealthireland.ie/wp-content/uploads/2025/10/MHI-2025-Research_-Key-Findings.pdf
 (Accessed: 24 December 2025).

- Movember (2025) The real face of men’s health: Ireland report 2025. Available at: https://movember.com/uploads/files/2025/Movember%20-%20The%20Real%20Face%20of%20Men's%20Health%20Report%20Ireland%202025.pdf
 (Accessed: 28 December 2025).