🛡️ Injury Prediction Model for Industrial Safety

This repository contains a predictive machine learning model designed to prevent workplace injuries using historical data. It leverages factory records on shift timings, incident types, departments, and body parts affected, helping occupational health teams proactively plan safety interventions.


---

📊 Objective

To build an AI model that predicts:

The most probable body part to be injured

The most vulnerable department

The likely month of injury occurrence



---

🧠 Technologies Used

Python

Pandas & NumPy

Scikit-learn

Google Colab (for development)

Matplotlib & Seaborn (for visualization)

RandomForestClassifier (primary model)



---

📁 Dataset Features

Simulated dataset with 3 years of realistic factory injury data including:

Date

Shift

Incident Type

Type of Injury

Department (Encrypted)

Body Part



---

🛠️ Workflow

1. Data Cleaning & Preprocessing


2. Feature Engineering (Month extraction, label encoding, etc.)


3. Train-Test Split (80:20)


4. Model Training using Random Forest


5. Evaluation using accuracy and classification report


6. Predictions on:

Department at high risk

Body part likely to be injured

Risk month





---

📈 Output

Trained AI model (can be reused on new datasets)

Insightful visualizations on injury patterns

Accuracy metrics of predictive performance


neural network is also created to check the difference in outcome between machine learning model and neural network model.
---

🚀 How to Run

1. Open Injury prediction model.ipynb in Google Colab


2. Upload your factory injury dataset or use the simulated data


3. Run all cells step-by-step


4. View predictions and save the trained model




---

🔐 Data Privacy

Departments are encrypted for confidentiality

No patient-identifiable data is used



---

📌 Use Case

Ideal for:

Factory safety officers

Occupational health doctors

Industrial engineers



---

📜 License

This project is licensed under the MIT License.
You are free to use, modify, and distribute this software for any purpose, with or without attribution.

MIT License

Copyright (c) 2025 Aby Alex

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


---

👤 Author

Dr. Aby Alex
Occupational Health & AI in Healthcare Enthusiast
Currently building AI models to improve industrial safety outcomes
