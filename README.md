# Credit-Scores Dataset

### Attention: Machine Learning Code Section

This dataset pertains to binary classification (0, 1) with class 1 containing roughly 68,000 samples, while class 0 comprises approximately 712,000 samples. The dataset has been partitioned into three distinct segments:

1. **First Part:** This section encompasses 100,000 samples, evenly split with 50,000 samples per class. 70,000 samples were employed for training, and 30,000 samples were reserved for testing. Remarkably, both the training and testing phases yield promising results, with accuracy consistently exceeding 95%.

2. **Second Part:** Comprising 36,000 samples, this section is equally divided between both classes. However, the accuracy when testing on this subset hovers around 65%.

3. **Third Part:** The final section of the dataset comprises a substantial 644,000 samples, all exclusively belonging to class 1. The accuracy achieved on this subset is also approximately 65%.

These accuracy values were obtained through the application of three distinct models:

1. **Random Forest**
2. **Stacking Classifier:** This ensemble model combines Random Forest, Logistic Regression, and AdaBoost.
3. **Deep Learning:** In this case, the accuracy tends to be around 50% when using balanced data, but it can soar as high as 98% when handling unbalanced data.

While the first 30,000 samples yield high accuracy, it's noteworthy that the accuracy drops significantly on other parts of the data. 

Need help

#### Data Link:
[Credit-Scores Dataset on Kaggle](https://www.kaggle.com/datasets/gauravduttakiit/loan-defaulter)

Please feel free to reach out if you have any further questions or require additional information.
