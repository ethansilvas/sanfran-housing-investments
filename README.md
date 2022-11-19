# Module 6 Challenge - Geospatial Analysis for San Francisco Housing Investments

This is my proptech project that includes interactive data visualizations for a geospatial analysis of properties in San Francisco to find viable investment opportunities. The data used is a combination of quantitative stats for properties in different San Francisco neighborhoods and the coordinate data for each of them. 

**Data from 2010-2016** <br>
[Neighborhood Census Data](/Resources/sfo_neighborhoods_census_data.csv) - sale price per square foot, housing units, and gross rent <br>
[Neighborhood Coordinates](/Resources/neighborhoods_coordinates.csv) - latitude and longitude coordinates

My analysis starts by looking at the average number of housing units and showing the trend from 2010-2016

![Bar graph for number of housing units for each year from 2010-2016](/Images/housing_trends.png)

Then I aggregate the data by year and neighborhood to compare the average gross rent and average sale prices per square foot over time. 

![Line graph of average sale price per square foot and average gross rent for Alamo Square](/Images/sale_price_gross_rent.png)

Finally, I create a geospatial points plot to show the average gross rent and average sale prices per square foot over a map of San Francisco.  

![Geographical OSM map of San Francisco with color points showing data points by neighborhood](/Images/geoplot.png)

Using the generated graphs, I complete my data story by looking at neighborhoods like Silver Terrace ($3528 average gross rent and $170.29 average sale price per square foot) that would be potentially profitable investments for a real estate firm looking to capitalize on the increasing gross rent trend found in the data. 

---

## Technologies

This is a Python 3.7 project ran using a JupyterLab in a conda dev environment. 

The following dependencies are used: 
1. [Jupyter](https://jupyter.org/) - Running code 
2. [Conda](https://github.com/conda/conda) (4.13.0) - Dev environment
3. [Pandas](https://github.com/pandas-dev/pandas) (1.3.5) - Data analysis
4. [Matplotlib](https://github.com/matplotlib/matplotlib) (3.5.1) - Data visualization
5. [Numpy](https://numpy.org/) (1.21.5) - Data calculations + Pandas support
6. [hvPlot](https://hvplot.holoviz.org/index.html) (0.8.1) - Interactive and Geospatial plots


---

## Installation Guide

If you would like to run the program in JupyterLab, install the [Anaconda](https://www.anaconda.com/products/distribution) distribution and run `jupyter lab` in a conda dev environment.

---

## Usage

The Jupyter notebook [san_francisco_housing.ipynb](/san_francisco_housing.ipynb) will provide all steps of the data collection, preparation, and analysis. Data visualizations are shown inline and accompanying analysis responses are provided.

---

## Contributors

[Ethan Silvas](https://github.com/ethansilvas)

---

## License

This project uses the [GNU General Public License](https://choosealicense.com/licenses/gpl-3.0/)
