# Sewerage System Design & Hydraulic Modeling

**Author:** Aiman Afzal
**Course:** Water Supply and Wastewater Engineering (Institute of Environmental Engineering & Research, UET Lahore)

## 📌 Project Overview
This project involves the comprehensive design of a centralized sewerage system for **Muslim Nagar Housing Society, Lahore** (an 18-hectare residential area with 416 plots). The objective was to replace outdated septic tanks and informal drainage with a modern, 20-year design-life network that ensures public health and environmental safety.

The proposed system is a **partially combined sewerage network** featuring a gravity-driven network supplemented by a strategically located pumping station to overcome topographical challenges.

## 🛠️ Data & Tools
*   **Software:** Bentley SewerGEMS, Microsoft Excel, AutoCAD (for structural drawings)
*   **Design Criteria (PHED Standards):**
    *   **Sewage Generation:** 80% of water consumption.
    *   **Peak Factor:** 2.5 (applied to account for peak flows).
    *   **Minimum Self-Cleansing Velocity:** 2.5 ft/s (prevents sedimentation).
    *   **Maximum Velocity:** 10 ft/s (prevents pipe erosion).
    *   **Manning's Coefficient (n):** 0.013 (for RCC pipes).

## ⚙️ Methodology
1.  **Flow Calculation:** Estimated average daily sewage flow, added 10% for Infiltration & Inflow (I&I), and applied a peak factor to determine the design flow.
2.  **Hydraulic Design:** Used Manning's Equation to calculate pipe slopes and diameters (9" to 18" RCC pipes).
3.  **Software Simulation (SewerGEMS):** Modeled the network to verify the Hydraulic Grade Line (HGL), ensure gravity flow, and identify critical nodes. Sections with velocities < 2.5 ft/s were identified for periodic flushing.
4.  **Structural Analysis:** Conducted load analysis on pipes using Marston's Formula (Earth Loads) and AASHTO HS-20 (Traffic Loads) to ensure structural integrity.
5.  **Pumping Station Design:** Designed a wet well (210 ft³ capacity) and selected two centrifugal submersible pumps (9 HP; 1 duty, 1 standby) with a screening chamber.
6.  **Economic Analysis:** Performed a detailed capital and O&M cost estimation, including a per-household monthly billing calculation.

## 📊 Key Results
*   **Capital Cost:** PKR 5.62 Million (including 3% contingencies and 5% PRA charges).
*   **O&M Cost:** PKR 7.21 Million annually.
*   **Household Bill:** PKR 1,445/month (ensuring financial sustainability for the 350 constructed houses).
*   **Network Performance:** Successfully prevented surcharging across all 51 manholes during peak flow conditions.

---

## 🖼️ Visuals & Analysis

### 1. Study Area & Network Layout
**Project Area Map**
![Project Area Map](./project_area_map)

### 2. Hydraulic Profile & Structural Design
**Longitudinal Profile View (MH-20 to MH-34)**
*This profile demonstrates gravity flow, adequate pipe slope, and confirms the Hydraulic Grade Line (HGL) remains below the ground surface, preventing surcharging.*
![Sewer Profile View](./sewer_profile_view)

**Pumping Station Layout**
![Pumping Station Layout](./pumping_station_layout)

**Pumping Station Detailed Plan**
![Pumping Station Plan](./pumping_station_plan)

### 3. Economic Analysis
**Abstract of Capital Costs**
![Capital Cost Summary](./capital_cost_summary)

---

## 📁 Full Documentation & Data
The repository contains both the complete technical report and the detailed hydraulic spreadsheet. 

👉 **[Click here to view the complete Sewerage Design Report (PDF)](./Sewerage_System_Design_Report.pdf)**

👉 **[Click here to view the SewerGEMS Hydraulic Calculations (Excel)](./SewerGEMS_Hydraulic_Calculations.xlsx)**

### 📊 What is inside the Excel File?
The Excel spreadsheet is comprehensive and contains two major sections:
1.  **Manual Hydraulic Statement:** The complete step-by-step calculations using Manning's Equation, including pipe diameters, slopes, Qd/Qfull capacity checks, d/D depth ratios, and invert elevations for all manholes.
2.  **SewerGEMS Simulation Outputs:** The raw data exported directly from Bentley SewerGEMS, which includes:
    *   **Node Calculation Summary:** Confirms that the "Is Ever Overflowing?" status is `False` for all 51 manholes, proving the network can handle peak flows without surcharging.
    *   **Conduit Summary:** Detailed hydraulic grade lines (HGL), maximum velocities, and flow capacities (cfs) for every pipe segment.
    *   **Outfall Data:** Specific boundary conditions for the final discharge point.
