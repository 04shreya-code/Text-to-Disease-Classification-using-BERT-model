# Disease Prediction from Symptom Descriptions

## Overview
This project involves developing a language model to accurately predict diseases based on short descriptions of symptoms. The dataset consists of 1200 datapoints with two columns: "label" and "text". The "label" column contains disease labels, while the "text" column contains natural language symptom descriptions. The dataset covers 24 different diseases, with each disease having 50 symptom descriptions.

## Dataset
The dataset includes the following diseases:
1. Psoriasis
2. Varicose Veins
3. Typhoid
4. Chicken pox
5. Impetigo
6. Dengue
7. Fungal infection
8. Common Cold
9. Pneumonia
10. Dimorphic Hemorrhoids
11. Arthritis
12. Acne
13. Bronchial Asthma
14. Hypertension
15. Migraine
16. Cervical spondylosis
17. Jaundice
18. Malaria
19. Urinary tract infection
20. Allergy
21. Gastroesophageal reflux disease
22. Drug reaction
23. Peptic ulcer disease
24. Diabetes

Each disease has 50 symptom descriptions, resulting in a total of 1200 datapoints.

## Task
The primary task is to develop a machine learning model capable of predicting the disease given a short description of the symptoms faced by the user. Such models can help in identifying potential diseases early, allowing patients to seek timely medical attention. This can be especially useful for remote diagnosis and treatment recommendations when in-person consultations are not possible or desirable.

## Project Structure
- `data/`: Contains the dataset files.
- `notebooks/`: Jupyter notebooks for exploratory data analysis and model development.
- `src/`: Source code for data preprocessing, model training, and evaluation.
- `models/`: Saved models and checkpoints.
- `results/`: Evaluation results and metrics.


