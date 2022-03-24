# COVID-19 Pandemic in Greece: Cases, Deaths, and Vaccination Progress

<p align="center">
    <a href="https://nbviewer.jupyter.org/github/KOrfanakis/COVID-19_in_Greece/blob/main/COVID-19_Pandemic_in_Greece.ipynb">
        <img alt="Render With" src="https://img.shields.io/badge/Render%20with-nbviewer-c0220d.svg">
    </a>
    <a href="https://www.python.org/">
        <img alt="Made with" src="https://img.shields.io/badge/Made%20with-Python-blue.svg">
    </a>
    <a href="https://jupyter.org/try">
        <img alt="Made with and" src="https://img.shields.io/badge/And%20-Jupyter-orange.svg">
    </a>
    <a href="https://opensource.org/licenses/MIT">
        <img alt="Licence" src="https://img.shields.io/badge/License-MIT-0298c3.svg">
    </a>
    <a>
        <img alt="Star if useful" src="https://img.shields.io/static/v1?label=%F0%9F%8C%9F&message=If%20Useful&style=style=flat&color=0aa619">
    </a>
    <br/>
</p>

**Table of Contents**:

<!--ts-->

- [Motivation](#motivation)
- [How to View](#how-to-view)
- [Data](#data)
- [Resources Used](#resources-used)
- [Feedback](#feedback)

<!--te-->

<br>

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

Python Version: 3.10.2 <br>
Jupyter Notebook Version: 6.4.8 <br>
Packages: Pandas (1.4.1), Plotly (5.6.0), Matplotlib (3.5.1), PyWaffle (0.6.4), and NumPy (1.22.2)

<br>

## Feedback

If you have any feedback or ideas to improve this project, feel free to contact me via:

<a href="https://twitter.com/korfanakis">
  <img align="left" alt="Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />
</a>

<a href="https://uk.linkedin.com/in/korfanakis">
  <img align="left" alt="LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />
</a>
