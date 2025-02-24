## **Breast Cancer Analyzer**

### **Project Description**

This AI model is designed to analyze breast cancer data and classify tumors as **benign** or **malignant** based on medical features. The dataset used comes from a CSV file  online, derived from the **Wisconsin Breast Cancer Dataset**. The model leverages machine learning to assist in early detection and diagnosis, which can be crucial for timely treatment.

----------

### **How the AI Model is Built**

#### **1. Data Processing & Preprocessing**

-   **Libraries Used:**  `pandas`, `numpy`, `seaborn`, `matplotlib`
    
-   **Dataset:** Loaded from a URL using `pandas.read_csv()`
    
-   **Feature Encoding:** The target variable (`diagnosis`) is converted into numerical values using `LabelEncoder`.
    
-   **Feature Scaling:** Standardization is applied using `StandardScaler()` to normalize feature values.
    

#### **2. Exploratory Data Analysis (EDA)**

-   **Correlation Matrix:** Used to identify relationships between different features.
    
-   **Value Counts:** Checked the distribution of benign vs. malignant cases.
    

#### **3. Model Development**

-   **Train-Test Split:** Data is split into training and testing sets using `train_test_split(test_size=0.2, random_state=12)`.
    
-   **Algorithm Used:**  `KNeighborsClassifier` (K-Nearest Neighbors)
    
-   **Parameter Selection:**  `n_neighbors=5` is used for KNN.
    

#### **4. Model Training & Evaluation**

-   The KNN classifier is trained using the training data.
    
-   Model performance is evaluated using accuracy metrics.
![accuracy](https://github.com/user-attachments/assets/d1b771cf-44b1-4939-9de2-42f665a7a51a)
![loss](https://github.com/user-attachments/assets/2525c310-b210-44c8-af0f-84780b955430)

## Installation
To run this project locally, ensure you have the following dependencies installed:
- Python 3.x
- TensorFlow
- Scikit-learn

