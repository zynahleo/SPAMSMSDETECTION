# SPAMSMSDETECTION
Within the spam email dataset, this Python code segment executes text classification utilizing Support Vector Machines (SVM). Initially, it loads the dataset and conducts preliminary data cleaning tasks, such as eliminating redundant columns and outliers based on text length.

Further preprocessing involves removing stopwords, tokenizing, and lemmatizing words to refine the text data. Following this preprocessing step, text features are transformed into TF-IDF vectors utilizing the TfidfVectorizer from scikit-learn. The target variable undergoes label encoding.

Subsequently, the dataset undergoes division into training and testing sets, where a linear SVM model is trained using the training data. Classification metrics including accuracy, precision, recall, F1 score, and area under the ROC curve (AUC) are employed to evaluate model performance on the testing data.

To evaluate the SVM model's capacity to discern between spam and non-spam email reports, a classification table and ROC curve are presented. The model demonstrates an accuracy of approximately 98.29% for both categories, accompanied by favorable precision and recall values.
