# REDCap Data Import Script

This repository contains a script for systematically and accurately mapping and transferring data from source files into a REDCap project template.

## Features
- Combines data from multiple source files based on unique identifiers.
- Uses a mapping dictionary to transfer data from source columns to target columns.
- Supports multiple entries for a single record using REDCap's repeat instrument functionality.
- Ensures data integrity and transparency with logging and validation.

## Usage
1. Place your source files (`UHNDataSection.xlsx` and `GXTestDataSection.xlsx`) in the same directory as the script.
2. Run the script with a dynamically provided start ID.
3. Review the generated `Updated_Import_CPET.xlsx` for accuracy before importing into REDCap.

## Requirements
- Python 3.x
- pandas
- redcap

## License
This project is licensed under the MIT License.
