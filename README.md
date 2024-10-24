# Penguin Species Prediction App

## Overview

The Penguin Species Prediction App is a Streamlit application designed to predict the species of penguins based on their physical characteristics. This application utilizes machine learning algorithms, including Support Vector Machine (SVM), Logistic Regression, and Random Forest Classifier, to classify penguin species from the Penguin dataset.

## Features

- User-Friendly Interface: The app provides an intuitive sidebar for users to input physical measurements of penguins.
- Multiple Classifier Options: Users can select from different classifiers to observe how model choice affects predictions.
- Species Prediction: The app outputs the predicted species based on user inputs along with the model's accuracy.
- Interactive Input Sliders: Users can input measurements using sliders for an engaging experience.

## Technologies Used

- Python
- Streamlit
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   git clone https://github.com/AditDua/penguin_app.py.git

2. Navigate to the project directory:
   cd penguin-species-prediction-app

3. Create a virtual environment (optional but recommended):
   python -m venv venv

4. Activate the virtual environment:
   - On Windows: venv\Scripts\activate
   - On macOS/Linux: source venv/bin/activate

5. Install the required packages:
   pip install streamlit pandas numpy scikit-learn matplotlib seaborn

## Usage

1. Run the application:
   streamlit run penguin_app.py

2. Access the app: Open your web browser and go to http://localhost:8501 to view the app.

3. Input Measurements: Use the sliders to set values for bill length, bill depth, flipper length, and body mass. Select the penguin's gender and island.

4. Choose Classifier: Select the desired classifier from the dropdown menu.

5. Make a Prediction: Click the "Predict" button to see the predicted species and the accuracy score of the selected model.

## Dataset

The application uses the Penguin dataset, which contains information on three species:
- Adelie
- Chinstrap
- Gentoo

Ensure the dataset file penguin.csv is placed in the project directory.

## Contributing

If you would like to contribute to this project, feel free to fork the repository and submit a pull request. Any suggestions or improvements are welcome!

## License

This project is open-source and available under the MIT License.
