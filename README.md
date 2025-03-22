# Data Analysis Project

## Overview
This repository holds several dataset analyses, including government data, student exam scores, Titanic survival prediction, car price prediction, and question analysis. Each dataset folder has:
- **Raw Dataset**: The original data in CSV or equivalent format.
- **Jupyter Notebook (`.ipynb`)**: Exploratory Data Analysis (EDA) and machine learning models.  
- **PDF Report**: A summary of findings, visualizations, and insights.  
- **Presentation (`.pptx`)** (For Government Data Analysis): A PowerPoint summary of key findings.  

## Project Structure  
```
/1.Government_Dataset_Analysis  
  ├── government_data.csv  
  ├── government_data_analysis.ipynb  
  ├── government_data_report.pdf  
  ├── government_data_analysis.pptx  

/2.Exam_Marks_Dataset_Analysis
├── exam_marks.csv  
  ├── exam_marks_analysis.ipynb  
  ├── exam_marks_report.pdf  

/3.Question_Marks_Analysis  
  ├── question_data.csv  
  ├── question_analysis.ipynb  
  ├── question_analysis_report.pdf  

/4.Titanic_Dataset_Analysis  
  ├── titanic.csv  
  ├── titanic_analysis.ipynb  
  ├── titanic_report.pdf  

/5.Car_Price_Prediction_Analysis  
  ├── car_prices.csv  
  ├── car_price_prediction.ipynb  
  ├── car_price_report.pdf  
```

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/data-analysis-project.git
   cd data-analysis-project
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
3. Run Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open the `.ipynb` files and run the code.

## Dataset Summaries
### 1️⃣ Government Dataset Analysis
- Processes government-related information, such as demographics, policy, and economic trends.
- Plots the most important statistics and trends across time.
- **Includes** a PowerPoint summary of findings (**government_data_analysis.pptx**).

### 2️⃣ Exam Marks Dataset Analysis
- Assesses performance of students by exam marks.
- Finds patterns in marks distribution and possible correlations.

### 3️⃣ Question Marks Analysis
- Analyzes question-wise scoring patterns.
- Assists in identifying tough topics and maximizing learning strategies.

### 4️⃣ Titanic Dataset Analysis
- Learns to predict passenger survival based on machine learning models.
- Examines factors such as age, gender, and ticket class.

### 5️⃣ Car Price Prediction Analysis
- Creates a machine learning model that predicts car prices based on various parameters.
- Compares regression models on the basis of prediction.  

## Key Features
✅ Data Cleaning: Dealing with missing values, outliers, and formatting errors.
✅ Exploratory Data Analysis (EDA): Insights through visualizations using Seaborn & Matplotlib.
✅ Machine Learning: Creating predictive models wherever appropriate.
✅ Reports: PDF reports with conclusions and major takeaways.
✅ **Presentation**: Government data analysis results in PowerPoint presentation.

## Future Improvements
Enhance feature engineering to make more accurate predictions.
Utilize deep learning models for deeper analysis.
Increase dataset diversity for more general insights.
