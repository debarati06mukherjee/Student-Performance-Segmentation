# Student Performance Segmentation and Academic Success Profiling

**ISI–IDEAS TIH Autumn Internship 2026 | Data Science**

## Project Overview

This project analyzes student academic performance using data preprocessing, exploratory data analysis, clustering, and machine learning techniques. The objective is to identify student groups based on academic performance and background characteristics and explore how these insights can support personalized educational strategies.

## Dataset

- **Dataset:** StudentsPerformance.csv
- **Records:** 1,000 students
- **Original Features:** 8
- **Source:** [Students Performance Dataset](https://raw.githubusercontent.com/rashida048/Datasets/master/StudentsPerformance.csv)

The dataset includes mathematics, reading, and writing scores along with student demographic and educational background information.

## Technologies Used

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Methodology

1. Data loading and cleaning
2. Exploratory data analysis and correlation visualization
3. Composite academic score calculation
4. Categorical feature encoding and standardization
5. K-Means clustering and Elbow Method
6. Cluster profiling and interpretation
7. Logistic Regression, Random Forest, and MLP classification
8. Model evaluation and comparison
9. Educational strategy recommendations

## Results

- Identified four student clusters using K-Means clustering.
- Obtained a silhouette score of approximately **0.1954**, indicating relatively weak cluster separation.
- Compared Logistic Regression, Random Forest, and MLP classifiers.
- All three classifiers achieved **100% test accuracy** when predicting the generated cluster labels.

**Note:** The classification models predict K-Means-generated cluster labels rather than independently observed academic success. Therefore, the accuracy results should not be interpreted as perfect prediction of student academic outcomes.

## Conclusion

The project demonstrates how clustering and classification can be applied to student data to identify different student profiles. The findings may help educational platforms explore personalized learning support, although further validation and consideration of demographic fairness are necessary.

## Internship Details

**Organization:** IDEAS – Institute of Data Engineering, Analytics and Science Foundation, ISI Kolkata

**Mentor:** Dr. Chandan Biswas

**Internship Duration:** 21 September – 16 October 2026
