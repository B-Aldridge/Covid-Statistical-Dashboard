# Project3_COVID_Stats
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Javascript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=Leaflet&logoColor=white)

This repository contains the code for the Interactive Covid Statistical Dashboard, which was developed as a project part of the Vanderbilt Data Analytics Bootcamp in 2023. The project focuses on creating a website with multiple visualization tools for analyzing the relationships between COVID deaths and infections, population density, tourism, and vaccination within a country.

# How to Run the Code
To run the code, follow the steps below:

1. Ensure that you have a MongoDB local server running.
2. Import the "owid_covid_data" collection into your local MongoDB database. The collection can be imported from the file databases/local.owid_covid_data.json.
3. Run the file Dashboard/app.py. This will launch the website using Flask.

# Project Files
The root directory of this repository contains the following files:

•Group1ProposalProject3.docx: The initial written proposal for this project. It outlines the project objectives and goals.

•layout.pdf: The original layout idea for the project. Please note that the final implementation may have some differences due to feasibility considerations, but it generally addresses the original intent.

Feel free to explore the code and project files to understand the implementation details and how the visualizations were created.

# Credits
Team responsible for the formation of this project:

Andrew Lounsbury: (https://github.com/a676-code)

Kirill Zavalin: (https://github.com/KZavalin)

Joshua Aldridge: (https://github.com/B-Aldridge)

Madi Subaiti: (https://github.com/mssubaiti)

Seth B: (https://github.com/SNbeverley)

# Data Sources
The following data sources were used for this project:

[World Health Organization (WHO) COVID-19 Data](https://covid19.who.int/data): The project scraped data from this website to gather COVID-19 related information such as deaths, infections, and vaccinations.

[Worldometer](https://www.worldometers.info/coronavirus/): This website was also scraped to collect COVID-19 data, including deaths and infections.

[Our World In Data](https://ourworldindata.org/covid-vaccinations): This website was used to download the CSV file with Covid-19 data which contained a large portion of the metrics used.

[World Bank](https://data.worldbank.org/indicator/ST.INT.ARVL?end=2020&start=2020&view=map&year=2020): This website was used to download a csv of tourism data for our visualization.



