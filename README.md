# fashion-with-cnn
# Fashion MNIST Classification

## 📌 Project Overview
This project uses the **Fashion MNIST dataset** to classify grayscale images of clothing items (e.g., shirts, shoes, bags) into 10 categories.  
The dataset is loaded from CSV files (`fashion-mnist_train.csv` and `fashion-mnist_test.csv`) and processed for machine learning model training and evaluation.

---

## 📊 Dataset
The Fashion MNIST dataset contains **70,000** images of fashion items:
- **Training set:** 60,000 samples (`fashion-mnist_train.csv`)
- **Test set:** 10,000 samples (`fashion-mnist_test.csv`)
- **Image size:** 28x28 pixels (flattened into 784 features)
- **Labels:** 10 classes

## 🔍 Project Steps

1. **Load CSV Data**
2.  using `pandas.read_csv`
3.  
4. **Data Preprocessing**
 - Separate labels from features
 - Normalize pixel values (0–255 → 0–1)
 - Reshape for visualization
 - 
3. **Exploratory Data Analysis (EDA)**
 - Display random sample images
 - Check class distribution
 - 
4. **Model Training**
 - Neural Networks (optional)
