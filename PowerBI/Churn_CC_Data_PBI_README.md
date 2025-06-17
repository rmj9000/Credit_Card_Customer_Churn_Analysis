# Churn_CC_Data_PBI - PowerBI File ReadMe

## Instructions for use of the PowerBI file with the data in this project

There were issues with sharing the PowerBI file with the visualisations created for the project. 

The issue is that it requires the absolute path for the data used ( BankChurners_cleaned.csv ) which is in the \data\inputs\cleaned folder in the GitHub repository.

Attempts have been made to use a relative path, placing the data file in the same folder as the PowerBI file and trying to set a parameter to the relative path and pointing to the file.

## Step-by-Step: Create a Portable Power BI Package with the CSV file

Use a Relative Path to the CSV in Power Query Instead of hardcoding the Absolute Pathname.

In Power BI Desktop, go to Home > Transform Data > Advanced Editor.

With the CSV file (or a copy) in the same folder as the PowerBI file, replace the CSV file path with:

let

    Source = Csv.Document(File.Contents("BankChurners_cleaned.csv"),[Delimiter=",", Columns=26, Encoding=1252, QuoteStyle=QuoteStyle.None])

in

    Source

If this does not work, insert the Absolute Path within the speech marks, remembering the \ before BankChurners_cleaned.csv

eg. 

    Source = Csv.Document(File.Contents("D:\data\BankChurners_cleaned.csv"),[Delimiter=",", Columns=26, Encoding=1252, QuoteStyle=QuoteStyle.None])


## PowerBI Version Information

The version of PoowerBI used was the free desktop edition released June 2025, version: 2.144.679.0 64-bit (June 2025)