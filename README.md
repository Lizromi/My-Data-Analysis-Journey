# PROJECT NAME: Employee Attrition Analysis and Prediction
----
# PROJECT OBJECTIVE: Problem Statement

Acme Corporation, a leading tech company, is grappling with a pressing challenge – employee turnover. The increasing rate of attrition poses significant concerns for the HR department, as it adversely affects team dynamics, project continuity, and overall company morale. In response to this critical issue, Acme Corporation aims to harness the power of data analytics and machine learning to gain insights into the factors driving employee turnover and to predict which employees are likely to leave in the near future.

By leveraging advanced analytical techniques, Acme Corporation seeks to proactively identify at-risk employees and implement targeted retention strategies. This proactive approach not only helps in mitigating the negative impacts of turnover but also fosters a more stable and productive work environment.
Through this initiative, Acme Corporation demonstrates its commitment to employee well-being and organizational sustainability, positioning itself as a forward-thinking employer dedicated to leveraging data-driven solutions for workforce management challenges.

----
# DATA SOURCING
Acme Corporation has provided historical data on employee demographics, job satisfaction, work environment, performance metrics, and turnover status. This dataset spans the last five years and includes information on employees who have left the company and those who are still currently employed.

The dataset typically includes several features that provide insights into employee characteristics, job satisfaction, and performance. While the exact features may vary, here's a general list of common features you might find in such a dataset:

Employee ID: A unique identifier for each employee.

Age: The age of the employee.

Attrition: A binary variable indicating whether the employee has left the company (1) or is still employed (0).

Business Travel: The frequency and nature of business-related travel (e.g., "Travel_Rarely," "Travel_Frequently," "Non-Travel").

Department: The department to which the employee belongs (e.g., "Sales," "Research & Development," "Human Resources").

Distance From Home: The distance of the employee's residence from the workplace.

Education: The employee's level of education (e.g., "1: 'Below College'," "2: 'College'," "3: 'Bachelor'," "4: 'Master'," "5: 'Doctor').

Education Field: The field in which the employee's education lies (e.g., "Life Sciences," "Medical," "Marketing").

Environment Satisfaction: The level of satisfaction with the work environment on a scale.

Gender: The gender of the employee.

Job Involvement: The degree to which the employee is involved in their job.

Job Level: The level or rank of the employee's position.

Job Role: The specific role or title of the employee's job.

Job Satisfaction: The level of satisfaction with the job on a scale.

Marital Status: The marital status of the employee.

Monthly Income: The monthly salary of the employee.

Num Companies Worked: The number of companies the employee has worked for.

Over Time: Whether the employee works overtime or not.

Performance Rating: The performance rating of the employee.

Relationship Satisfaction: The level of satisfaction with relationships at the workplace.

Stock Option Level: The level of stock options provided to the employee.

Total Working Years: The total number of years the employee has been working.

Training Times Last Year: The number of training sessions the employee attended last year.

Work-Life Balance: The balance between work and personal life.

Years At Company: The number of years the employee has been with the current company.

Years In Current Role: The number of years the employee has been in their current role.

Years Since Last Promotion: The number of years since the last time the employee was promoted.

Years With Current Manager: The number of years the employee has been working under the current manager.

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
