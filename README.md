# Disease Symptoms and Treatments Analysis

**_Dataset_**  
- Kaggle dataset of diseases with **symptoms**, **treatments**, and labels for **contagious** and **chronic** diseases (MIT License).  

**_Exploratory Analysis_**  
- Calculated percentages of contagious (~28%) and chronic diseases.  
- Identified most common **diseases, symptoms, and treatments**.  
- Visualized distributions using **bar plots**.  
- Cleaned and tokenized symptom and treatment text.  

**_Predictive Modeling_**  
- Logistic regression using **TF-IDF features** from symptoms to predict contagiousness.  
- 80/20 train/test split with **cross-validated L2 regularization**.  
- Test set accuracy: **71.4%**.  
- Better at predicting **non-contagious diseases** (sensitivity 88.7%) than **contagious** (specificity 42.5%).  

**_Conclusion_**  
- Symptoms contain **some predictive signal** for contagiousness.  
- Additional features (disease category, transmission route, lab results) could improve predictions.  

**_Dataset Credit_**  
- [Kaggle: Disease Symptoms and Treatments Dataset](https://www.kaggle.com/datasets/snmahsa/disease-symptoms-and-treatments-dataset/data) (MIT License)
