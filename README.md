# Enhancing Electric Vehicle Charging Infrastructure  
### A Network Analysis Based on Real-Time Usage and Geographical Data  
 The goal is to optimize the charging station infrastructure to improve user experience and expand the network's reach and efficiency.
- Demo: https://www.youtube.com/watch?v=QRC4-sDGa2Y
## Project Files
- `ElectricVehicleChargingStationUsageJuly2011Dec2020_2797601698338421488.csv` — Raw dataset (uncleaned)  
- `clean_electric_vehicle_dataset.csv` — Preprocessed and cleaned dataset  
- `Tableau_sourcecode` — Dashboard for data visualization  
- `SourceCode.ipynb` — Python notebook for Exploratory Data Analysis (EDA) and network analysis
- `Group6_DV_finalprojectreport.pdf` - read report 
## Timeframe
Data collected from **Data year is from 2011 to 2013**

## Dataset Description
This dataset, sourced from the **City of Palo Alto**, captures over nine years of electric vehicle charging activity and interaction. It is central to our network-based analysis aiming to enhance infrastructure planning and identify key usage patterns.

### Key Features Analyzed
- **Start Date & End Date**  
  Reveal peak station usage periods, daily cycles, and seasonal trends  

- **Total Duration**  
  Average charging duration — reflects user habits and station efficiency  

- **Energy (kWh)**  
  Power consumed per session — useful for profiling equipment performance  

- **GHG Savings (kg)** & **Gasoline Savings (gallons)**  
  Measure the environmental impact — vital for sustainability metrics  

- **Port Type & Plug Type**  
  Capture user preferences and detect compatibility gaps  

- **EVSE ID & Address**  
  Essential for geospatial mapping and identifying high-demand or underserved areas  

- **Fee**  
  Charging session cost — helps analyze spending behavior and pricing models  

- **Ended By**  
  Indicates how charging sessions were terminated — informs on user and station behavior  

- **User ID**  
  Allows segmentation between frequent and occasional users  

## Objectives
- Perform **real-time usage analysis** to uncover behavioral and temporal patterns  
- Apply **network analysis** to map high-density charging clusters and underutilized stations  
- Use **geographical visualizations** to highlight regional trends and infrastructure gaps  
- Quantify **environmental and financial metrics** for sustainability evaluation  

## Tools & Technologies
- Python (Pandas, NetworkX, Matplotlib, Seaborn)
- Tableau
- Latex
- Jupyter Notebook
- GitHub for version control and collaboration  
- NetworkX: For constructing and analyzing complex networks of EV station usage patterns.
- Tableau: For creating interactive visualizations that provide insights into user distribution and behavior.
- Python: Used for data preprocessing, analysis, and visualization with libraries such as Pandas and Matplotlib.
---
 _This project aims to inform city planners, EV manufacturers, and sustainability advocates about electric vehicle usage patterns, to optimize and expand EV charging infrastructure based on real-world data._
