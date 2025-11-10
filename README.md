```
# EV Charging Stations 2024 — Project  
**Author:** Shubhrat Chaursiya  
**Notebook:** [Colab Link](https://colab.research.google.com/drive/1clowTOHD2XPwD80Xpl0n3N0DkKtdJdnE?usp=sharing)  

## 📝 Project Overview  
This project uses the [Electric Vehicle Charging Stations 2024](https://www.kaggle.com/datasets/sahirmaharajj/electric-vehicle-charging-stations-2024) dataset from Kaggle to analyse and visualise EV charging infrastructure across India. The focus is on cleaning the data, performing exploratory data analysis (EDA), applying K-Means clustering for geographic segmentation, and creating interactive maps and nearest-station lookup utilities.

## 🎯 Objectives  
- Load and clean the dataset (remove duplicates, invalid coordinates, standardise column names)  
- Explore key features including geographic distribution (latitude & longitude), power ratings, connector types  
- Apply **K-Means clustering** to group charging stations into meaningful geographic clusters  
- Develop a **nearest-station finder** function using KDTree for real-time query capability  
- Create an interactive map (via Folium) showing station locations and cluster centres  
- Export processed data and map for further reporting or deployment  

## 📂 Project Structure  
```

│
├── EV_Charging_Stations_2024_Analysis.ipynb         # Jupyter/Colab notebook
├── electric_vehicle_charging_stations_2024.csv      # Raw dataset (to be downloaded separately)
├── EV_Charging_Stations_with_Clusters.csv           # Processed dataset after clustering
├── EV_Charging_Stations_Map.html                    # Interactive map output
└── README.md                                         # Project documentation

````

## 🛠️ How to Run  
1. **Download the dataset** from Kaggle:  
   https://www.kaggle.com/datasets/sahirmaharajj/electric-vehicle-charging-stations-2024  
2. Place `electric_vehicle_charging_stations_2024.csv` in the `Week1/` folder.  
3. Open the notebook (`EV_Charging_Stations_2024_Analysis.ipynb`) in Google Colab or Jupyter Notebook.  
4. Install required libraries if not already available:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn folium
````

5. Run all cells in order.
6. After execution you will get:

   * A cleaned & clustered dataset: `EV_Charging_Stations_with_Clusters.csv`
   * An interactive map: `EV_Charging_Stations_Map.html`
   * Console outputs with summary metrics and visualisation charts.

## 📊 Key Features & Visualisations

* Histogram plots of latitude, longitude distributions
* Scatter plot of station locations colour-coded by cluster
* Interactive map showing station markers and cluster centres
* Nearest station search function: `find_nearest_station(lat, lon, k)` for on-the-fly query

## 🔍 Improvements Made

* Standardised column naming and cleaned invalid coordinate entries
* Removed duplicates and filtered out extreme coordinate outliers
* Applied K-Means clustering to identify geographic segments for better planning
* Built a nearest-station lookup utility with `KDTree` for fast geographic queries
* Visualised results via Folium map and exported processed data for further analysis

## 📚 Future Enhancements

* Introduce additional features such as charger pricing (₹/kWh), station usage stats (kWh/day)
* Integrate advanced ML models to predict demand or optimal station placement
* Build a web/desktop UI (e.g., Streamlit app) for user-interactive queries and visualisations
* Include temporal data (if available) to analyse growth trends in charging infrastructure

## 📄 License & Acknowledgements

Dataset provided by Kaggle user Sahir Maharaj. Please refer to the original dataset page for usage conditions.
This project is for educational purposes and part of the Shell-Edunet internship.

---

## 📫 Connect with Me

<p align="left">
  <a href="https://www.linkedin.com/in/shubhrat-chaursiya-819672354/" target="_blank">
    <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" width="28" height="28" alt="LinkedIn" />
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/shubhratchaursiya" target="_blank">
    <img src="https://cdn-icons-png.flaticon.com/512/733/733553.png" width="28" height="28" alt="GitHub" />
  </a>
  &nbsp;&nbsp;
  <a href="mailto:shubhratchuarsiya2005@gmail.com">
    <img src="https://cdn-icons-png.flaticon.com/512/732/732200.png" width="28" height="28" alt="Email" />
  </a>
</p>

---
