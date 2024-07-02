# Bird Strike Data Visualization (2010-2011)

## Project Overview

This project focuses on visualizing bird strike data between 2010 and 2011. Bird strikes pose a significant threat to aircraft safety and understanding their patterns is crucial for developing preventive measures. The analysis is conducted using Python programming, with libraries such as Pandas, Seaborn, Numpy, and Matplotlib.

## Problem Statement

Transport and communication are crucial domains in the field of analytics. Environmental impacts and safety are major concerns of the scientific community, especially in the context of growing urban areas and increasing vehicular traffic. Bird strikes, defined as collisions between birds and aircraft, are a significant threat to aircraft safety. This project aims to visually depict the data on bird strikes collected by the FAA between 2010 and 2011 to better understand their patterns and impact on aviation safety.

## Objectives

* Analyze the frequency and patterns of bird strikes during different flight phases.
* Visualize the impact of bird strikes on aircraft safety.
* Identify the most common types of birds involved in strikes.
* Provide insights to help develop preventive measures for bird strikes.

## Data Source

The data used for this analysis is collected by the FAA and includes various attributes such as:
* Record ID                                  
* Aircraft: Type                          
* Airport: Name                             
* Altitude bin                              
* Aircraft: Make/Model                      
* Wildlife: Number struck                   
* Wildlife: Number Struck Actual            
* Effect: Impact to flight                 
* FlightDate                                
* Effect: Indicated Damage                  
* Aircraft: Number of engines?              
* Aircraft: Airline/Operator                
* Origin State                              
* When: Phase of flight                     
* Conditions: Precipitation                 
* Remains of wildlife collected?              
* Remains of wildlife sent to Smithsonian     
* Remarks                                    
* Wildlife: Size                            
* Conditions: Sky                           
* Wildlife: Species                          
* Pilot warned of birds or wildlife?       
* Cost: Total $                             
* Feet above ground                         
* Number of people injured                    
* Is Aircraft Large?                        


## Tools and Libraries

The following Python libraries were used for data analysis and visualization:

* **Pandas**: For data manipulation and analysis.
* **Seaborn**: For creating statistical visualizations.
* **Numpy**: For numerical operations.
* **Matplotlib**: For creating static, animated, and interactive visualizations.

## Methodology

1. **Data Cleaning and Preparation**:
   - Remove duplicates and irrelevant data.
   - Handle missing values.
   - Convert data types for analysis.

2. **Exploratory Data Analysis (EDA)**:
   - Summary statistics to understand the distribution of data.
   - Visualizations to identify trends and patterns.

3. **Data Visualization**:
   - Use Matplotlib and Seaborn to create visualizations.
   - Include key metrics such as the number of bird strikes, phase of flight, bird species, and damage severity.
   - Visualize temporal patterns and geographical distribution of bird strikes.
  
## Visualizations

The visualizations created in this project provide a comprehensive view of bird strike data:
  ● Yearly Analysis & Bird Strikes in the US
  ● Top 10 US Airlines in terms of having encountered bird strikes
  ● Airports with most incidents of bird strikes – Top 50
  ● Yearly Cost Incurred due to Bird Strikes:
  ● When do most bird strikes occur?
  ● Altitude of aeroplanes at the time of strike
  ● Phase of flight at the time of the strike.
  ● Average Altitude of the aeroplanes in different phases at the time of strike
  ● Effect of Bird Strikes & Impact on Flight
  ● Effect of Strike at Different Altitude
  ● Were Pilots Informed? & Prior Warning and Effect of Strike Relation
