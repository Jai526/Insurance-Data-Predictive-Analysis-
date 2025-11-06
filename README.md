#Project Overview

This project focuses on performing predictive data analysis to estimate medical insurance charges based on various demographic and lifestyle factors using IBM SPSS Modeler. The project aims to help the organization understand how attributes like age, body mass index (BMI), smoking habits, region, and number of dependents influence an individual’s medical expenses.
By applying SPSS Modeler’s data preparation, transformation, and predictive modeling tools, the project demonstrates how raw data can be turned into actionable insights that assist insurance companies in pricing policies accurately, identifying high-risk customers, and improving decision-making.

##Project Objectives
To import and explore the Insurance dataset using IBM SPSS Modeler.


To identify relationships between key fields, such as BMI vs. charges and smoker vs. charges.


To perform Derive operations for creating new fields like BMI Category and Age Group.


To apply Reclassify operations for simplifying and grouping categorical fields (e.g., combining regional data).


To build a predictive model (such as a regression or decision tree) to forecast insurance charges.


To evaluate model performance and interpret which factors most significantly influence insurance costs.



##Dataset Description
The dataset used in this project is the Insurance Dataset, which contains information about individuals’ personal and lifestyle attributes along with their corresponding medical charges.
 The main attributes include:
Age: Age of the insured person


Sex: Gender of the insured person


BMI: Body Mass Index, representing body weight relative to height


Children: Number of dependents covered by the insurance


Smoker: Indicates whether the person is a smoker


Region: The residential area (northeast, northwest, southeast, southwest)


Charges: Medical insurance cost billed by the provider



#Tools and Techniques Used
Software: IBM SPSS Modeler


##Techniques:


Data Import and Exploration


Derive and Reclassify Operations


Correlation and Relationship Analysis


Predictive Modeling (Regression / Decision Tree)


Data Visualization using Graph and Table Nodes



##Data Preparation and Transformation
##Derive Operation
The Derive node is used to create new fields based on existing data to improve analysis and modeling accuracy.
 Examples include:
BMI Category: Derived from the BMI value to classify individuals as Underweight, Normal, Overweight, or Obese.


Age Group: Derived from the Age field to group customers as Young Adult, Middle Aged, or Senior.


##Reclassify Operation
The Reclassify node is applied to simplify categorical data and group similar values.
 Examples:
Grouping regional data into “North” and “South” categories.


Renaming the Smoker field values from “yes/no” to “Smoker/Non-Smoker”.


These transformations make the dataset more meaningful and easier to analyze during predictive modeling.


##Relationship Analysis
After data preparation, relationship analysis is conducted to explore dependencies between different variables:
Correlation Analysis: To find relationships between numeric variables like BMI and Charges.

##Insights and Interpretation
From the analysis, several insights can be drawn:
Smokers generally have much higher medical charges than non-smokers.


BMI has a positive correlation with insurance charges — higher BMI often results in higher costs.


Age also influences charges, with older individuals tending to incur higher expenses.


Derived and reclassified fields provide clearer segmentation for analysis and decision-making.



##Business Impact
This project demonstrates how data-driven insights can help an insurance company:
Predict customer charges more accurately.


Identify high-risk individuals.


Optimize premium pricing strategies.


Support fair and evidence-based policy decisions.



##Conclusion
This project successfully illustrates the complete workflow of data preparation, analysis, and predictive modeling using IBM SPSS Modeler. By performing Derive and Reclassify operations and analyzing relationships between key variables, meaningful insights were extracted from the dataset.
 The predictive model built through this project helps estimate future medical insurance costs and supports the company’s efforts in improving its data-driven decision-making process.
