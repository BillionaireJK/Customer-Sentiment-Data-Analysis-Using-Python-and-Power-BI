# Customer Sentiment Data Analysis Using Python And Power BI

This project focuses on analyzing customer sentiment through the implementation of the NLTK (Natural Language Toolkit) algorithm on product web reviews. The process involves extracting data from a SQL database, applying sentiment analysis using Python, generating CSV files, and then visualizing the data in Power BI for deeper insights.

## Dependencies

- Python 3.x
- NLTK (Natural Language Toolkit)
- SQL Server (or any SQL database)
- Power BI Desktop (for visualization)

## Project Structure

1. **Database Setup**: 
    - Ensure the availability of the SQL database containing the product web reviews. 
    - Make sure the necessary credentials and permissions are set up for access.

2. **Python Script for SQL Extraction (extract_data.py)**:
    - Utilize this script to connect to the SQL database and extract relevant data.
    - Ensure that the script handles any necessary data transformations or filtering required.

3. **Python Script for NLTK Algorithm (sentiment_analysis.py)**:
    - This script implements the NLTK algorithm for sentiment analysis.
    - It takes the extracted data as input and generates sentiment scores for each review.

4. **Python Script for Generating CSV File (generate_csv.py)**:
    - After sentiment analysis, use this script to generate CSV files containing the processed data.
    - Customize the script to include any additional metadata or formatting required.

5. **Automatic Upload of CSV File in Power BI**:
    - Set up an automated process or schedule to upload the generated CSV files to Power BI.
    - Utilize Power BI APIs or any relevant integration tools for seamless data transfer.

6. **Data Processing in Power BI**:
    - Upon uploading the CSV files, perform necessary data processing steps in Power BI.
    - This may include data cleansing, transformation, and merging with other datasets if needed.

7. **Visualization in Power BI**:
    - Leverage Power BI's visualization capabilities to create insightful dashboards and reports.
    - Design visualizations that effectively communicate customer sentiment trends and patterns.






