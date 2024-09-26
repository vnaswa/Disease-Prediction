Here’s an expanded version of the GitHub project description:

---

# Disease Prediction Using Machine Learning

This project is a **Disease Prediction System** that uses machine learning algorithms to diagnose diseases based on symptoms provided by the user. It is designed to predict possible diseases using three different models: **Decision Tree**, **Random Forest**, and **Naive Bayes**. The system features a **Graphical User Interface (GUI)** created using **Tkinter**, making it easy for users to input symptoms and get predictions.

## Overview
The system allows users to:
- Input up to **five symptoms** from a list of common symptoms.
- Choose between three machine learning algorithms to predict the disease:
  1. **Decision Tree Classifier**
  2. **Random Forest Classifier**
  3. **Naive Bayes Classifier**
- Get an accurate prediction based on trained data, along with model performance metrics (accuracy score).

The underlying models are trained on a dataset containing various diseases and their associated symptoms. The system uses this training data to classify the disease based on the symptoms entered.

## Features
- **Multiple Algorithms:** Users can compare results from different algorithms to see which one fits best.
- **Accuracy Measurement:** Each model displays its accuracy when tested on unseen data.
- **Interactive GUI:** The Tkinter-based GUI allows users to easily input symptoms and view results.
- **Symptom List:** The system can process 132 different symptoms, which are mapped to 41 potential diseases.
  
## Machine Learning Models
1. **Decision Tree**: A model that uses a tree-like structure to make decisions based on input features.
2. **Random Forest**: An ensemble method that uses multiple decision trees to improve the accuracy of predictions.
3. **Naive Bayes**: A probabilistic model based on Bayes' Theorem, often used for classification tasks.

### How It Works:
1. **Select Symptoms**: Choose up to five symptoms from dropdown menus.
2. **Choose Classifier**: Select a machine learning model to predict the disease.
3. **Get Prediction**: The system will output the predicted disease and display it in the results field.
4. **Accuracy Check**: The models also display their accuracy based on test data.

## Dataset
The training dataset contains a list of common symptoms and corresponding diseases. The symptoms are categorized, and each row represents a patient with specific symptoms, labeled with the diagnosed disease.

### Training Data:
The model is trained using a **.csv** file that includes the following:
- **Symptoms**: A list of symptoms such as back pain, fever, nausea, etc.
- **Diseases**: Diagnoses such as Fungal Infection, Hypertension, Typhoid, Tuberculosis, etc.

### Testing Data:
Another **.csv** file is used for testing and validating the model's performance.

## Project Structure
- **`Code.py`**: The main Python script that implements the GUI and models.
- **`Training.csv`**: The training dataset used to build and train the models.
- **`Testing.csv`**: The testing dataset used to evaluate the models' accuracy.

## Dependencies
- **Python 3.x**
- **Tkinter** (for GUI)
- **pandas** (for data manipulation)
- **NumPy** (for array operations)
- **scikit-learn** (for machine learning algorithms)

To install the necessary dependencies, run:
```bash
pip install numpy pandas scikit-learn
```

## How to Run the Project
1. Clone the repository.
2. Install the dependencies using `pip install`.
3. Run the `Code.py` script:
   ```bash
   python Code.py
   ```
4. The GUI will launch, allowing you to input symptoms and choose a machine learning model to predict the disease.

## Screenshots
Here are some examples of the application's interface and functionality:

1. **Main Screen**: Select symptoms and view predictions.
2. **Model Performance**: The system shows the accuracy of each model after prediction.

## Future Improvements
- **Enhanced Dataset**: Adding more symptoms and diseases to improve prediction accuracy.
- **Deep Learning Models**: Implementing deep learning techniques for better classification.
- **Web Integration**: Deploying the system as a web application for broader accessibility.

## Conclusion
This project demonstrates how machine learning algorithms can be effectively used in the healthcare domain for early disease detection. By inputting symptoms, the system provides potential disease diagnoses, helping medical professionals and patients alike.

## Contributions
Contributions are welcome! Feel free to fork the repository and submit pull requests with any improvements or additional features.

