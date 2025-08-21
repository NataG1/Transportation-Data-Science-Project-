## NYC Motor Vehicle Collisions Analysis
## Project Overview
This project analyzes motor vehicle collision data from New York City to identify patterns, contributing factors, and potential safety improvements. The analysis was conducted as part of the Explorer Transportation Data Science Project hosted by the Northeast Big Data Innovation Hub & National Student Data Corps, in collaboration with the U.S. Department of Transportation Federal Highway Administration.

## Project Goals
Identify patterns in motor vehicle collisions across NYC boroughs
Analyze contributing factors to crashes
Examine temporal trends in collision data
Conduct geospatial analysis of crash locations
Investigate gender differences in collision causes
Provide data-driven recommendations for improving road safety

## Dataset
The primary dataset used is the NYC OpenData Motor Vehicle Collisions - Crashes dataset, which contains detailed information about all police-reported motor vehicle collisions in NYC from 2012 to present. Each row represents a crash event with information about location, time, vehicles involved, contributing factors, and injuries/fatalities.

Source: NYC OpenData

## Methodology
The analysis follows six milestones:

Milestone 1: Data Preparation
Environment setup and library installation
Data loading and initial exploration
Basic statistical analysis

Milestone 2: Data Ethics, Pre-Processing, and Exploration
Ethical considerations in transportation data
Missing value analysis
Contributing factor analysis
Vehicle type analysis

Milestone 3: Time Series Analysis
Hourly crash patterns
COVID-19 impact assessment
Time series decomposition

Milestone 4: Geospatial Analysis
Borough-level crash distribution
Heatmap visualization of crash locations
Severity mapping with accessibility considerations

Milestone 5: Self-Guided Research
Investigation of gender differences in collision causes
Statistical analysis (chi-square tests, logistic regression)
Visualization of behavioral patterns

Milestone 6: Data Storytelling
Creation of virtual poster board
Presentation of key findings and recommendations
Policy implications discussion

## Key Findings
Temporal Patterns
Afternoon/evening hours (3-7 PM) show the highest crash rates
Significant decrease in crashes during COVID-19 lockdowns (March-April 2020)
Gradual recovery post-lockdown, but not to pre-pandemic levels

Geographic Distribution
Brooklyn has the highest number of crashes among NYC boroughs
Staten Island has the fewest crashes
High-concentration areas include Manhattan's urban core and major highway junctions

Contributing Factors
Top contributing factors: driver distraction, failure to yield, following too closely
Sedans, station wagons/SUVs, and passenger vehicles are most frequently involved

Gender Analysis
Males show higher likelihood of aggressive driving (2× odds ratio)
Males have moderately higher rates of DUI and speeding-related crashes
Females show slightly higher distraction-related crashes
Overall gender explains less than 1% of variance in collision causes

## Recommendations
For Policy Makers
Target high-risk behaviors, not demographic groups
Focus interventions on aggressive driving, DUI, and distraction
Implement behavior-based enforcement strategies

Time-specific interventions
Increase enforcement during high-risk hours (3-7 PM)
Implement targeted messaging during commute times

Location-based improvements
Address high-crash intersections with engineering solutions
Improve pedestrian infrastructure in high-risk areas
Data-driven education campaigns
Develop gender-tailored (but not gender-stereotyped) messaging
Focus on specific behaviors rather than broad demographic categories

For Data Collection
Standardize vehicle type categorization
Improve reporting consistency across boroughs
Enhance data on driver demographics and behaviors
Address underreporting in underserved communities

## Technologies Used
Python
Pandas
Matplotlib
Seaborn
Folium
Scikit-learn
Scipy
Google Colab

## Installation & Usage
Clone or download the project files
Open the Jupyter Notebook in Google Colab or local environment
Ensure all required packages are installed
Download the dataset from NYC OpenData
Update the file path in the notebook to point to your dataset
Run the cells sequentially to reproduce the analysis

## Acknowledgments
This project was completed as part of the Explorer Transportation Data Science Project hosted by:

Northeast Big Data Innovation Hub
National Student Data Corps
U.S. Department of Transportation Federal Highway Administration
Special thanks to the instructional team and mentors for guidance and support throughout the project.

## License
This project uses open data from NYC OpenData. Please review the terms of use for the dataset before using this analysis for other purposes.



