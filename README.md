# Prices and Slack in the Rental Market: Analysis of Listed Advertisements

> Analyzing the residential rental market in Chile using new indicators based on internet listings to understand price dynamics and market slack.

<p align="center">
<img src="https://www.bcentral.cl/documents/33528/133326/DTBC_988.pdf/8bf1d0a5-501e-69f5-2eb2-2d5fb5e515b2?t=1697649230136" alt="image_github" style="width:300px;height:200;"/>
</p>

## Keywords
Real Estate, Rental Market, Price Dynamics, Market Slack, Internet Listings, Hedonic Pricing

---

## Table of Contents

1. [About the Project](#about-the-project)
2. [Key Features](#key-features)
3. [Key Results](#key-results)
4. [Data Overview](#data-overview)
5. [Methodology](#methodology)
6. [Screenshots and Graphs](#screenshots-and-graphs)
7. [Technologies Used](#technologies-used)
8. [Setup & Installation](#setup--installation)
9. [Usage](#usage)
10. [Contributing](#contributing)

---

### About the Project

This project analyzes the residential rental market in Chile, which has experienced significant growth over the past 15 years. By proposing new indicators based on internet listings, the project aims to understand the evolution of rental and sale prices and their implications for the financial system and real economy.

### Key Features

- **New Indicators**: Developed new measures based on internet listings to analyze the rental market.
- **Price Dynamics**: Studied the impact of market slack on price dynamics at the micro level.
- **Comprehensive Analysis**: Covered various geographical areas in Santiago to provide a detailed understanding of market trends.

### Key Results

- **Price Increases**: Both rental and sale prices increased across different areas in Santiago over the last decade.
- **Market Slack**: The proposed slack measure is relevant for understanding short-term price pressures during periods of lower availability.
- **Economic Impact**: The findings highlight the importance of the rental market for the financial system and real economy.

### Data Overview

The dataset includes internet listings of residential properties in Santiago, Chile, covering various fault conditions. Key data points:

- **Source**: Internet listings from Portalinmobiliario.com, provided by Mercado Libre.
- **Time Period**: Data from 2007 to 2018.
- **Geographical Coverage**: Various communes in Santiago.

### Methodology

This project utilizes hedonic pricing models to analyze the rental market:

- **Hedonic Pricing Models**: Estimate the value of each observable attribute of a property to calculate price evolution for a representative property.
- **Market Slack Measure**: Developed a measure based on the incidence and duration of rental listings to understand market slack.
- **Data Filtering**: Applied filters to remove outliers and ensure data quality.

**Hyperparameters**: 
- Models were estimated using Ordinary Least Squares (OLS) and controlled for regional fixed effects.

### Screenshots and Graphs

These visuals illustrate data distribution, model performance, and key findings:

1. **Class Distribution of Listings (Bar Chart)**  
   Shows the number of listings per fault type, confirming dataset balance.

   <p align="center">
  <img width="413" alt="class_distribution" src="https://www.bcentral.cl/documents/33528/133326/DTBC_988.pdf/8bf1d0a5-501e-69f5-2eb2-2d5fb5e515b2?t=1697649230136">
  </p>

2. **Sample Listings of Rental Properties**  
   Examples of rental properties under various conditions.
<p align="center">
<img width="380" alt="thermographic_samples" src="https://www.bcentral.cl/documents/33528/133326/DTBC_988.pdf/8bf1d0a5-501e-69f5-2eb2-2d5fb5e515b2?t=1697649230136">
</p>

3. **Price Dynamics Comparison (Bar Chart)**  
   Comparison of rental and sale price dynamics across different areas.
  <p align="center">
  <img width="373" alt="model_accuracy" src="https://www.bcentral.cl/documents/33528/133326/DTBC_988.pdf/8bf1d0a5-501e-69f5-2eb2-2d5fb5e515b2?t=1697649230136">
  </p>

4. **Market Slack Measure**  
   Displays the incidence and duration of rental listings, showing market slack.
  <p align="center">
  <img width="510" alt="Captura de pantalla 2024-11-11 a la(s) 7 45 37 p  m" src="https://www.bcentral.cl/documents/33528/133326/DTBC_988.pdf/8bf1d0a5-501e-69f5-2eb2-2d5fb5e515b2?t=1697649230136">
  </p>

5. **Price and Slack Dynamics Over Time**  
   Shows the relationship between rental prices and market slack over time.
  <p align="center">
  <img width="912" alt="losses" src="https://www.bcentral.cl/documents/33528/133326/DTBC_988.pdf/8bf1d0a5-501e-69f5-2eb2-2d5fb5e515b2?t=1697649230136">
  </p>
  

6. **Efficiency Comparison of Models**  
   Compares the efficiency of different models in analyzing price dynamics.
<p align="center">
  <img width="729" alt="test_time" src="https://www.bcentral.cl/documents/33528/133326/DTBC_988.pdf/8bf1d0a5-501e-69f5-2eb2-2d5fb5e515b2?t=1697649230136">
  </p>



### Technologies Used

> 🛠️ Emphasizing the primary tools and libraries utilized.

- ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white): Main programming language.
- **🔥 R**: Used for implementing and training the hedonic pricing models.
- **📊 Data Mining**: Leveraged data mining techniques to extract relevant information from internet listings.

### Setup & Installation

Clone the repository and install the required dependencies to run the project:

```bash
# Clone the repository
git clone https://github.com/username/Rental-Market-Analysis.git

# Navigate to the project directory
cd Rental-Market-Analysis

# Install dependencies
pip install -r requirements.txt
```

### Usage

The repository includes the following file:

- **`Rental_Market_Analysis.ipynb`**: Jupyter notebook containing the full workflow, from data loading and preprocessing to model training and evaluation.

To run the project, open `Rental_Market_Analysis.ipynb` in Jupyter Notebook and execute the cells sequentially.

### Contributing

Contributions are welcome! Please see the contributing guidelines for more details.
