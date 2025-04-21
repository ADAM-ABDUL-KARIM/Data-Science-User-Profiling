# Data-Science-User-Profiling
This project analyzes smartphone usage data collected from May 17, 2019, to November 27, 2019 (approximately 6 months). The analysis focuses on understanding app usage patterns, screen time habits, and user behaviors

## Data Files

The project uses several datasets:

- **app_usage.csv**: Raw app usage statistics
- **app_usage_cleaned.csv**: Cleaned app usage data
- **phone_use_data.csv**: Daily phone usage statistics
- **phone_use_data_cleaned.csv**: Cleaned phone usage data
- **detailed_phone_usage.csv**: Detailed logs of phone usage
- **detailed_phone_usage_cleaned.csv**: Cleaned detailed usage data
- **MergedFinal.csv**: Final merged dataset
- **MergedForWeka.arff**: Dataset formatted for Weka machine learning

## Project Structure

- **[Data Science/Jupyter/Project Practice/](Data%20Science/Jupyter/Project%20Practice/)**: Main data processing and visualization
  - **Codes.ipynb**: Primary notebook with data cleaning and EDA
  
- **[Data Science/Models/python/](Data%20Science/Models/python/)**: Machine learning models
  - **Model.ipynb**: Classification model for app categories
  - **heavyusage.ipynb**: Model to determine heavy usage patterns

## Key Findings

1. **Total Screen Time**: ~1,214 hours (approx. 50 days) over the 6-month period
2. **Phone Check Count**: 14,090 times the user checked their phone
3. **Most Used Apps**:
   - Instagram: 329 hours
   - WhatsApp: 145 hours
   - Phone: 105 hours
   - Call of Duty: 85 hours
   - YouTube: 82 hours

4. **Usage Patterns**:
   - Strong correlation between app access count and usage hours
   - Social media dominates usage time
   - Usage varies by day of week and time of day
   - The merged dataset includes calculated metrics like average time per access and average time per day

## Analysis Techniques

- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Temporal analysis (monthly, daily, hourly patterns)
- App category classification
- Usage pattern identification
- Visualization of usage trends

## Machine Learning Models

The project implements models to:
- Classify apps into categories
- Determine if a user has "high screen time" (defined as >240 minutes daily)

## Technologies Used

- Python
- Pandas for data manipulation
- Matplotlib for visualization
- Scikit-learn for machine learning models
- Weka for alternative machine learning analysis

## Further Development

The project could be extended to include:
- Predictive modeling of future usage patterns
- App recommendation systems
- Screen time reduction interventions
- More sophisticated classification of app usage behaviors
