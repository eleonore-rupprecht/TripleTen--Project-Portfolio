# File Title: Manhattan Vacation Rental Market Project

This is VERSION 2 of the first project I worked on in the TripleTen Business Intelligence Analytics Program. It was an independent project designed to showcase what I have learned about Advanced Spreadsheets. This project is about analyzing Airbnb listings in Manhattan, NYC to help a client decide what type of vacation rental property to invest in.

### Table of Contents for Repository Artifacts
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [Manhattan Vacation Rental Market_Part 1.pdf](https://github.com/eleonore-rupprecht/TripleTen--Project-Portfolio/blob/main/Manhattan%20Vacation%20Rental%20Market/Manhattan%20Vacation%20Rental%20Market-Part%201.pdf)
| 2 | [Manhattan Vacation Rental Market_Part 2.pdf](https://github.com/eleonore-rupprecht/TripleTen--Project-Portfolio/blob/main/Manhattan%20Vacation%20Rental%20Market/Manhattan%20Vacation%20Rental%20Market-Part%202.pdf)
| 3 | [Project Rubric V2.pdf]((https://github.com/eleonore-rupprecht/TripleTen--Project-Portfolio/blob/main/Manhattan%20Vacation%20Rental%20Market/Project%20Rubric%20V2.pdf)| A .PDF file with the provided template for grading. |
| 4 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 5 | [Requirements.txt](https://github.com/eleonore-rupprecht/TripleTen--Project-Portfolio/blob/main/Manhattan%20Vacation%20Rental%20Market/Requirements.txt) | A simple .txt file with the provided project requirements as provided by TripleTen. |

### Table of Contents for README
| Section Title | Description |
| ----------- |----------- |
| Description | Describes the final product's purpose, software, format, and included visuals. |
| Process | Describes the process, including tools or tech used. |
| DATA | Describes the source of data, included files, tables, and fields. |
| Assumptions | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| Findings & Recommendations | Insights and suggested considerations learned from the data analysis. |

#### Description:
- 10 page spreadsheet
- Includes organizational tabs, raw data (Hidden), processed data, data analysis, pivot tables, and bar charts.

#### Process:
1) **Data Preparation**: *Filtering* techniques were used to identify and clean inconsistencies within the Airbnb data. Irrelevant columns were hidden to maintain a focused analysis. Key functions such as PROPER, TRIM, IF, ISNUMBER, FIND, ROUND, SUMIF, VLOOKUP, CHOOSE, and WEEKDAY were employed for data tidying.
2) **Neighborhood Analysis**: Identify the top-performing neighborhoods based on review frequency via *Pivot Table*.
3) **Property Size Analysis**: Determine the optimal property sizes for each neighborhoodvia *Pivot Table* showcased with *conditional formatting*.
4) **Revenue Analysis**: Calculate estimated annual revenue for the most attractive listings.
5) **Data Visualization**: Create clear and informative *visualizations* (charts) to present findings.
6) **Formatting and Organization**: Ensure your analysis is well-formatted for ease of readability.
7) **Documentation**: Create organizational sheets like an executive summary, table of contents, assumptions log, and change log.
 
#### Data
The data was one Google spreadsheet file provided by TripleTen, Copy can be found [HERE](https://docs.google.com/spreadsheets/d/1Z7KNEYs_YtQP57mWXRddPGAI3Sk-tPzLnCsdysCSw_c/edit?usp=sharing):
- `'nyc_airbnb_data.csv'`: each row corresponds to one listing on Airbnb in September 2022
    - `'data_dictionary'`: summary of field titles seen in the file and its data type
    - `'listings'`: uniquely listings available with all available data
    - `'calendar'`: listings with upcoming availabilities and date-type data

#### Assumptions:
-Airbnb rentals are equivalent to the general short-term vacation rental market.
-Only properties with a Minimum night requirement of 7 days or less were considered. 
-Properties with no reviews in the last 12 months were considered inactive.
-Reviews reflect rental frequency, we used "number_of_reviews_ltm" to measure a listing's attractiveness.
-Super luxury listings with prices greater than $1,321.21 were filtered from the analysis, 1% outlier.
-Extremely low-priced listings of less than $85.28 were filtered from the analysis, 1% outlier.
-Estimated Annual Revenue can be calculated by comparing averages for top listings.
-"Building staff" equates to a Doorman
-A listing of 9k can be excluded when examining price/review due to it being an extreme outlier.

#### Findings and Recommendations:
1. The top recommended neighborhoods for vacation rentals are as follows: Lower East Side, Hell's Kitchen, Harlem, Midtown, Upper West Side, Chelsea, East Village, East Harlem, West Village, Upper East Side.	
2. The top rental size is 1 bedroom overall. Lower East Side properties should have 1-bedrooms to meet demand. Hell's Kitchen prefers 2 bedrooms and Midtown prefers Studio.	
3. The estimated annual revenue based on top listing characteristics is $69,957.	
