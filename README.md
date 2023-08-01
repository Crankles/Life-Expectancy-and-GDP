# Life-Expectancy-and-GDP
An analysis into the relationship between GDP life expectancy across 6 countries

---

Investigating time series data using predominantly visual methods.  
The data in `all_data.csv` is in the form:
| Country | Year | Life expectancy at birth (years) | GDP |
| --- | --- | --- | --- |
Where GDP is [Gross Domestic Product](https://en.wikipedia.org/wiki/Gross_domestic_product)

By loading the data into a Pandas `DataFrame`, Seaborn can be used to efficently create visualisations for analysis.  
Firstly this is in the form of bar plots to compare the countries over the entire time period, then with line plots to compare over time.  

Due to the difference in scale of variables such as GDP, in order to more properly see the changes over time, multiple plots were created using a Seaborn `FacetGrid`.

Finally, correlation between GDP and life expectancy was investigated using Pearson correlation.

---

### Dependencies:
- Pandas
- Matplotlib
- Seaborn (v0.11.0+)
- Scipy

---

Data provided by [CodeCademy.com](https://www.codecademy.com/) from the original sources:
- GDP: [World Bank](https://data.worldbank.org/indicator/NY.GDP.MKTP.CD) national accounts data, and OECD National Accounts data files.
- Life expectancy: [World Health Organization](https://apps.who.int/gho/data/node.main.688).
