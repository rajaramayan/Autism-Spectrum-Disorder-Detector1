
# ASD Screening Prediction System

A web-based application for predicting Autism Spectrum Disorder (ASD) using Machine Learning and Artificial Neural Networks.

## ⚠️ Disclaimer

**This tool is for educational and research purposes only.** It should NOT be used as a substitute for professional medical diagnosis. Please consult with qualified healthcare professionals for proper diagnosis and treatment.

---

## 🚀 Quick Start Guide

### Prerequisites
- Python 3.8 or higher
- pip (Python package installer)

### Installation Steps

#### Step 1: Install Required Packages

Open PowerShell or Command Prompt in your project directory and run:

```bash
pip install -r requirements.txt
```

#### Step 2: Run the Streamlit App

```bash
streamlit run streamlit_app.py
```

#### Step 3: Access the Application

The app will automatically open in your default browser at:
```
http://localhost:8501
```

If it doesn't open automatically, manually navigate to the URL above.

---

## 📋 Features

### 1. **Home Page** 🏠
- Overview of the application
- Dataset information and statistics
- Preview of the screening data

### 2. **Model Training** 🤖
- Train 8 classical ML models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - KNN
  - SVM (Linear & RBF)
  - Naive Bayes
  - Linear Discriminant Analysis
- Train Artificial Neural Network (ANN)
- View performance metrics for all models

### 3. **Make Prediction** 🔮
- Input patient screening values using interactive sliders
- Get predictions from both:
  - Best classical ML model
  - Artificial Neural Network
- View confidence scores for each prediction

### 4. **Model Comparison** 📊
- Compare all models side-by-side
- View ROC curves
- Analyze performance metrics (Accuracy, Precision, Recall, F1-Score, etc.)
- Visual ranking of models by ROC-AUC score

---

## 📊 Dataset

- **File:** `Autism_Screening_Data_Combined.csv`
- **Contents:** Screening features and ASD diagnosis labels
- **Preprocessing:**
  - Removes duplicates
  - Handles missing values
  - Encodes categorical variables
  - Applies SMOTE for class imbalance
  - Standardizes features

---

## 🔧 Technical Details

### Models Included

#### Classical ML Models
- **Logistic Regression:** Linear model for binary classification
- **Decision Tree:** Tree-based model for interpretability
- **Random Forest:** Ensemble method with multiple decision trees
- **K-Nearest Neighbors:** Distance-based classification
- **Support Vector Machines:** Powerful kernel-based classifier (Linear & RBF kernels)
- **Naive Bayes:** Probabilistic classifier
- **Linear Discriminant Analysis:** Statistical classifier

#### Deep Learning Model
- **Artificial Neural Network (ANN):**
  - Input Layer: Dynamic based on feature count
  - Hidden Layer 1: 32 neurons with ReLU activation
  - Hidden Layer 2: 16 neurons with ReLU activation
  - Output Layer: 1 neuron with Sigmoid activation
  - Optimizer: Adam
  - Loss: Binary Crossentropy
  - Epochs: 50

### Evaluation Metrics
- **Accuracy:** Overall correctness
- **Precision:** True positives among positive predictions
- **Recall:** True positives among actual positives
- **Specificity:** True negatives among actual negatives
- **F1-Score:** Harmonic mean of Precision and Recall
- **ROC-AUC:** Area under ROC curve
- **Log Loss:** Probabilistic error measure

---

## 🛠️ Troubleshooting

### Issue: "Module not found" error
**Solution:** Make sure all dependencies are installed:
```bash
pip install -r requirements.txt
```

### Issue: Streamlit not starting
**Solution:** Try running with explicit Python:
```bash
python -m streamlit run streamlit_app.py
```

### Issue: Dataset file not found
**Solution:** Ensure `Autism_Screening_Data_Combined.csv` is in the same directory as `streamlit_app.py`

### Issue: TensorFlow installation issues
**Solution:** On Windows, TensorFlow might take time to install. Try:
```bash
pip install --upgrade tensorflow
```

### Issue: Permission denied
**Solution:** Run PowerShell as Administrator and try again

---

## 📁 Project Structure

```
Chhaya_project_deployment/
├── streamlit_app.py                          # Main Streamlit application
├── requirements.txt                          # Python dependencies
├── Autism_Screening_Data_Combined.csv        # Dataset
├── ASD in Children using Machine Learning and ANN (1).py  # Original analysis script
└── README.md                                 # This file
```

---

## 🔗 Streamlit Documentation

- Official Docs: https://docs.streamlit.io/
- Streamlit Gallery: https://streamlit.io/gallery

---

## 📝 Usage Tips

1. **First Time:** Start with the "Home" page to understand the dataset
2. **Training:** Go to "Model Training" and click "Train All Models"
3. **Wait:** Training takes 2-5 minutes depending on your computer
4. **Prediction:** Once training is complete, go to "Make Prediction"
5. **Comparison:** View model performance in "Model Comparison"

---

## ⚡ Performance Tips

- **First run will be slower** due to model training
- **Subsequent runs will be faster** as models are cached
- **Close unused applications** if you have slow performance

---

## 📞 Support

For issues or questions:
1. Check this README
2. Review Streamlit documentation
3. Verify all files are in the correct directory

---

## 📄 License

This project is for educational purposes. Use responsibly and always consult healthcare professionals for medical decisions.

---

## 🎓 Educational Purpose

This application demonstrates:
- Machine Learning model comparison
- Feature preprocessing and scaling
- Class imbalance handling (SMOTE)
- Deep Learning with TensorFlow/Keras
- Interactive web applications with Streamlit
- Data visualization and analysis

---

**Happy exploring! 🚀**

# autism_predictor
PREDICTION OF AUTISM SPECTRUM DISORDER IN CHILDRENS USING MACHINE LEARNING TECHNIQUES

