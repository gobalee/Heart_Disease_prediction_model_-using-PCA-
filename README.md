# Heart Disease prediction model(using-PCA)

1. The classification model used is RandomForestClassifier() 
2. The categorical features are first converted to numbers with the help of pd.get_dummies()
3. The features are then scaled using StandardScaler()
4. The model trained on original dataset (without reducing the features) is ~90%
5. Accuracy of model trained on reduced features is ~70%
