![image](https://github.com/user-attachments/assets/ca9b9290-5dec-4977-b89f-eb0497192d99)# Capstone-project-SA2025
 Dynamic Pricing for Urban Parking Lots

**Capstone Project - Summer Analytics 2025**

## 1. Project Overview

This project delivers an intelligent, data-driven dynamic pricing engine designed to optimize the utilization of 14 urban parking spaces. In response to the inherent inefficiencies of static pricing (leading to overcrowding or underutilization), this system continuously adjusts parking prices based on real-time data reflecting demand, competitive pressure, and environmental conditions. The entire system is built with a focus on core data science principles, utilizing fundamental libraries, and is structured for conceptual real-time processing and visualization.

**Key Features:**
* **Simulated Real-time Data Processing:** Processes historical parking data as a continuous stream to mimic real-world dynamic environments.
* **Custom Dynamic Pricing Model:** Implements a transparent and interpretable pricing logic built exclusively using `numpy` and `pandas` from scratch.
* **Advanced Feature Engineering:** Extracts critical features such as `Occupancy Rate`, `Demand Proxy`, and `Nearby Competition Pressure` (derived from neighboring lot activity using Haversine distance).
* **Real-time Interactive Visualization:** Utilizes `Bokeh` to generate live, interactive line plots showcasing predicted prices and their relationship with key influencing factors over time.
* **Economic & Business Justification:** The pricing strategy is rooted in basic economic theory, with clear explanations of how price reacts to changes in demand and competition.

## 2. Tech Stack

This project strictly adheres to the specified technology constraints, emphasizing fundamental data science tools and custom implementations where higher-level libraries are restricted.

* **Programming Language:**
    * `Python`
* **Data Manipulation & Numerical Computing:**
    * `Pandas`: Essential for efficient data loading, cleaning, transformation, and complex feature engineering.
    * `NumPy`: Utilized for high-performance numerical operations and the core mathematical logic within the custom pricing model.
* **Real-time Data Stream (Conceptual Integration):**
    * `Pathway`: The project's architecture is designed for seamless integration with Pathway, a real-time data processing framework. While direct live streaming is simulated within the notebook, the design incorporates hooks for Pathway to feed continuous data into the pricing engine.
* **Interactive Visualization:**
    * `Bokeh`: Chosen for creating interactive and customizable web-based plots, enabling real-time visualization of pricing dynamics and their underlying drivers.
* **Development Environment:**
    * `Google Colab`: The entire codebase is developed and fully executable within Google Colab, ensuring accessibility and ease of replication.

## 3. Project Architecture Diagram

Below is a conceptual architecture diagram illustrating the data flow and component interactions within the dynamic parking pricing system.

![image](https://github.com/user-attachments/assets/0a00b0a7-0b40-4321-a42e-97dad3a90b92)


