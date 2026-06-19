
Script_To_Generate_High_Resolution_Map_Using_Excel_Data_Source

Overview

This repository provides a Python script for generating high-resolution global distribution maps of germplasm accessions using geographic coordinate data stored in an Excel file. The script is designed to run in Google Colab and produces publication-quality maps in both PNG and PDF formats.

Features
• Reads accession coordinate data directly from an Excel workbook.
• Automatically validates and filters latitude and longitude values.
• Generates a global map using the Robinson projection.
• Colors accession points by collecting institute (INSTCODE).
• Creates publication-quality outputs suitable for reports, presentations, and scientific publications.
• Exports maps as high-resolution PNG and vector PDF.
• Runs entirely in Google Colab with minimal setup.

Input Data Requirements
Required columns:
- DECLATITUDE: Latitude coordinate in decimal degrees
- DECLONGITUDE: Longitude coordinate in decimal degrees
- INSTCODE: Institute code used for color grouping

Generated Outputs
- accession_map_by_INSTCODE.png
- accession_map_by_INSTCODE.pdf

Google Colab Usage
1. Open Google Colab.
2. Copy and run the script.
3. Upload the Excel file when prompted.
4. The script generates and downloads the PNG and PDF outputs.

Required Libraries
- pandas
- matplotlib
- cartopy
- openpyxl

Applications
- Genebank collection mapping
- Germplasm distribution analysis
- Collection gap assessment
- Collection site visualization
- Research reports and presentations

Citation
Sime, Y. (2026).
Script_To_Generate_High_Resolution_Map_Using_Excel_Data_Source.
GitHub Repository.

License
MIT License

Author
Yonas Sime

Data Management and Germplasm Information Specialist

