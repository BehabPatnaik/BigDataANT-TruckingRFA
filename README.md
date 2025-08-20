# BigDataANT-TruckingRFA
This is a comprehensive big data analytics project focused on trucking fleet risk factor analysis. The project analyzes trucking data to identify risk factors and patterns in fleet operations, providing insights for safety management and operational optimization.

## Project Structure
### Data Sources
Trucks Dataset (trucks.csv): Contains detailed monthly fuel consumption and mileage data for 100 trucks (A1-A100) over multiple years (2009-2013)
Driver and truck IDs
Truck models (Freightliner, Ford, Kenworth, Hino, Caterpillar, Navistar, Volvo, Peterbilt, Oshkosh, Crane, Western Star)
Monthly miles driven and gas consumption for each truck

## Geolocation Dataset (geolocation.csv): Real-time GPS tracking data with 8,002 records
Truck and driver identification
GPS coordinates (latitude/longitude)
Location data (city, state)
Event types (normal, overspeed, unsafe following distance, lane departure)
Velocity and idling indicators
Event indicators for risk assessment
Complete Dataset (Complete Dataset.csv): Consolidated dataset (309MB) combining all data sources (Using BigData tools Hadoop and Hive)

### Data Processing
Data Manipulation Script (Data Manupulator.ipynb): Python notebook for data preprocessing
Uses pandas and numpy for data manipulation
Creates sampled datasets for analysis
Handles large dataset processing efficiently

### Visualization & Analysis
Tableau Dashboards: Multiple interactive dashboards for data visualization
Risk factor analysis with configurable thresholds (default: 7.0)
Geographic mapping of truck locations and events
Performance metrics and trend analysis
Safety event monitoring and reporting

## Key Features
Risk Factor Analysis: Implements a risk scoring system to identify high-risk drivers and vehicles
Geographic Visualization: Maps truck locations and safety events across California
Performance Monitoring: Tracks fuel efficiency, mileage, and operational patterns
Safety Event Detection: Identifies overspeed, unsafe following distance, and lane departure events
Real-time Monitoring: GPS-based tracking with velocity and idling detection
