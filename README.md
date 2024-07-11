# Physical Activity Tracker Landscape Report

## Description

### Overview
This repository hosts a comprehensive data science report that delves into the landscape of physical activity tracking, highlighting growth, challenges, and data insights. The report focuses on utilizing the advanced capabilities of the Colibri Wireless Inertial Measurement Unit (IMU) to explore human kinetics through an in-depth analysis of data collected from various physical activities.

### Data Collection
The study involved nine participants, each equipped with three Colibri wireless IMUs placed on the wrist, chest, and ankle. Additionally, a heart rate monitor (BM-CS5SR from BM Innovations GmbH) was used. Data were recorded at a frequency of 100Hz across 18 different physical activities, resulting in a rich dataset encapsulating 54 attributes per session. This dataset is presented in .dat files and provides a detailed view of human movement.

### Data Processing
The raw data underwent a meticulous cleaning process, including:
- Discarding transient activities and records with invalid orientation data.
- Normalizing sensor measurements with different frequency scales.
- Backward filling missing heart rate data due to frequency mismatches between IMUs and heart rate monitors.

### Analysis
The analysis covers multiple aspects:
1. **Exploratory Data Analysis (EDA):** Visualizations and statistical summaries of the dataset.
2. **Testing:** Statistical methods (ANOVA, Tukey HSD) to analyze the impact of different activities on heart rate and predicting MET (Metabolic Equivalent of Task) values.
3. **Modeling:** Linear regression models to predict MET based on heart rate and temperature at different body locations.
4. **Cluster Analysis:** KMeans clustering to reveal individual variability in physiological responses.

### Findings
Key findings include:
- A positive relationship between heart rate and MET, with negative relationships for hand and ankle temperatures.
- Significant differences in heart rates across various activities, with robust patterns observed for several subjects.
- Individual variability in physiological responses during activities, as shown by cluster analysis.

### Recommendations
To enhance the utility and sophistication of the physical activity tracking device, the following recommendations are made:
1. **Feature Enhancement:** Incorporate additional physiological features like oxygen saturation and respiratory rate.
2. **Individualized Monitoring:** Develop personalized training plans based on unique physiological responses.
3. **Real-time Feedback:** Integrate real-time feedback mechanisms to provide immediate insights to users.
4. **Continuous Monitoring:** Establish a framework for continuous updates and monitoring of the predictive model.

### Conclusion
This repository provides valuable insights into the potential of fitness data in driving innovation and product development. By leveraging the advanced sensor capabilities of the Colibri IMUs, this study offers a detailed exploration of human kinetics and paves the way for creating user-centric health and fitness solutions.

## Repository Contents
- **Scripts:** Python scripts for data cleaning, EDA, statistical analysis, and modeling.
- **Report:** Detailed report documenting the methodology, analysis, and findings.


---

