Network-Intrusion-Analysis-UNSW-NB15
statistical analysis and machine learning classification of network traffic using R
Network Intrusion Detection Analysis

 Project Overview
This project analyzes the **UNSW-NB15** cybersecurity dataset to distinguish between normal and malicious network traffic. It was completed as a group assignment for the **Programming for Data Analysis** module at **APU**.

 My Individual Analysis (Nour Mohamed)
I was responsible for analyzing **Timing and Jitter** features to detect attack patterns.
**Variables:** Source/Destination Inter-Packet Times (`sinpkt`, `dinpkt`) and Jitter (`sjit`, `djit`).
**Methodology:** Performed data cleaning, missing value imputation using medians, and outlier detection.
**Machine Learning:** Implemented a **Random Forest** model (importance analysis) to rank features based on their predictive power.

 Tools Used
-Language: R
- Libraries: tidyverse, dplyr, ggplot2, randomForest
