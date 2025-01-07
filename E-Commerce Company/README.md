# File Title: E-Commerce_Business_Analysis

This was my third project in the TripleTen Business Intelligence Analytics Program! It was an independent project where I applied my Business Analytics skills to transform raw company transaction logs into actionable business metrics.

### Table of Contents for Repository Artifacts
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [E-Commerce_Business_Analysis .pdf](https://github.com/eleonore-rupprecht/TripleTen--Project-Portfolio/blob/main/E-Commerce%20Company/E-Commerce%20Business%20Analysis.pdf) | The completed project in a downloadable pdf file . |
| 2 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 3 | [Requirements.txt](https://github.com/eleonore-rupprecht/TripleTen--Project-Portfolio/blob/main/E-Commerce%20Company/Requirements.txt) | A simple .txt file with the provided project requirements as provided by TripleTen. |

### Table of Contents for README
| Section Title | Description |
| ----------- |----------- |
| Description | Describes the final product's purpose, software, format, and included visuals. |
| Process | A general outline of how this project formed from start to finish. |
| DATA | Describes the source of data, included files, tables, and fields. |
| Assumptions | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| Findings | Insights learned from the data analysis. |
| Recommendations | Recommended direction for the stakeholders based on final analysis. |

#### Description:
- 8 page spreadsheet
- Includes raw data (Hidden), processed data, data analysis, and pivot tables.

#### Process:
I first explored, filtered, and cleaned the data.
Then I created and built a conversion funnel.
I prepared data for cohort analysis.
Calculated retention rates.
Lastly, I finalized the formatting and documentation for the client's readability.

#### Data
The data was one Google spreadsheet file provided by TripleTen. Raw Data Google Spreadsheet can be found <a href='https://docs.google.com/spreadsheets/d/1qWRY5svKGkJRyYNv7K4XvEGm9FpcoJhH5G0p4Qbq0V0/edit?usp=sharing' target=_blank><u>here</u>.</a>
- `'Business Analyst Project.csv'`: raw transaction logs
    - `'raw_user_activity'`: Each row represents an activity, or event, by a user on the company’s website
        - `'user_id'`: unique customer IDs
        - `'event_type'`: the type of activity by the user
        - `'category_code'`: category of the product being viewed or purchased
        - `'brand'`: the company that makes the product
        - `'price'`: price of the product, in USD
        - `'event_date'`: date of the user activity, in YYYY-MM-DD format
    - `'Table of Contents'`: Preformated yet empty table of contents sheet
    - `'Executive Summary`: Preformated yet empty executive summary sheet

#### Assumptions:
- The "raw_user_activity" sheet accurately reflects all website activity for the relevant timeframe.
- Missing values or inconsistencies in the data are minimal and can be ignored.
- The provided data format (columns, data types) is correct and consistent.

#### Findings:
| Results | Synopsis |
| :-----------: | ----------- |
| Conversion Funnel | The total conversion rate from view to purchase was 10%. While the view-to-shopping cart conversion rate was 29% | 
| Retention Rates | Retention rates for the 2020-09 cohort group after the first month were only 13%; by the 4th month, it was down to 3% | 

### Recommendations:
- Address Shopping Cart Abandonment and Purchase Conversion. Future projects can focus on the best approach such as product page vs checkout process as a source of funnel deterioration.
- Enhance customer engagement and loyalty. Potential marketing campaigns could be personalized communications, loyalty programs, and looking into customer support.
- Gain customer feedback for a more targeted strategy.
- Continue data-driven insights to follow changes in the cohort analysis.
