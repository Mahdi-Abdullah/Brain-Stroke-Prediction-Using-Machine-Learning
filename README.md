# Brain Stroke Prediction

This is a Python code for predicting brain stroke using various health parameters. The code takes input data in the form of a CSV file and trains a machine learning model on it. The model can then be used to predict the likelihood of an individual suffering from a brain stroke based on their health parameters.

## Requirements

This code requires the following Python packages to be installed:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Usage

To use this code, follow these steps:

1. Install the required Python packages using pip:

2. Prepare your input data in a CSV file. The file should contain columns for the following health parameters:
- age
- gender (0 for female, 1 for male)
- hypertension (1 if the patient has hypertension, 0 otherwise)
- heart_disease (1 if the patient has heart disease, 0 otherwise)
- ever_married (1 if the patient is married, 0 otherwise)
- work_type (0 for private job, 1 for self-employed, 2 for government job, 3 for children, 4 for never worked)
- Residence_type (0 for rural, 1 for urban)
- avg_glucose_level (average glucose level in blood)
- bmi (body mass index)
- smoking_status (0 for never smoked, 1 for formerly smoked, 2 for smokes)

3. Update the `file_path` variable in the code to point to your input CSV file.

4. Run the code: 
```
python stroke_prediction.py
```

The code will train the machine learning model and output the predicted stroke probability for each individual in the input data.

## Methodology

The code uses a Random Forest classifier from scikit-learn to predict the likelihood of an individual suffering from a brain stroke. The model is trained using input data containing various health parameters of individuals, as well as information on whether or not they have suffered from a stroke in the past.

## License

This code is released under the MIT license. See the LICENSE file for more information.

