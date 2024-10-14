# UK_Property_Data_Analysis
A project analyzing UK property data using Python and GeoPandas

# UK Property Data Analysis

This project showcases an analysis of UK property sales data using Python and geospatial libraries. The project involves processing large datasets, transforming data, creating visualizations, and applying statistical techniques to gain insights into property sales trends across the UK.

## Objective

The objective of this project is to explore various datasets related to UK property sales and address the following key questions:

### Questions Answered in this Project:

1. **Calculate the number of sales and average sale price for London Boroughs in 2023.**
2. **Analyze the sales trends of new build flats since 2020.**
3. **Plot the number of sales per week since 2020 and discuss patterns and anomalies.**
4. **Plot a histogram of property sale prices and discuss the distribution.**
5. **Visualize the number of sales per 10km grid square using geospatial data.**
6. **Visualize the average sale price per 10km grid square.**
7. **Provide a detailed discussion on property price trends based on the analysis.**
8. **Discuss potential improvements to a predictive model based on the findings.**
9. **Explore useful fields from the Energy Performance Certificates (EPC) dataset to enhance the model.**
10. **Explain how to join the EPC dataset with Land Registry data for further analysis.**

These questions have been addressed and thoroughly discussed in the Jupyter Notebook included in this project.

## Data Sources

- **Land Registry:** [Price Paid Data](https://www.gov.uk/government/statistical-data-sets/price-paid-data-downloads)
- **UK Postcodes:** [Postcodes Dataset](https://geoportal.statistics.gov.uk)
- **British National Grid (BNG) Tiles:** [10km Grid Shapefiles](https://github.com/charlesroper/OSGB_Grids)

## Tools Used

- **Python:** For data analysis and visualization.
- **Pandas:** Data manipulation and processing.
- **GeoPandas:** Geospatial data handling.
- **Matplotlib:** For plotting charts and graphs.
- **Jupyter Notebook:** Interactive environment to run Python code.

## Key Features

- **Data Processing:** Loading and cleaning large datasets using Python’s pandas and geopandas libraries.
- **Statistical Analysis:** Calculating mean, median, and distribution of property prices.
- **Visualization:** Using Matplotlib to create visual representations of the data.
- **Geospatial Mapping:** Visualizing property sales data over geographical grids.

## How to Run

To run this notebook:

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/UK_Property_Data_Analysis.git
    ```

2. Install dependencies:

    ```bash
    pip install pandas geopandas matplotlib
    ```

3. Open the Jupyter notebook:

    ```bash
    jupyter notebook Property_Data_Analysis.ipynb
    ```

## Results

- **Sales Trends:** Visualized weekly sales and identified trends in property transactions.
- **Price Distribution:** Generated histograms to assess the distribution of sale prices.
- **Geospatial Analysis:** Created heat maps showing sales distribution and average sale price across different regions.

## Next Steps

- **Further Data Integration:** Enhance the analysis by integrating more datasets, such as energy performance data.
- **Advanced Geospatial Techniques:** Apply more advanced geospatial methods for refined analysis, such as clustering, spatial interpolation, or further regional segmentation.
- **Modeling Property Prices:** Incorporate machine learning models for price prediction using features like property characteristics and geospatial data.

