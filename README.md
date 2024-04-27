# Traffic Crashes - People Analysis Using PySpark

## Introduction
This project analyzes traffic crash data focusing on the individuals involved, using data sourced from the City of Chicago's Data Portal. The analysis is performed using PySpark to handle and process the data efficiently.

## Data Source
- **Dataset**: Traffic Crashes - People
- **Source URL**: [City of Chicago Data Portal](https://data.cityofchicago.org/Transportation/Traffic-Crashes-People/u6pd-qa9d)

## Project Steps
1. **Setup**: Installation of Java, Spark, and Findspark.
2. **Environment Setup**: Configuration of environment variables for Java and Spark.
3. **Spark Session**: Initialization of the Spark session.
4. **Data Importing**: Loading of the dataset into a Google Colab sheet.
5. **Data Viewing**: Initial exploration to determine potential analyses.
6. **Data Cleaning**:
   - Removal of irrelevant columns and rows with NaN or null values.
   - Conversion of column titles to lowercase.
   - Elimination of duplicate records.
7. **Data Wrangling**:
   - Formatting of `crash_date` to MM/dd/yyyy.
   - Filtering the `age` column to include only individuals aged 16 and above.
   - Addition of a year-only column to aid in analysis.
8. **Data Analysis**:
   - Focus on crashes involving drivers, excluding other participant types like passengers or animals.
   - Analysis of crash data by gender and age.
   - Identification of years with higher crash frequencies.
9. **Further Analysis**:
   - Statistical analysis of age data with precision to two decimals.
   - Computation of correlations and covariance between age and year.
   - Calculation of average age of female drivers involved in crashes.

## Conclusion
The project reveals that male drivers, particularly in the age range of 20-40, are more frequently involved in crashes than females. The use of PySpark provided insights into its capabilities compared to Pandas, highlighting the complexity and robust feature set of PySpark, despite its steeper learning curve.

### Advantages and Disadvantages of PySpark vs. Pandas
- **Pandas**:
  - Faster and easier to learn.
  - Code simplicity and clarity.
  - Better for routine tasks with a more user-friendly data display.
- **PySpark**:
  - Requires more in-depth knowledge.
  - Provides powerful distributed data processing capabilities.
  - Less visually appealing data output, but more scalable for large datasets.

## Learning Outcomes
The analysis not only provided insights into traffic crash dynamics but also helped in understanding and comparing the functionalities of PySpark and Pandas in real-world data processing scenarios.

