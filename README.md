# Vaccines
"Analyzing Differential Adverse Reactions among Covishield, Covaxin and Sputnik V Recipients: Insights from Machine Learning and Epidemiological Analysis"

# Vaccine Adverse Reaction Checker

This project provides a simple and direct way for users to check the potential adverse reactions they might experience based on their **age**, **gender** and **vaccine type**. It uses a basic machine learning model trained on a CSV dataset to make predictions.

##  Project Description

The idea behind this project is to help individuals get a quick overview of possible side effects from different vaccines. It does this by using a trained model on sample data. 

##  How It Works

1. User enters:
   - Age
   - Gender
   - Vaccine Type (Covishield, Covaxin, etc.)
2. These inputs are fed into a pre-trained ML model.
3. The model returns a likely adverse reaction (e.g., Fever, Headache, None, etc.)
4. The result is displayed on a simple output page.

##  Project Structure

Vaccines/
│
├── dataset/
│   └── Vaccine_Adverse_Reactions.csv    # Sample dataset used to train the model
│
├── model/
│   └── vaccine_model.pkl                # Trained machine learning model 
│
├── app.py                              
└── README.md                            # This file

##  Technologies Used

- Python
- Pandas
- Scikit-learn
- Pickle (for saving the ML model)

##  How to Run

1. Clone this repository:

   git clone https://github.com/Architaa16/Vaccines.git
   
   cd Vaccines

3. Install the required packages:

   pip install -r requirements.txt


4. Run the Flask app:

   python app.py


5. Open your browser and go to:

    http://127.0.0.1:5000/

