# COVID-19 Pandemic in Greece: Cases, Deaths, and Vaccination Progress

## Motivation

This notebook aims to provide an overview of the COVID-19 pandemic in **Greece</b>**. Specifically, it explores:
-	The current situation and how the pandemic has evolved since its beginning.
-	How vaccinations are progressing in the country.

The notebook is by no means a complete analysis. Its goal is to paint the general picture of COVID-19 in Greece through various visualisations. 
It is written so that it can be reused for any other country, provided that the country's name exists in all four datasets.

I have summarised the visualisations in a PowerPoint presentation, which you can find in this [repository](https://github.com/KOrfanakis/COVID-19_in_Greece/blob/main/Summary.pptx).

<br>

## How to View

Since the notebook is rendered as a static HTML file in the repository, its interactive features (Plotly plots) will not be displayed. 
To view the notebook with interactive content you can use [nbviewer](https://nbviewer.jupyter.org/github/KOrfanakis/COVID-19_in_Greece/blob/main/COVID-19_Pandemic_in_Greece.ipynb), [Kaggle](https://www.kaggle.com/korfanakis/covid-19-pandemic-in-greece-an-overview) or run it locally.

**Note**: Interactive maps cannot be displayed with the nbviewer. Consequently, maps will be displayed as static images using the `svg` renderer. 
To access the interactive version, please visit the notebook on [Kaggle](https://www.kaggle.com/korfanakis/covid-19-pandemic-in-greece-an-overview) or run the notebook locally after removing the `svg` rendered from the `fig.show()` command.

<br>

## Data

Our analysis requires five datasets. 

- **Summary and Daily Data on COVID-19**: These two datasets were scraped from [woldometers.info](https://www.worldometers.info/coronavirus/) by [Joseph Assaker](https://www.kaggle.com/josephassaker), who maintains them on [Kaggle](https://www.kaggle.com/josephassaker/covid19-global-dataset).

- **Tests Dataset**: Data were collected directly from [Our World in Data](https://ourworldindata.org/)'s GitHub [repository](https://github.com/owid/covid-19-data) for COVID-19 using Pandas' `read_csv()` method.

- **Vaccination Dataset**: Data were collected from [Our World in Data](https://ourworldindata.org/)'s GitHub [repository](https://github.com/owid/covid-19-data) for COVID-19, merged and uploaded on [Kaggle](https://www.kaggle.com/gpreda/covid-world-vaccination-progress) by [Gabriel Preda](https://www.kaggle.com/gpreda).

- **Government Response Tracker Dataset**: Data from the Oxford Coronavirus Government Response Tracker (OxCGRT) on [Github](https://github.com/OxCGRT/covid-policy-tracker), published and managed by researchers at the Blavatnik School of Government at the University of Oxford. The dataset was retrieved directly from the repository using Pandas' `read_csv()` method.

<br>

## Resources Used

Python Version: 3.7 <br>
Jupyter Notebook Version: 5.7.8 <br>
Packages: pandas, plotly, matplotlib, pywaffle, and numpy
