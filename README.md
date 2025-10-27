# Data Analytics Basics 📊

## 1. Foundations of Data Analysis
- **Data Analysis Definition**: Data analysis is a process of modelling, analyzing, and interpreting data to
extract insights.
- **Data lifecycle**: Use case > Data collection > Storage > Processing > Analysis > Visualization > Communication
- **Types of analytics**: Descriptive, Diagnostic, Predictive, Prescriptive
- **Data roles**: Data Analyst, BI Analyst, Data Scientist, Analytics Engineer, Data Engineer

## 2. Data Sources
- Databases, spreadsheets, APIs, streaming data
- Structured, Semi-structured, Unstructured data
- Data formats: CSV, JSON, Parquet
- Keys & relationships:
  - **Primary**: a unique identifier for each record in a table.
  - **Foreign keys**: a field in a table that refers to the primary key of another table, establishing a relationship between the two tables.
  - 1–1, 1–Many, Many–Many

## 3. Data Preparation (Cleaning & Transformation)
- Handling missing values
- Handling duplicates
- Data types & conversions
- Outlier basics
- Normalization vs Standardization
- Text cleanup (trim spaces, case formatting, remove symbols)

## 4. Exploratory Data Analysis (EDA)
- Descriptive statistics (mean, median, mode, std, percentiles)
- Distributions & variability
- Correlations
- Segmentation

## 5. Business Understanding & Metrics
- KPIs
- Essential business metrics (marketing):
  - Conversion rate
  - Retention rate
  - Growth metrics
  - Cohorts & segmentation
 
## 6. Data Modelling Concepts
- Star schema: fact vs dimension tables
- Granularity
- Slowly changing dimensions (basic awareness)
- Benefits of data modelling (performance, reusability)

## 7. Data Visualisation & Insight Communication
- Chart selection best practices
- Storytelling with data
- Dashboards & Reports

## 8. Documentation & Reproducibility
- Meta data
- Code / Queries / Workflows documentation
- Version control basics
- Communicating assumptions, limitations, and data decisions

### Miscellaneous

**`Data Mining vs Data Profiling:`**

| Aspect            | **Data Mining**                                                     | **Data Profiling**                                              |
| ----------------- | ------------------------------------------------------------------- | --------------------------------------------------------------- |
| **Purpose**       | Extract hidden patterns, correlations, and insights from data       | Understand data quality, structure, and anomalies               |
| **Focus**         | Analytics, prediction, and decision support                         | Assessing data fitness for use before analytics                 |
| **Techniques**    | Machine learning, statistical modelling, clustering, classification | Completeness checks, data type validation, frequency analysis   |
| **Output**        | Trends, predictive models, actionable insights                      | Data quality metrics, metadata summaries                        |
| **Project Stage** | Typically after data preparation                                    | Early phase of data pipeline (before cleansing/transformation)  |
| **Key Benefit**   | Drives strategic and operational decisions                          | Reduces errors and improves reliability of downstream analytics |

#### `Data Normalization:`
The process of structuring data to reduce redundancy and improve integrity—typically by organizing it into related tables and enforcing rules (normal forms) so that each data point is stored once and updated consistently.

#### `Data Warehouse:`
A large centralized repository of data used for reporting and analysis, combining and organizing data from different sources for efficient querying and reporting.

#### `Role of a Data Analyst:`
Collects, processes, and analyzes data to identify trends, patterns and make informed decisions.

#### `Handling Large Datasets:`
Requires the use of efficient data storage and processing techniques such as;
- SQL databases
- Parallel computing: running multiple computations at the same time across multiple processors, rather than sequentially on a single one.
- Cloud-based solutions
- Code optimization (performance tuning)

#### `Latest Trends and Developemts Updates:`
- Blogs
- Podcasts
- Online courses
- Conferences
- Industry publications

#### `Data Privacy and Security Concerns:`
- Data protection regulations
- Anonymizing sensitive data
- Secure data storage and transfer methods
- Access controls
