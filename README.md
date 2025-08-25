# Basic Music Recommendation 🎵

This project demonstrates a **basic machine learning model** that predicts a person's preferred music genre based on their **age** and **gender**.  
It uses a **Decision Tree Classifier** from Scikit-learn and includes model evaluation, visualization, and performance metrics.

---

## 📂 Project Structure
- `BasicMusicRecommendation.ipynb` → Jupyter Notebook with full code and explanations  
- `music.csv` → Dataset containing age, gender, and music genre  
- `music-recommender.dot` → Decision Tree visualization in Graphviz format  
- `README.md` → Project documentation  

---

## 🚀 Features
- Loads dataset with Pandas  
- Trains a **Decision Tree Classifier**  
- Splits data into **training and test sets**  
- Evaluates model with **accuracy score**, **classification report**, and **confusion matrix**  
- Visualizes the decision tree with **Graphviz**  
- Interactive prediction example: input age & gender → get music genre recommendation  

---

## 📊 Example Workflow
```python
# Train and predict
model.fit(X_train, y_train)
predictions = model.predict(X_test)

# Evaluate accuracy
from sklearn.metrics import accuracy_score
print("Accuracy:", accuracy_score(y_test, predictions))
