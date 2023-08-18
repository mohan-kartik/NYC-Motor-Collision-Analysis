# NYC Motor Collision Analysis

## Overview:
New York City is a sprawling metropolis comprising five boroughs and houses approximately 8.2 million individuals.

Given its dense population and bustling traffic, it's unsurprising that the city sees a significant number of accidents every year, each with its unique circumstances. Committed to fostering transparency and public engagement, the NYPD compiles data for every accident, making it accessible to the public via nycopendata.socrata.com.

## Dataset:
This comprehensive crash data analysis aims to unearth underlying patterns or correlations that could provide insights into the prevalent collision rates. The dataset spans from 2012 to 2019 and contains close to 1.6M+ observations.

* Accident Data: Comprehensive records capturing the specifics of each incident.
* Accident Time: Timestamps that help gauge peak accident intervals and chronological trends.
* Borough and Zip Code: These offer insights into which areas and neighborhoods are particularly accident-prone.
* Contributing Factor Vehicle: Key reasons leading to the accidents.
* Off Street Name & On Street Name: Detailed locational data to determine exact sites of collisions.
* Longitudes & Latitude: Geographic coordinates to map out accident hotspots visually.
* Number of People Killed and Injured: Breakdown by category, including cyclists, motorcyclists, vehicle occupants, and pedestrians.

## Tasks:
* The data was extracted from "nycopendata.com" using Open Data API (OData API) and performed Data Connection with Tableau.
* The data was cleaned using Python and stored in Google Cloud Storage as a Bucket to create a virtual instance.
* I performed analysis using Google's Big Query in Google Cloud Platform and stored the query results in CSV files.

## Analysis:

A) Regional Analysis
![image](https://github.com/mohan-kartik/NYC-Motor-Collision-Analysis/assets/42971268/78acee17-04f5-4910-860f-34a85ae9bb95)

B) Time Series Analysis
![image](https://github.com/mohan-kartik/NYC-Motor-Collision-Analysis/assets/42971268/adbafbb0-4e86-4805-a38a-bd4ce3b3a3fb)

C) Top Vehicle Type involved in Accident
![image](https://github.com/mohan-kartik/NYC-Motor-Collision-Analysis/assets/42971268/27ad63a0-c4b1-46e0-8ac8-23cf38bcd866)


## Insights:
* Peak injury time: 4 pm - 6 pm.
* Injuries peaked in 2018 with 67K+ cases, but reduced to 53K+ cases by 2019.
* July and August are the month with the most number of injuries.￼
* The Main cause of accidents was "Driver inattention / Distraction." 
* Passenger vehicles, station wagons, and sport utility vehicles are the top vehicle categories involved in accidents.  
* Top accident-prone areas: 11236, 11207, 11234.
* BROOKLYN and QUEENS reported the highest fatalities in NYC.

## Recommendations:
* Deploy more Traffic Officers from 4 pm - 6 pm on high-accident days.
* Boost ambulance availability from 1 pm - 5 pm in high-risk zones.
* Prioritize safety projects in high-risk zones: 11236, 11207, 11234.
* Focus on safety measures in BROOKLYN and QUEENS due to high fatalities.
* Intensify driver re-training and enforce stricter penalties for habitual offenders.
* Improve and promote the public transit system to encourage commuter use to minimize accidents.
