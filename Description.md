- **Data Gathering:**
  - Used Pandas to read a wine dataset from a CSV file.
  - Explored the dataset with basic commands such as `shape`, `info`, `isna().sum()`, and `describe()` to understand its structure and characteristics.

- **Exploratory Data Analysis (EDA):**
  - Checked the shape, info, and summary statistics of the dataset.
  - No missing values were found.
  - Descriptive statistics were examined to understand the distribution of features.
  
- **Feature Engineering:**
  - Detected outliers using the Interquartile Range (IQR) method.
  - Replaced outliers with upper or lower bounds for specific columns using a custom function.

- **Principal Component Analysis (PCA):**
  - Standardized the data using `StandardScaler`.
  - Applied PCA to reduce dimensionality.
  - Computed covariance matrix, eigenvalues, and eigenvectors.

- **Model Training:**
  - Split the dataset into training and testing sets.
  - Applied Logistic Regression for multi-class classification.
  - Utilized PCA for dimensionality reduction.

- **Results and Conclusion:**
  - Explored variance ratios of principal components.
  - Trained a Logistic Regression model on the transformed data.
