# Breast Cancer Prediction

This project aims to predict whether a patient is suffering from malignant or benign breast cancer. By leveraging various machine learning techniques, including logistic regression, support vector machine (SVM), and neural networks, this tool provides accurate predictions to aid in medical diagnosis.

## Usage

To use this project:

1. Clone the repository to your local machine.
2. Run the `breastcancerpredict.ipynb` script.
3. Input the required patient data.
4. Obtain the prediction for the patient's condition.

## Techniques Used

### Logistic Regression

Logistic regression is a commonly used statistical technique for binary classification tasks. In this project, logistic regression is utilized to model the probability of a patient having malignant or benign breast cancer based on input features.

### Support Vector Machine (SVM)

SVM is a powerful supervised learning algorithm capable of performing classification, regression, and outlier detection tasks. It works by finding the optimal hyperplane that best separates data points belonging to different classes. SVM is employed in this project to classify patients into malignant or benign categories.

### Neural Networks

Neural networks are a class of machine learning models inspired by the structure and function of the human brain. They consist of interconnected nodes organized in layers and are capable of learning complex patterns from data. In this project, neural networks are used to capture intricate relationships between input features and the likelihood of a patient having malignant or benign breast cancer.

## Dataset

The dataset used in this project contains various features extracted from breast cancer biopsies, including:

ID: Unique identifier for each patient.
Diagnosis: The target variable indicating whether the cancer is malignant (M) or benign (B).
Radius Mean: Mean of distances from the center to points on the perimeter.
Texture Mean: Standard deviation of gray-scale values.
Perimeter Mean: Total perimeter of the tumor.
Area Mean: Total area of the tumor.
Smoothness Mean: Local variation in radius lengths.
Compactness Mean: Perimeter^2 / area - 1.0.
Concavity Mean: Severity of concave portions of the contour.
Concave Points Mean: Number of concave portions of the contour.
Symmetry Mean: Symmetry of tumor.
Fractal Dimension Mean: "Coastline approximation" - 1.
... and many more.


## Acknowledgments

Special thanks to the medical professionals and researchers whose work contributes to the understanding and treatment of breast cancer. Their dedication and expertise make projects like this possible.
