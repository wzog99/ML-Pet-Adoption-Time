# Predicting Pet Adoption Time
![Kaggle Dataset](https://www.kaggle.com/c/petfinder-adoption-prediction/data)

### Purpose 
Predicting whether the adoption of a pet would take over or under 30 days.

### Process
- Obtain dataset from Kaggle with accompanying csv files for joining 
- Replace ID placeholders for breed, color, and location with corresponding values
- Replace numerically encode information with appropriate categorical terms. For example: 1 becomes ‘dog’, 2 becomes ‘cat’.
- Applying EDA to gain insight on what feature shows a significant impact on adoption speed
- Apply standard scaler / min max  transformation to standardize and remove outliers 
- Train-test split
- Evaluate and compare various Machine Learning classifiers

### TO-DO's
- Apply NLP to description field to vectorize and encode impact on adoption times
- Look into how computer vison (CNN) can improve model predictions 

