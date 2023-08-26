# **Pre-Interview Classification Project**


This project is focused on predicting whether an individual will be accepted for an interview based on various features. 
The dataset comprises features such as age, business travel frequency, marital status, and others. Several classifiers were evaluated 
to obtain the best predictive model.




**Features Description**

**1.Age**: Numeric representation of the age of the candidate.

**2.BusinessTravel**: Categorical feature indicating the frequency of business travel (e.g., "Rarely", "Frequently").

**3.Education**: Numeric value indicating the education level.

**4.MaritalStatus**: Categorical feature indicating marital status.

**5.OverTime**: Categorical feature representing whether the candidate works overtime.

**6.EmployeeNumber**: Unique identifier for each employee.

**7.DailyRate**: Numeric value representing the daily rate of the employee.

**8.Gender**: Categorical feature indicating the gender of the candidate.

**9.accepted for the interview**: Target variable. Boolean representation indicating whether the candidate was accepted for the interview.




**Workflow**

**1.Importing Libraries**: Necessary Python libraries for data manipulation, visualization, and modeling were imported.

**2.Loading Data**: Data was loaded from a provided source.

**3.Data Exploration and Preprocessing**:Explored dataset to understand its structure and the type of data it contains.
Observed imbalance in the target variable and performed data balancing to make prediction more accurate.
Applied necessary preprocessing techniques like one-hot encoding.




**Conclusion**

After conducting extensive analyses and testing multiple classification models, the Random Forest classifier emerged as the most 
suitable choice for predicting whether a candidate was accepted for an interview based on the given features. This decision was 
informed by the model's robustness, ability to handle imbalances, and superior performance metrics.
