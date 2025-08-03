# 14.-Quora-Duplicate-Question-Pairs-detection

🧠 Today's Focus:
Today, I tackled a real problem from platforms like Quora, where identical questions are asked with different wording. This causes answers to get scattered, making it harder for users to find complete or high-quality responses in one place.

To solve this, I created a model that can predict whether two questions have the same contextual meaning, regardless of how they’re phrased.

📌 What Makes This Project Stand Out:
✅ At first, I was unsure how to make the model understand meaning beyond just words
✅ Then I used Bag of Words to convert the questions into vector form
✅ Trained classifiers like XGBoost and Decision Tree to detect if two questions are duplicates based on those features
✅ The model predicts whether the pair should be merged or treated as separate

🔍 How It Works:
✅ Cleaned and tokenized question pairs
✅ Converted text to numerical form using BoW
✅ Trained models for binary classification: Duplicate or Not Duplicate

📈 Tech Stack:
Python | Scikit-learn | XGBoost | NLTK | Pandas | Streamlit

🌐 Use Case Impact:
This solution can significantly improve Q&A platforms by grouping duplicate questions, leading to better answer visibility and improved user experience.



#QuoraDuplicateQuestionDetector #DuplicateDetection #XGBoost #DecisionTree
#BagOfWords #MachineLearning #NLP #PythonProjects #AIProjects
#TextClassification #DataScience #MLChallenge #QuestionSimilarity
