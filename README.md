# Los Angeles Crime Data Analysis

## Overview
Welcome to the Los Angeles Crime Data Analysis project! 🌟

Los Angeles, California – the City of Angels and the Entertainment Capital of the World. Known for its beautiful weather, palm trees, sprawling coastline, and the glitz and glamour of Hollywood, LA is also a city that faces significant challenges with crime. The Los Angeles Police Department (LAPD) has enlisted our help to analyze crime data in order to uncover patterns and trends. This analysis aims to provide actionable insights that can assist the LAPD in more effectively allocating resources to combat crime across the city.

## Dataset
- The dataset used for this project is a modified version of the data available from Los Angeles Open Data. It includes various attributes about crime incidents reported in Los Angeles.
- **Provided By**: DataCamp

## Project Goals
The primary goal of this project is to analyze the provided crime data to identify patterns in criminal activity. By understanding these patterns, we can provide insights that help in the effective allocation of law enforcement resources to reduce crime in Los Angeles.

## Tools and Libraries
This project utilizes several Python libraries to analyze and visualize the crime data:
- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical operations.
- **matplotlib** and **seaborn**: For creating visualizations that help interpret the data.

## Key Analyses
### Identifying Peak Crime Hours
We analyze the crime data to determine which hours of the day have the highest crime frequency. Understanding peak crime hours helps in planning effective policing strategies during those times.

### Night Crimes by Area
The analysis identifies areas with the highest frequency of night crimes, defined as crimes occurring between 10 PM and 4 AM. This helps in focusing nighttime patrols in areas with higher crime rates during these hours.

### Crime Victim Age Distribution
We categorize crime victims into different age groups to understand which demographics are most affected by crime. This insight helps in tailoring crime prevention strategies for specific age groups.

## Data Description
The dataset used for this analysis is a modified version of the crime data publicly available from Los Angeles Open Data. It includes various attributes about crime incidents reported in Los Angeles, such as the date and time of occurrence, location, type of crime, and details about the victims and suspects.

### Main Columns
- **Date Reported**: The date on which the crime was reported.
- **Date of Occurrence**: The date when the crime actually occurred.
- **Time of Occurrence**: The time when the crime occurred, in 24-hour format.
- **Area Name**: The geographic area or patrol division where the crime was reported.
- **Crime Description**: A brief description of the type of crime committed.
- **Victim Details**: Information about the victim, including age, sex, and descent.
- **Location**: The street address where the crime occurred.

## Usage
To explore and analyze the crime data yourself, follow these steps:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/youssefraafat/la-crime-analysis.git
    ```

2. **Navigate to the Project Directory**:
    ```bash
    cd la-crime-analysis
    ```

3. **Run the Jupyter Notebook**:
    ```bash
    jupyter notebook crime_analysis.ipynb
    ```

4. **Explore the Analysis**:
    Open the `crime_analysis.ipynb` notebook to view detailed analysis and visualizations of the crime data.


## Acknowledgements
- Data sourced from [Los Angeles Open Data](https://data.lacity.org/).
- Special thanks to the LAPD for providing the crime data and for their ongoing efforts to keep Los Angeles safe.

---
