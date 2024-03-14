This report was written with a goal of analysing and predicting whether a women would develop diabetes based on a the PimaDiabetes dataset. It was derived from the USA’s National Institute of Diabetes and Digestive and Kidney Diseases(NIDDK) (Smith et al., 1988). 

The data was collected from a Pima Indian population near Phoenix, Arizona. This population has a higher rate of diabetes as compared to the general population. If accurate, this model serves the purpose of predicting whether women in that population would get diabetes given certain variables. 

I followed the normal set of procedures that one would before creating a supervised classification model for logistic regression. These steps included:
  a) Exploratory data analysis (missing values, kernel density estimators, boxplots, skewness, heatmaps etc) 
  b) Data preprocessing (Standardising skewed features, removing outliers, dropping columns with too many missing values. 
  c) Training the model (performing a train-test split wiht 0.25 test data ratio, 5-fold cross validation,hyperparameter tuning using grid search)
  d) testing the model + results (accuracy score, precision and recall, confusion matrix, ROC curve)
