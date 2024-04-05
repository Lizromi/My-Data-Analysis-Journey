# PROJECT NAME: Employee Attrition Analysis and Prediction
----
# PROJECT OBJECTIVE: PROBLEEM STATEMENT
Acme Corporation, a leading tech company, is facing a significant challenge with employee turnover. The HR department is concerned about the increasing rate of attrition, as it negatively impacts team dynamics, project continuity, and overall company morale. To address this issue, Acme Corporation wants to leverage data analytics and machine learning to understand the factors influencing employee turnover and predict which employees are likely to leave in the near future.
----
# DATA SOURCING

----
# DATA TRANSFORMATION
Step 1: Introduction and Import Libraries
Imported essential modules such as NumPy, pandas, Matplotlib, seaborn, and scikit-learn.

Step 2: Exploratory Data Analysis
Loaded the employee dataset using pandas. Explored the data visually by plotting various features against the target variable 'Attrition'. Use Matplotlib and seaborn for visualization.

Step 3: Encode Categorical Feature. 
The dataset contains categorical variables: 'Attrition', 'Overtime', and 'Gender'. I encoded these categorical variables using one-hot encoding or label encoding. This step ensures that the machine learning model can understand and process the textual data.

Step 4: Visualize Class Imbalance
Createed a bar plot to visualize the distribution of the 'Gender' column and check for any data imbalance. This step helps in understanding if there is any bias in the dataset towards a particular gender.

Step 5: Create Training and Validation Sets
Splited the data into training and validation sets using a stratified sampling strategy. Ensure an 80/20 split to maintain a balance between the two sets. Stratified sampling helps in preserving the distribution of classes in both sets.

Step 6: Build a Logistic Regression Model
Use scikit-learn to build and train a logistic regression model. Evaluate the model's performance on both the training and validation sets by calculating accuracy and other evaluation metrics.


# FINDINGS AND RECOMMENDATIONS
-
