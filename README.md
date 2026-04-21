# **Experiment No. 15**
## **Title**

Data Normalization and Encoding using Python

## **Aim**

To apply data normalization and encoding techniques to prepare datasets for analysis and machine learning.

## **Theory**

Data preprocessing is an important step in data analysis and machine learning. It includes techniques like normalization and encoding to make data consistent and suitable for modeling.

Normalization is used to scale numerical data into a standard range, while encoding converts categorical data into numerical form so that machine learning algorithms can process it.

### Data Normalization
- Scaling numerical values to a standard range
- Improves model performance and accuracy
###### Min-Max Normalization
- Scales values between 0 and 1
- Formula: (X - Xmin) / (Xmax - Xmin)
- Functions used:
  - df.min()
  - df.max()
###### Z-Score Normalization
- Centers data around mean (0)
- Formula: (X - μ) / σ
- Functions used:
  - df.mean()
  - df.std()
###### Decimal Scaling
- Scales values by dividing by powers of 10
- Uses arithmetic operations
### Encoding Techniques
######Label Encoding
- Converts categories into numeric labels
- Functions used:
  - LabelEncoder()
  - fit_transform()
###### One-Hot Encoding
- Converts categories into multiple binary columns
- Function used:
  - pd.get_dummies()
###### Dummy Encoding
- Similar to one-hot but avoids redundancy
- Function used:
  - pd.get_dummies(drop_first=True)
###### Additional Functions Used
- pd.DataFrame() → Create dataset
- pd.read_csv() → Load dataset
- print() → Display output
- df[['col1','col2']] → Select columns
- df.columns → View column names
### Dataset Description
###### Product Dataset
- Product Name
- Price
- Units Sold
- Discount
###### E-Commerce Dataset
- Order ID
- Gender
- Payment Method
- Product Category
- City
- Order Value
###### Amazon Dataset
- Product Name
- Price
- Rating
- Reviews
- Units Sold
###### Student Dataset
- Gender
- Department
- CGPA
- Attendance
- Placement Status
- Salary
### Operations Performed
###### Normalization Techniques
- Min-Max normalization
- Z-score normalization
- Decimal scaling
###### Encoding Techniques
- Label encoding
- One-hot encoding
- Dummy encoding
###### Data Processing
- Handling multiple datasets
- Transforming structured data
- Preparing machine learning ready data
###### Workflow
- Data creation or loading
- Data inspection
- Applying normalization
- Encoding categorical data
- Data transformation
- Final dataset preparation
### Observations
- Different normalization techniques produce different scales
- Encoding is necessary for machine learning models
- Method selection depends on dataset and use case
## **Conclusion**

This experiment demonstrates how normalization and encoding convert raw data into a machine-ready format.

Numerical data becomes comparable
Categorical data is transformed into usable form
Preprocessing improves analysis accuracy
Dataset becomes suitable for machine learning applications
