
**AI Internship Test**
Language: Python
Allowed: Open-source libraries (NumPy, pandas, scikit-learn, TensorFlow, PyTorch,
matplotlib, seaborn).

**Section A: Python & Data Manipulation**

**Q1. Data Cleanup & Summary**

You are given a CSV file: student_scores.csv with columns:
Name, Math, Science, English, Gender
Write a function that:
• Fills any missing numeric values with the mean of the column.
• Converts Gender into binary values.
• Returns a summary DataFrame showing average scores per gender.

**Q2. Dictionary-Based Stats**

Write a function that takes a dictionary of the form:
{
"user_1": [80, 90, 85],
"user_2": [60, 65, 70],
...
}
And returns a new dictionary with each user’s:
• Average score
• Min score
• Max score
Section B: Machine Learning

**Q3. Classifier on Iris**

• Load the Iris dataset from sklearn.datasets.
• Train a Decision Tree classifier.
• Split the data (80-20).
• Predict and print accuracy on the test set.
• Plot a confusion matrix using matplotlib or seaborn.

**Q4. Simple Regression**

You are given a CSV simple_housing.csv with:
area, bedrooms, price
Build a linear regression model:
• Predict price using the other columns.
• Evaluate it using Mean Absolute Error (MAE).
• Plot actual vs. predicted prices on a scatter plot

**Section C: AI/ML Application & Thinking**

**Q5. Conceptual**

Answer the following briefly (1-2 sentences each):
1. What is overfitting in machine learning?
2. When would you use a decision tree over logistic regression?
3. Explain the train-test split and why it’s important.
4. What’s the purpose of normalization?
5. What’s the difference between classification and regression?

**Q6. Simple NLP Task – Sentiment Classification**

Use the built-in sklearn.datasets.fetch_20newsgroups:
• Load only two categories: rec.autos and comp.sys.mac.hardware
• Use TfidfVectorizer to convert text to vectors.
• Train a Logistic Regression classifier to predict the category.
• Print accuracy and show 5 most important words per class.
