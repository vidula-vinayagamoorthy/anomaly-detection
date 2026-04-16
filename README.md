🎬Anomaly Detection - Summary
---
This project explores different approaches to detecting anomalous activity within a ship’s engine dataset. The work focuses on applying statistical and machine learning techniques, analysing how their results differ, and understanding the trade‑offs between interpretability, visualisation, and model output. 

✨ Technologies
---
Python (google colab) - numpy, pandas, seaborn, matlplotlib, sklearn

🚀 Approach
---
- Exploratory data analysis (EDA) of engine sensor data - checking for missing, duplicates, distribution.
- Application of three anomaly detection techniques on the same dataset, with data standardised where required.
  -  Interquartile Range (IQR),
  -  One‑Class Support Vector Machine (One‑Class SVM)
  -  Isolation Forest
- Principal Component Analysis (PCA) was used for visualisation
- Comparisons made between the techniques results

<img width="699" height="304" alt="image" src="https://github.com/user-attachments/assets/c2ad23dc-1285-40db-8771-5a880d3a4aa5" />


🚦 Running the Project
---
ipynb file can be run directly on google colab

🎞️ Preview of the output 
--- 
Report attached has
- Tables summarising anomalies by technique
- PCA visualisations of anomalous data points

Visualisation is used to support interpretation and highlight limitations.

IQR and One‑Class SVM offer practical and complementary approaches, with IQR providing stronger interpretability. Isolation Forest shows the importance of validating model outputs and visualisation, rather than relying on them in isolation.

🔭 Why this project? 
--- 
This project was undertaken to gain hands‑on experience with data science and machine learning techniques, with a focus on understanding model/measures behaviour, assumptions, and limitations in practice. The work supports a broader objective of strengthening practical understanding of ML and AI concepts that are increasingly relevant in technology risk, governance, and assurance contexts.

:tada:
