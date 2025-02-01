# Cricket-Match-Data-Analysis

This project demonstrates the process of transforming raw cricket related JSON data into structured dimension and transactional tables using Snowflake. The focus is on extracting relevant details related to players, teams, matches, and innings to populate the following tables:

Data Source: https://cricsheet.org/downloads/


Technologies Used:
-> Snowflake (Data Warehousing & Processing)
-> SQL (Data Transformation)
-> JSON Handling (Parsing & Structuring Data)

This project follows the ETL (Extract, Transform, Load) process to clean, transform, and load the data into Snowflake's structured tables.

Processed Data Includes:
DimPlayer : Player details
DimTeam : Team information
DimVenue : Venue details
Match_Details : Match-level data
Innings_Details : Ball-by-ball or innings-level information

Note: In order to reduce the credit used in Snowflake, only one JSON file is used. Feel free to increase the number of JSON input files as needed for your specific use case.

