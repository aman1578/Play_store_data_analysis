
## Google Play Store Apps Data Analysis & Cleaning

# Overview
This project analyzes and cleans the Google Play Store apps dataset to uncover insights about app ratings, categories, pricing, and user engagement. The workflow includes data loading, preprocessing, handling missing values, feature engineering, and exploratory analysis.

Dataset : Source: Kaggle/Krishnaik's Play Store Dataset
Size : 10,841 apps × 13 features (Category, Rating, Reviews, Size, Installs, etc.).

# Key Steps
Data Cleaning:

Handled missing values (e.g., Rating, Content Rating).

Converted columns to appropriate types (Reviews → int, Size → numeric, Price → float).

Processed date features (Last Updated to datetime, extracted Day/Month/Year).

Removed duplicates (1,181 duplicates dropped).

Feature Engineering:

Cleaned Installs and Price by removing special characters.

Normalized Size (converted "M" to KB and "k" to MB).

Exploratory Data Analysis (EDA):

Analyzed categorical distributions (Category, Type, Content Rating).

Explored trends in app ratings, installs, and pricing.

# Tools Used

Python, Pandas, NumPy, Matplotlib, Seaborn.

# Key Insights

Top Categories: Family, Games, Tools.

Missing Data: 1,474 missing ratings addressed.

Free vs. Paid: 92.6% apps are free.

User Engagement: Most apps have 10,000+ installs.

# Output

Cleaned dataset saved as google_cleaned.csv.

# Usage
Install dependencies:
pip install pandas numpy matplotlib seaborn  
Run play_store.ipynb to reproduce analysis.

# Next Steps
Perform deeper statistical analysis.
Build predictive models for app ratings/success.

