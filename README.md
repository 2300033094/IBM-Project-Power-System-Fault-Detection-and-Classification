**Power System Fault Detection and Classification**


This project implements a machine learning solution for automatic detection and classification of faults in power distribution systems using electrical measurement data (such as voltage, current, and associated features). The workflow leverages IBM Cloud Lite services, with the aim of supporting rapid and reliable grid stability.

Project Structure
 IBM Project.pdf                   -> Detailed project report/documentation
 IBM Project.pptx                  -> Project presentation slides
 Power System Fault Detection.ipynb -> Main Jupyter notebook for data analysis, modeling, and evaluation
 fault_data.csv                    -> Source dataset used for training and evaluation
 Problem Statement
Rapid and accurate identification of power system faults (such as line breakage, transformer failure, and overheating) is critical to maintain grid reliability. This project uses machine learning to detect and classify such faults based on electrical and environmental data.

Solution Overview
Data Preprocessing: Feature scaling, encoding categorical columns, and handling missing values.

Modeling: Training supervised machine learning models (Random Forest, SVM) for fault classification.

Evaluation: Assessing model performance via accuracy, confusion matrix, and classification report.

Deployment (Planned): Saving and preparing models for deployment via IBM Watson Machine Learning.

Key Technologies
IBM Cloud Lite

IBM Cloud Object Storage

IBM Watson Studio

Python: pandas, scikit-learn, matplotlib, seaborn

How to Use
Data

fault_data.csv is the main dataset. Inspect it to understand feature columns and fault classes.

Analysis & Modeling

Open and run Power System Fault Detection.ipynb in IBM Watson Studio or locally (with Juypter).

All data exploration, preprocessing, training, and evaluation steps are documented in the notebook.

Documentation & Presentation

For technical details, refer to IBM Project.pdf.

For project overview, refer to IBM Project.pptx.

Deployment

Trained models are saved and ready for deployment as a REST API via IBM Watson Machine Learning (see notebook for export code).

Results (Summary)
SVM and Random Forest models were trained.

Best achieved accuracy (example): SVM ~45%, Random Forest ~39%.

'Overheating' fault was most accurately classified; confusion remained between some similar fault types.

Future Work
Advanced algorithms and hyperparameter optimization

Real-time deployment with live data feeds

Feature enrichment and model explainability

Project Repository
GitHub: https://github.com/2300033094/IBM-Project-Power-System-Fault-Detection-and-Classification.git
Dataset: https://www.kaggle.com/datasets/ziya07/power-system-faults-dataset

License
This project is licensed under the MIT License — see the LICENSE file for details.

Author
Chebrolu Chaithanya Kumar (2300033094)
