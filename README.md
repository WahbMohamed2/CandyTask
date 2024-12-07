# Location Data Cleaning Project

This project provides a script to clean and standardize location data, handling inconsistencies such as misspellings, unwanted characters, and missing values. The cleaned data ensures uniformity, making it ready for further analysis.

## Features

- Handles common misspellings and incorrect formats (e.g., "califormia" → "California").
- Converts all entries to lowercase and removes unnecessary whitespace.
- Replaces abbreviations with full names (e.g., "ny" → "New York").
- Removes invalid or irrelevant data entries (e.g., "sub earth", "ur mom").
- Standardizes "City, State" formats for better clarity.

## Usage

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_name>
