# Student_Academic_Performance_Prediction
An attempt at predicting academic performance of a student by accounting for their daily activities. Using sample data, this predicts with accuracy of 0.53
Unlike traditional models which react after the student already failed, this model tracks micro level daily tasks to flag possible decline
## Data pipeline
Fully automated to stream the dataset directly rom a cloud hosted github url for zero setup execution
## Current Model Performance
- *Baseline Accuracy:* 0.5333 (53%)
- *Data Science Insight:* The current 53.33% accuracy indicates that simple median/mode imputation flattens unique behavioral variations among students. Human routines are highly complex and non-linear. Future development phases will require migrating from baseline linear classifications to robust ensemble architectures (like Random Forests) to boost accuracy.
