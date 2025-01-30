# ETL-Workflow-with-Python
## Introduction:
    The Extract, Transform, Load (ETL) process is essential for data engineers, enabling them to manage data from various formats and transform it for further use. In this project, we will demonstrate how to extract data from CSV, JSON, and XML formats, transform it, and load the transformed data into a structured format for further processing.

## Objectives:

  By the end of this project, you will be able to:
  Extract data from CSV, JSON, and XML files.
  Transform the extracted data into a desired format, including unit conversions.
  Load the transformed data into a CSV file for future use in databases.
  Log the progress of ETL operations for monitoring purposes.

## Dataset :
  Attached in the repository

## Steps:

**Step 1: Gather Data Files**

**Step 2: Import Libraries and Set Paths**
  1. Import necessary libraries like:
  2. glob to handle file formats.
  3. pandas to read CSV and JSON files.
  4. xml.etree.ElementTree to parse XML data.
  5. datetime to track the progress of each phase through logging.
  6. Install the pandas library .
  7. Set up paths for:
  8.log_file.txt to record the logs.
  9. transformed_data.csv to save the final output.

**Step 3: Define functions for each step of  ETL**
  1. Extract Data
  2. Transform Data
          The transformation process involves converting: 
          Heights from inches to meters. 
          Weights from pounds to kilograms. 
  3. Load Data
  4. Logging

**Step 4: ETL Execution**
The ETL process follows this sequence: 
1. **Extraction Phase:**
  The project extracts data from all CSV, JSON, and XML files located in the project directory.Each file type is processed, and the results are combined into one DataFrame.
2. **Transformation Phase:**
  The extracted data undergoes transformation to convert the measurements to standard units (e.g., height to meters, weight to kilograms).
3. **Loading Phase:**
  The transformed data is written into a CSV file, which can be imported into a database for further use.
4. **Logging:**
  The start and end of each phase (Extraction, Transformation, Loading) are logged to track progress and ensure everything runs smoothly.

## Conclusion:
  This project highlights the practical implementation of ETL processes using Python. The data extraction from multiple file formats, transformation of units, and loading of the final data into a structured CSV format demonstrate essential data engineering skills. Additionally, by logging each step of the process, you can monitor the progress and debug issues if they arise
