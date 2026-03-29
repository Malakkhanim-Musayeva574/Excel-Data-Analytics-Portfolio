## DATA CLEANING AND TRANSFORMATION PROCESS
## Every great analysis starts with a foundation of clean data.When l first opened this Spofity dataset, l was faceed with a typical messy real-world senario:scientific notations hiding small values, inconsistent text casing, and dirty strings with hidden spaces. My mission was to transform this raw chaos into a structured, reliable narrative.
## Table Structuring : Converted raw data into an official Excel Table (Ctrl + T) and used Freeze Panes for better navigation and dynamic analysis.
## Text Standartization : Applied PROPER(),TRIM(),CLEAN() functions to unify text casing and remove hidden whitespaces, non-printable characters.
## Data Validation: Implemented drop-down lists for the Genre column to ensure data entry consistency and prevent future errors.
## Numeric Optimization : Converted scientific notations to standard numbers and unified all metrics(energy,danceability,etc.)to a 2 decimal precision.
## Feature Engineering: Created a new Full Key column by merging Key and Mode (e.g. C# Major) to add deeper musical context.
## Data Integrity: Performed a Deduplication sweep to remove redundant records and used find , replace to fix minor naming inconsistencies.
