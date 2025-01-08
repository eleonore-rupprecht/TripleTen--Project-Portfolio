# File Title: ShopifyPBI

This was my sixth project in the TripleTen Business Intelligence Analytics Program! It was an independent project where I showcased my Power BI skills. The focus was on analyzing data scraped from publicly available Shopify websites to explore the app landscape and identify the key factors driving the success of Shopify apps.

### Table of Contents for Repository Artifacts
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 2 | [Requirements.txt](https://github.com/eleonore-rupprecht/TripleTen--Project-Portfolio/blob/main/Shopify%20(PowerBI)/Requirements.txt) | A simple .txt file with the provided project requirements as provided by TripleTen. |
| 3 | [Shopify_PowerBI analysis.pdf](https://github.com/eleonore-rupprecht/TripleTen--Project-Portfolio/blob/main/Shopify%20(PowerBI)/Shopify_PowerBI%20analysis%20.pdf) | A PDF file showing the work progress of PowerBI Dashboards |

### Table of Contents for README
| Section Title | Description |
| ----------- |----------- |
| Description | Describes the final product's purpose, software, format, and included visuals. |
| Process | Describes the process, including tools or tech used. |
| Data | Describes the data source, including files, tables, and fields. |
| Assumptions | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| Findings | Insights learned from the data analysis. |

#### Description:
- 3 page Power BI Dashboard
- Includes data analysis, KPI cards and Charts

#### Process:
I first assessed the app store landscape using KPI cards and charts.
Then I cataloged review data with cards and charts.
Lastly, I analyzed app developers across review types.

#### Data
The Excel file provided by TripleTenwas was public data scraped from the Shopify App Store.
- `'shopify.xlsx'`: Excel Workbook containing 4 sheets:
    - `'apps'`: Details of the apps on the Shopify apps marketplace
    - `'apps_categories'`: Join tables to connect apps with categories
    - `'categories'`: Categories of the apps. Each app has multiple categories
    - `'reviews'`: Each review (row) contains information on user opinion about the related app (rating and comment). Also, it contains the response from the developer if present.

#### Assumptions:
- The scraped data from Shopify websites is accurate and representative of the actual app landscape.
- The data in the shopify.xlsx file is complete and consistent, with minimal missing values or inconsistencies.
- The provided column names and data types in the tables accurately reflect their content.

#### Findings:
1. New Apps are more likely to be rated early in their deployment.
2. Most apps are rated favorably.
3. Reviews are higher for an app if a developer answers the review.
4. Reviews that have been voted as helpful have a weighted average of 5.48.
5. The app developer "Elfsight" has the highest combined ratings at 135.10 stars.
6. The app developer "Pictorem" has the highest average helpful reviews at 50.
7. The app developer "FireaApps" has responded to the highest amount of reviews at 6,008 responses.
