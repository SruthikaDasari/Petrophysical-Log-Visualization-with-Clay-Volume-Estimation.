# Petrophysical-Log-Visualization-with-Clay-Volume-Estimation.

##  Project Overview
This project focuses on the **visualization of well log measurements** using Python.  
The main objective is to generate **multi-track well log plots** of key logs such as:

- Gamma Ray (GR)  
- Neutron Porosity (NPHI)  
- Bulk Density (RHOB)  
- Sonic Transit Time (DT)  

Additionally, the project includes:
- A **Volume of Shale (Vshale)** computation module, which is essential for petrophysical evaluation.  
- An **interactive feature** to obtain Vshale values at selected depths.  

---

##  Tools & Libraries
- **NumPy** → Numerical computations  
- **Pandas** → Data handling and preprocessing  
- **Matplotlib** → Visualization and plotting  

---

##  Dataset: `WellDatafile.csv`
The dataset contains well log information. Each row corresponds to a **specific depth** in the well, and columns represent different log measurements.

### Key Columns:
- **DEPTH** → Depth measurement (feet or meters)  
- **GR** → Gamma Ray log (for lithology & shale volume estimation)  
- **NPHI** → Neutron Porosity log (porosity estimation)  
- **RHOB** → Bulk Density log (another porosity indicator)  
- **DT** → Sonic Transit Time (used for porosity & rock property evaluation)  

