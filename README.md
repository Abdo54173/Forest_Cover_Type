# 🌲 Forest Cover Type Classification

This project predicts the **type of forest cover** based on cartographic and environmental features using the **UCI Covertype dataset**.

---

## 📊 Project Workflow
1. **Data Loading & Preprocessing**
   - Handled categorical and continuous features  
   - Checked for missing values (dataset is already clean)  

2. **Exploratory Data Analysis (EDA)**
   - Target distribution visualization  
   - Histograms & boxplots for continuous features  
   - Correlation heatmap  

3. **Model Training**
   - **XGBoost Classifier** (with class weights for imbalance)  
   - **Random Forest Classifier** (with RandomizedSearchCV for tuning)  

4. **Evaluation**
   - Balanced Accuracy, Macro F1-score  
   - Classification Report & Confusion Matrix  
   - Feature Importance visualization  

---

## 📈 Results
- XGBoost achieved **Balanced Accuracy ~0.91**, good at capturing minority classes.  
- Random Forest achieved **Macro F1 ~0.84**, more precise but less recall for rare classes.  

---

## 🔍 Visualizations
- Confusion Matrix heatmap  
- Feature importance plots (XGBoost & Random Forest)  

---

## 🚀 How to Run
```bash
# Clone repository
git clone https://github.com/Abdo54173/Forest_Cover_Type.git
cd Forest_Cover_Type

# Install requirements
pip install -r requirements.txt

# Run notebook / script
jupyter notebook forest_cover_classification.ipynb
