Team members: Shreyas Shah, Sayali Lokhande, Bhuvana Ravikumar

**All results were found to be reproducible while running on CPU**

---

## File Descriptions

- **telco_raw_data.csv**  
  Raw Telco Customer Churn dataset.

- **final_telco_engineered.csv**  
  Dataset after data cleaning, preprocessing, and feature engineering.

- **models.ipynb**  
  Traditional machine learning models trained on the original dataset with class weights in loss function.

- **models-oversampling.ipynb**  
  Traditional machine learning models trained with random oversampling of the minority (churn) class.

- **models-smote+enn.ipynb**  
  Traditional machine learning models trained using SMOTE + ENN for class imbalance handling.

- **deep_learning_models.ipynb**  
  Feedforward Neural Network (FNN) and Multilayer Perceptron (MLP) models trained on the original dataset with class weights in loss function.

- **deep_learning_models-oversampling.ipynb**  
  FNN and MLP models trained with random oversampling of the minority class.

- **deep_learning_models-smote+enn.ipynb**  
  FNN and MLP models trained using SMOTE + ENN.

- **tabTransformer.ipynb**  
  Transformer-based model inspired by TabTransformer, trained on the original dataset with class weights in loss function.

- **tabTransformer-oversampling.ipynb**  
  Transformer-based model trained with random oversampling of the minority class.

- **tabTransformer-smote+enn.ipynb**  
  Transformer-based model trained using SMOTE + ENN.
