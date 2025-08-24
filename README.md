Predictive Optimization System (POS) for Green Logistics

Welcome to the Predictive Optimization System (POS), a groundbreaking project aimed at mitigating the environmental impact of the logistics sector through the innovative application of AI and Optimization technology.

📄 Abstract

Climate change is a pressing global challenge, with the transportation sector being a significant source of carbon dioxide (CO_2) emissions. This project introduces a comprehensive methodology that integrates data collected from Portable Emissions Measurement Systems (PEMS) with Machine Learning (ML) technology. The core objective is to make emission reduction a primary goal in transportation operations, moving beyond traditional methods that solely focus on time and cost.

Our system consists of two key stages: first, developing a machine learning model based on the Gradient Boosting algorithm to accurately predict emissions under real driving conditions (RDE), and second, integrating this predictive model into a multi-objective optimization framework solved by the NSGA-II algorithm.

💡 Problem and Solution

The Problem: Current logistics models often prioritize time and cost, neglecting environmental factors. This leads to inefficient routes from an emissions standpoint.

The Solution: We have developed a system to:

Predict Emissions: Accurately forecast vehicle emissions based on operational factors.

Optimize Routes: Identify the most efficient routes that balance emission reduction and travel time.

⚙️ Methodology

The project was executed through the following structured process:

Data Collection and Preprocessing: Utilizing reliable data from sources such as the European Commission's Joint Research Centre (JRC). The data undergoes preprocessing with techniques like the Extended Kalman Filter for cleaning and normalization.

Emission Prediction Model: We developed an ML model using a Gradient Boosting Machine (GBM) (like XGBoost) to predict emissions with high accuracy.

Multi-Objective Optimization: The predictive model is integrated with the NSGA-II algorithm to find optimal routes that consider both environmental and temporal objectives.

📊 Results and Impact

The POS system has the potential for significant impact:

Environmental: Contribute to a substantial reduction in carbon emissions and other pollutants from vehicles.

Economic: Help logistics businesses optimize operational costs and increase efficiency.

Social: Support sustainable development goals and foster a greener transportation industry.

📁 Repository Structure

├── docs/                     https://github.com/tamnghijz1/Predictive-Optimization-System-POS-/blob/366fd0738fed4ec47407b12e50fe7888a9bcd76c/APPLYING%20GREEN%20AI%20TECHNOLOGY%20TO%20LOGISTICS%20TO%20OPTIMIZE%20TRANSPORTATION%20THROUGH%20MONITORING%20AND%20COLLECTING%20DATA%20ON%20CARBON%20EMISSIONS.pdf

├── src/                        https://github.com/tamnghijz1/Predictive-Optimization-System-POS-/blob/main/POS.ipynb

├── data/                       https://github.com/tamnghijz1/Predictive-Optimization-System-POS-/blob/main/Data_PV_fleet_2021_EU_PYCSIS.csv

🤝 Development Team

Team Name: Green Warrilogs

Members: Trần Tam Nghi, Tô Quỳnh Anh, Lê Quốc Bảo, Thạch Thảo Vy

Leader's number: 0968360606

Email: tttamnghi@gmail.com

This project was developed for the FIATA VLA Logistics Innovation competition.
