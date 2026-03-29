#  Tuwaiq Classification Mini Project

##  Project Overview
This project demonstrates the use of the **K-Nearest Neighbors (KNN)** algorithm to solve a classification problem using real-world data.

The main objectives are:
- Understand how KNN works
- Implement it using **Python & Scikit-learn**
- Improve model performance through **hyperparameter tuning**

---

##  About KNN
KNN is a **lazy learning algorithm** that makes predictions based on the closest data points in the feature space.

It works by:
- Calculating the distance between data points  
- Selecting the K nearest neighbors  
- Assigning the majority class  

 In simple terms:
> A data point is classified based on its neighbors.

---

##  Project Workflow

### 1️ Data Preparation
- Loaded the dataset  
- Checked for missing values  
- Selected relevant features  
- Split data into training and testing sets  

---

### 2️ Data Preprocessing
- Applied **StandardScaler**  

Why?  
KNN relies on distance calculations, so feature scaling is essential.

---

### 3️ Initial Model (Baseline)
- Trained KNN with default parameters  
- Used as a baseline for comparison  

---

### 4️ Hyperparameter Tuning
Used **GridSearchCV** to find the best parameters:

- n_neighbors  
- metric  
- weights  

Best Parameters:
- n_neighbors = 30  
- metric = manhattan  
- weights = distance  

---

##  Results

### Before Tuning
- Accuracy: 73%  
- Precision: 73%  
- Recall: 73%  
- F1 Score: 73%  

### After Tuning
- Accuracy: 84%  
- Precision: 85%  
- Recall: 84%  
- F1 Score: 84%  

---

##  Performance Comparison

| Metric     | Before | After |
|------------|--------|-------|
| Accuracy   | 73%    | 84%   |
| Precision  | 73%    | 85%   |
| Recall     | 73%    | 84%   |
| F1 Score   | 73%    | 84%   |

---

##  Key Improvements
- Performance improved after tuning  
- Better selection of K  
- Accuracy increased by +11%  

---

##  Challenges
- Slow with large datasets  
- Sensitive to scaling  
- Affected by noise  

---

##  Key Takeaways
- KNN is simple but powerful  
- Choosing K is critical  
- Tuning improves results significantly  

---

##  Technologies Used
- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn 

---

##  Project Structure
data/  
README.md  
Tuwaiq_Classification_Mini_Project.ipynb  

