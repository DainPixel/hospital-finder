# 🏥 Hospital Finder: Personalized Medical Facility Recommendation  

This project is a **Python-based program** designed to help users find the most suitable hospital based on their medical needs and location.  

Developed as part of the **"Python and Data Analysis"** team project.  
The following table summarizes the contributions of each team member:

| Team Member      | Contribution |
|-----------------|----------------------------------------------------------|
| **[Dain Kim](https://github.com/DainPixel)**    | **Overall implementation**: data preprocessing, core logic, visualization, error handling |
| **Eujin Lee**   | Coordinate transformation research and application |
| Other Members   | Presentation materials, documentation |


## 📌 Background & Motivation  
- **COVID-19 impact**: Local hospitals faced reduced patient flow.  
- **Lack of awareness**: Patients does not know the right department, leading to increased medical costs and misdiagnoses.  

## 🎯 Project Objectives  
1. **Emergency Handling**: List nearby hospitals with emergency rooms.  
2. **Hospital Type Selection**: General hospitals, oriental medicine, rehabilitation centers, etc.  
3. **Department Selection**: Internal medicine, ENT, and other specialties.  
4. **Hospital Comparison**: Compare hospitals based on staff count, facility size, etc.  
5. **Data Visualization**: Graphically display hospital statistics.  
6. **Pharmacy Locator**: Find nearby pharmacies based on the chosen hospital.  

## 🔧 **Implementation & Features**  
- **Data Preprocessing**: Cleaning and organizing medical facility data.  
- **Functionality**: Emergency hospital lookup, comparison, visualization, and pharmacy search.  
- **Geolocation Handling**: `pyproj Transformer` converts user coordinates (latitude/longitude → x, y).  
- **User-Friendly UI**: Dynamic fonts/colors for different status messages.  
- **Error Handling**: Input validation & user-friendly prompts.  
- **Libraries Used**: `Pandas`, `NumPy`, `math`, `pyproj`, and more.  

## 📊 **Dataset**  
- **Source**: [Korea Local Government Open Data](https://www.localdata.go.kr)  
- **Hospital Data**: Information on general hospitals, dental clinics, and facilities with 30+ patient capacity.  
- **Pharmacy Data**: Addresses, contact details, and additional pharmacy-related information.  

## 🚀 **How to Run**  
1. Install dependencies:  
   ```bash
   pip install pandas numpy pyproj matplotlib
