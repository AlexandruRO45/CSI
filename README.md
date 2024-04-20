## Laughter Event Analysis and Facial Expression Classification

This project investigates two facets of human communication: laughter in phone conversations and facial expression classification.

### Part 1: Laughter Event Analysis

*Analyzes laughter events in a dataset of 60 phone conversations involving 120 participants.*

**Research Questions:**

1. **Do women laugh more than men during phone conversations?**
2. **Do callers laugh more than receivers?**
3. **Are laughter events longer for women?**
4. **Are laughter events longer for callers?**

**Methodology:**

* Employed Chi-Square Goodness-of-Fit test to compare observed laughter frequencies against expected frequencies based on gender and conversation role.
* Utilized Student's t-test to compare the means and standard deviations of laughter duration between genders and conversation roles.

**Key Findings:**

* Women laughed more frequently and for longer durations than men during phone conversations.
* Callers tended to laugh more frequently and for longer periods than receivers.

### Part 2: Facial Expression Classification

*Develop a classifier to distinguish between smiles and frowns using Gaussian Discriminant Analysis (GDA).*

**Methodology:**

* Leveraged a dataset of 52 feature vectors representing activation levels of 17 Action Units (AUs) associated with smiles and frowns.
* Trained the GDA classifier on half of the data (26 instances each of smiles and frowns) to estimate the parameters of the Gaussian models.
* Classified the remaining data (16 instances) and assessed the performance based on error rate.

**Results:**

* Achieved an error rate of 12.5%, indicating that the classifier incorrectly classified 2 out of 16 instances.
* Misclassifications were not biased towards a specific class (smile or frown).
* Overlapping feature value distributions for some AUs may have contributed to errors.

**Conclusion:**

* This project demonstrates the potential of GDA for facial expression classification.
* Further research could explore feature engineering and more complex models to improve classification accuracy.

**Accompanying this repository is a Jupyter Notebook containing the code for the analysis and classification and a detailed report about terminologies and theoretical expressions used.**
