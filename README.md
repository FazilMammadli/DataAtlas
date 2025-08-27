# Atlas of datas across the globe
This repository contains the Power BI report for analyzing various world data metrics, including births, deaths, carbon intensity of electricity, freedom of expression index, GDP, HDI, merchandise exports as GDP, population, life expectancy, expected years of schooling, GNI, and weather forecasts for major cities.
Gathers weather data from cities across the globe with a population greater than 15,000.
Geography and Demographics: Includes a diverse range of indexes and metrics like population, births, deaths, life expectancy, expected years of schooling, and more.
Socio-Economics: Delivers insights on various economic indicators such as GDP, GDP per capita, GNI, and the HDI to gauge economic health and living standards across different regions.
The extensive range of data provides a comprehensive view of global trends and patterns, making it an invaluable resource for analysts, policymakers, data enthusiasts, and anyone interested in understanding the world better through data.
![Dashboard Screenshot]([https://github.com/FazilMammadli/DataAtlas/assets/98173546/88c2e0f2-d105-46cd-8b3e-5377c0c2fe84](https://github.com/FazilMammadli/DataAtlas/blob/main/w_1.png))
![Dashboard Screenshot 2]([https://github.com/FazilMammadli/DataAtlas/assets/98173546/79ca3f30-fc10-44af-b6f2-4d3d2fefbafb](https://github.com/FazilMammadli/DataAtlas/blob/main/w_2.png))


## Getting Started

To use this report, you'll need Power BI Desktop installed on your computer. After cloning or downloading this repository, open the `.pbip` file in Power BI Desktop.

### Configuring Parameters

The report uses several parameters to dynamically load data. Before you can refresh the data in Power BI, you'll need to configure these parameters:

1\. **PathToData**: Set this to the local path where your `.csv` and `.xlsx` files are stored. For example, if your data files are located in `C:\Users\YourName\Documents\WorldDataReport\Data`, you'll set the `PathToData` parameter to this path.

2\. **API Key**: Some data sources in this report require an API key. You'll need to replace the default API key with your own. Obtain an API key from the respective data provider's website and update the `API Key` parameter in the report.

### Data Files

This report requires the following data files to be placed in the `PathToData` directory:

- births-and-deaths-projected-to-2100.csv

- carbon-intensity-electricity.csv

- freedom-of-expression-index.csv

- gdp.csv

- gdp-per-capita.csv

- human-development-index.csv

- merchandise-exports-gdp-cepii.csv

- population.csv

- life-expectancy.csv

- expected-years-of-schooling.csv

- world-banks-income-groups.csv

- major_cities.xlsx (For weather forecast data)

Ensure these files are present in your specified `PathToData` directory before refreshing the data in Power BI.

### Creating and Changing the API Key

Create a free account to get an API key here: [weatherapi.com](https://www.weatherapi.com/)

To change the API key:

1\. Go to the `Transform Data` section in Power BI.

2\. Navigate to the `API Key` query under the `Parameters` folder.

3\. Replace the existing value with your new API key.

4\. Apply the changes.

### Changing the Path to Data Files

To change the path to your data files:

1\. Go to the `Transform Data` section in Power BI.

2\. Navigate to the `PathToData` query under the `Parameters` folder.

3\. Replace the existing path with the path to your data directory.

4\. Apply the changes.

## Refreshing the Data

Once the parameters are correctly set, you can refresh the data in Power BI to load the latest data from your files and APIs.

## Report Usage

Explore the various pages and visuals in the report to analyze the data. Use slicers and filters to narrow down the data and uncover insights.

