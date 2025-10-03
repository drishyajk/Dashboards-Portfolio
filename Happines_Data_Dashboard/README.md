Objective :
The purpose of this dashboard is to analyze and visualize the World Happiness Report across multiple counties and regions from 2015 to 2019 . The main objective is to identify the factors affecting happiness, evaluate its impact and visualize happiness trends using interactive dashboards.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Exploratory Data Analysis (EDA) :

During the EDA process, the following steps were carried out before visualization in Power BI:

1.  Data Cleaning
    -   Checked for duplicate entries and removed them.
    -   Validated data types to ensure numerical and categorical fields were consistent.
    -   Standardized and corrected column name ambiguities across multiple tables.
    -   Added a new Year column to distinguish data from different tables.
    -   Identified that some tables were missing the Region column → merged them with reference tables that had complete region information.
    -   Filled missing region values after merging.
    -   Appended all yearly tables into a single master dataset for further visualization.
        
2.  Data Transformation
    -   Converted Year and Region into a slicer for dynamic filtering.
    -   Created DAX queries for calculating:
        -   Average Happiness Score
        -   Most Happiest Country with Aerage Happiness Score
        -   Least Happiest Country with Average Happiness Score
    -   Unpivoted factor columns (GDP, Family, Freedom, Health, Generosity, Trust) to allow yearly comparison of each factor’s contribution to happiness scores.
    -   
3.  Exploratory Insights
    -   We found a total of 166 countries and 11 regions being included in the dataset.
    -   Countries like Denmark, Switzerland, Norway and Finland consistently appear among the top happiest countries.
    -   Sub-Saharan Africa regions rank mong the lowest in happiness scores.
    -   Higher GDP per capita regions like  Western Europe and Central/Eastern Europe generally reflect higher happiness levels.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Conclusion:
-   Happiness is strongly influenced by economic prosperity, social support and health, while generosity and trust show weaker but region-specific impacts.
-   Western European countries consistently rank highest, showing a balance of wealth, equality, and well-being.
-   Regions like Sub-Saharan Africa highlight the need for improved living standards and institutional trust.
-   This dashboard provides an interactive way to compare countries and regions along with year, enabling stakeholders to identify both strengths and challenges globally.

