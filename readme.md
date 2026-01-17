In this assignment, text data is converted into numerical features using TF-IDF. 

what TF-IDF did ?
- Tokenized text (split into words)
- Built a vocabulary
- Converted each sentence into a vector
- Assigned importance-based weights
- Output a sparse numeric matrix 

Naive Bayes predicts the emotion by calculating the probability of words occurring in each emotion class using Bayes’ theorem, assuming word independence. 

Support Vector Machine treats the TF-IDF vectors as points in a high-dimensional space and finds an optimal hyperplane that separates different emotion classes. 

SVM finds an optimal decision boundary that maximizes the margin between emotion classes, making it robust to noise and overlapping features. That might be the reason for better efficiency.
