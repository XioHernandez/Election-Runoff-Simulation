# Election-Runoff-Simulation

## Overview

This Project analyzes California 
county-level election results and 
simulates final election outcome by 
reallocating votes from eliminated 
candidates to remaining candidates.

## Technologies used

- Google Sheets
- Pivot Tables
- VSLOOKUP
- CSV Data Processing
- Data Cleaning
- Data Modeling

## The following assumptions were applied:

| Eliminated Candidate | Reallocated To |
|---------------------|---------------|
| Chad Bianco | Steve Hilton |
| Tom Steyer | Xavier Becerra |
| Matt Mahan | Xavier Becerra |

These assumptions were created solely for
analytical purposes and do not represent 
the behaviors of actual voters. 

## Step 1: Collect and Clean Data
Percentages and party labels were removed from the dataset.

## Step 2: Imported Data into Google Sheets
The clean CSV data was imported into Google Sheets
![Description of screenshot](Screenshots/Screenshot%202026-09-14%20130621.png)

## Step 3: Vote Reallocation Mapping
A mapping table was created to reassign votes from 
eliminated candidates to the remaining candidates
![Description of screenshot](screenshots/form-overview.png)

## Step 4: Reallocation Using VLOOKUP
A VLOOKUP formula was created to automatically assign
each candidate to a final candidate according to the mapping table.

## Step 5: Pivot Tables
Pivot tables were used to summarize vote totals
![Description of screenshot](screenshots/form-overview.png)

## Step 6: Comparison
This simulation allowed me to compare:
- Original totals
- Simulated results
- Vote gains from reallocation
