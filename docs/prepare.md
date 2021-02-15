# Preparing for the Workshop
Since the 2021 Datathon workshop will be happening virtually, pedagogical materials addressing the technical background necessary for the Datahon challenge will be delivered through pre-recorded videos and structured notebooks. We've prepared instructional materials with a range of different depths. We ask that participants review the materials that are complementary to their backgrounds before coming to the workshop.

## About the WiDS 2021 Datathon
This year, participants will work again with the WiDS 2020 Datathon data from MIT’s [GOSSIS (Global Open Source Severity of Illness Score)](https://gossis.mit.edu) dataset. Last year, the challenge was to predict patient survival; this year. the WiDS Datathon will focus on creating classifiers to determine whether patients have a type of diabetes which could potentially inform later treatment in the ICU.

The [WiDS Datathon](https://www.kaggle.com/c/widsdatathon2021) is hosted on Kaggle, an online community of data scientists.

### Resources for Exploring and Understanding the Data
The following are resources for getting started with Kaggle competitions and with working with this year's data:

1. [Getting Started with Kaggle (Video)](https://www.youtube.com/watch?v=4e5bMzUAbDs)
2. [Getting Started with the Datathon Challenge: Diabetes Prediction for ICU Patients (Video)](https://www.youtube.com/watch?v=LuPcDGY3dPI)
3. [An Introduction to Exploratory Data Analysis (Notebook)](https://www.kaggle.com/yubiabia98/visualization-exploratory-data-analysis-light)

The following are starter code for this year's datathon challenge:
1. [WiDS Global 2021 Starter Code (notebook)](https://www.kaggle.com/usharengaraju/widsdatathon2021-catboost-starter)
2. [The Official WiDS Cambridge 2021 Starter Code (notebook)](https://deepnote.com/project/bb1228b2-8df8-4e09-b078-7b81911b3da5)

**Important:** We ask that all participants work through the [Official WiDS Cambridge 2021 Starter Code](https://deepnote.com/project/bb1228b2-8df8-4e09-b078-7b81911b3da5) prior to attending the workshop meetings.

## Technical Background for the Datathon Challenge

### I. Programming
It would be helpful for participants to have some familiarity in `python` programming. You can familiarize yourself with `python` by completing online tutorials, for example: [https://www.learnpython.org](https://www.learnpython.org). In particular, it's helpful for participants to be able to manipulate data using `pandas` `DataFrames`, perform basic operations with `numpy` Arrays and make use of basic plotting functions (e.g. line chart, histogram, scatter plot, bar chart) from `matplotlib`:
1. [`pandas` Basics](https://www.learnpython.org/en/Pandas_Basics)
2. [`numpy` Basics](https://cs231n.github.io/python-numpy-tutorial/)
3. [`matplotlib` Basics](https://www.datacamp.com/community/tutorials/matplotlib-tutorial-python)

For this workshop, we will be using [DeepNote](https://deepnote.com/) - a free cloud computing service that comes with pre-installed machine learning tools. Deepnote allows you to easily work on your data science projects, together in real-time and in one place with your friends and colleagues. It allows you to create and share documents that contain live code, equations, visualizations and narrative text. You can familiarize yourself with the interface of DeepNote notebooks by reading the following tutorials (remember you don't need to install anything!):

1. [Deepnote: the modern way to teach Data Science](https://medium.com/@robertlacok/deepnote-the-modern-way-to-teach-data-science-99998ce659a)
2. [Deepnote: Documentation](https://docs.deepnote.com/)

Finally, we will be working with random variables in this workshop and will be reasoning about them through their distributions. But we'll only need a bit of familiarity with these concepts:

1. [Probability distributions in python](https://www.datacamp.com/community/tutorials/probability-distributions-python)

#### Skills Check for Participants
You might find the following Deepnote notebook useful to get a sense of the types of computational tasks that we will be using during the workshop

[Introduction to Deepnote Notebook and `python` Libraries for Data Science](https://deepnote.com/project/92d5bb62-1707-4095-b837-794234097fd6)

**Instructions:** 
1. Open the notebook,  under the drop-down menu by the name of the project, `0-preparing-for-the-workshop`, choose to Duplicate the project. The copy will open in the same tab.
2. If you want to share your work with others: under 'Share' (upper right-hand side of your screen), change the permissions to "Public access: On" and share the link, or invite specific collaborators.

### Machine Learning
The materials will be broken down into
a sequence of bite-sized concepts. Each concept will be introduced in a short 10-20 minute video; following each video, there
will be a short concept-check quiz for the viewer to test their understanding. For each topic, we have selected some supplementary readings that may be helpful. After two or three topics there will be an DeepNote notebook with starter code and experiments to help you further explore these topics. 

These materials are taken from [DSC6232 Machine Learning and Computational Statistics](https://onefishy.github.io/Rwanda-Data-Science/), an intensive summer data science course run by IACS and the University of Rwanda. You can find the complete set of lecture materials on the [course website](https://onefishy.github.io/Rwanda-Data-Science/). 

#### **Topic 1:** Introduction to Machine Learning and Data Science

- **Lecture Video:** <br>
[![Alt text](https://img.youtube.com/vi/UyzUQSSmlKY/0.jpg)](https://youtu.be/UyzUQSSmlKY)<br>
(12:23 minutes)

- **Lecture Slides:** [Slides](https://drive.google.com/file/d/1cR8COSU8DB7S8dJsbHc68rDN-EXUezI_/view?usp=sharing)

#### **Topic 2:** Linear Regression

- **Lecture Video:** <br>
[![Alt text](https://img.youtube.com/vi/OCuR5p7gWlg/0.jpg)](https://youtu.be/OCuR5p7gWlg)<br> 
(23:58 minutes)
- **Lecture Slides:** [Slides](https://drive.google.com/file/d/1YkXHgzs5OJ3SPwmz18X7I6bmqjoIwG02/view?usp=sharing)
- **References:** 
  - [Linear Regression Using Python](https://towardsdatascience.com/linear-regression-using-python-b136c91bf0a2)
- **Concept Quiz:** [Quiz](https://docs.google.com/forms/d/e/1FAIpQLScZs9MGFWR8D7ond4yNjBqDbLR7nQcl1MqWsSLr5soK3NwgYA/viewform?usp=sf_link)

#### **Topic 3:** Multi-Linear and Polynomial Regression

- **Lecture Video:**  <br>
[![Alt text](https://img.youtube.com/vi/MnfjfarIklQ/0.jpg)](https://youtu.be/MnfjfarIklQ)  <br>
(12:23 minutes)

- **Lecture Slides:** [Slides](https://drive.google.com/file/d/1XrREBhCfHh7JzWijr0HEJtNS_9tfLX5O/view?usp=sharing)
  
- **References:** 
  - [Polynomial Regression in Python](https://towardsdatascience.com/polynomial-regression-bbe8b9d97491)
  - [Overfitting vs Underfitting](https://towardsdatascience.com/overfitting-vs-underfitting-a-complete-example-d05dd7e19765)
  - [Train Test Split](https://towardsdatascience.com/train-test-split-and-cross-validation-in-python-80b61beca4b6)

- **Exploratory Notebooks:**
  - [Linear and Polynomial Regression](https://deepnote.com/project/49b24b4a-576e-42d4-a435-25c4392617a6)
  
#### **Topic 4:**  Confidence and Prediction Intervals
- **Lecture Video:** <br>
[![Alt text](https://img.youtube.com/vi/0k0DfJro5I8/0.jpg)](https://youtu.be/0k0DfJro5I8) <br>
(11:15 minutes)

- **Lecture Slides:** [Slides](https://drive.google.com/file/d/1hmBOt5lOv1Aksgy2CmoG1XvZDgZOUaq0/view?usp=sharing)
- **References:** 
  - [Bootstrap Confidence Intervals](https://ocw.mit.edu/courses/mathematics/18-05-introduction-to-probability-and-statistics-spring-2014/readings/MIT18_05S14_Reading24.pdf)
  - [Bootstrapping for Linear Regression](https://www.textbook.ds100.org/ch/18/hyp_regression.html)
  - [Prediction Interval, the Wider Sister of Confidence Interval](https://datascienceplus.com/prediction-interval-the-wider-sister-of-confidence-interval/)
- **Concept Quiz:** [Quiz](https://docs.google.com/forms/d/e/1FAIpQLSdzgyPK5EIncWJsFsvtae4azgu3ILTmFy8zeri4zVrEOI8yww/viewform?usp=sf_link)  
  
#### **Topic 5:**  Bias versus Variance
- **Lecture Video:** <br>
[![Alt text](https://img.youtube.com/vi/eTOxnGIiA6k/0.jpg)](https://youtu.be/eTOxnGIiA6k) <br>
(10:45 minutes)

- **Lecture Slides:** [Slides](https://drive.google.com/file/d/1wVMVJ7rU0HjD_DCOP_yjPZcqJCPeA1Gm/view?usp=sharing)
- **References:** 
  - [Understanding the Bias Variance Trade-off](https://towardsdatascience.com/understanding-the-bias-variance-tradeoff-and-visualizing-it-with-example-and-python-code-7af2681a10a7)
  - [Overfitting and Underfitting with Machine Learning Algorithms](https://machinelearningmastery.com/overfitting-and-underfitting-with-machine-learning-algorithms/)
- **Concept Quiz:** [Quiz](https://docs.google.com/forms/d/e/1FAIpQLSd8Lqy2yU60_jQgVMdTprucIAS4eg7_Y3FoIc8wkx-v7LLmqg/viewform?usp=sf_link) 
  
#### **Topic 6:**  Variance Reduction
- **Lecture Video:** <br>
[![Alt text](https://img.youtube.com/vi/zfQJ7uTFhIw/0.jpg)](https://youtu.be/zfQJ7uTFhIw) <br>
(7:35 minutes)

- **Lecture Slides:** [Slides](https://drive.google.com/file/d/1yGiYhbXEjdyUsjtXLa1-M0zyBr4fr1Fd/view?usp=sharing)
- **References:** 
  - [Regularization](https://towardsdatascience.com/ridge-and-lasso-regression-a-complete-guide-with-python-scikit-learn-e20e34bcbf0b)
  - [Bagging](https://towardsdatascience.com/a-guide-to-ensemble-learning-d3686c9bed9a)
  
- **Concept Quiz:** [Quiz](https://docs.google.com/forms/d/e/1FAIpQLSfDUYEIELn8Fnq6qjZgcAEqfbU6IXu0F9TPC_eH3fSNHZFV9Q/viewform?usp=sf_link)
- **Exploratory Notebooks:** [Generalization and Uncertainty](https://deepnote.com/project/1163d467-eac1-4050-a6cd-e7900d87eaaa)

#### **Topic 7:** Models for Classification

- **Lecture Video:** <br>
[![Alt text](https://img.youtube.com/vi/5Bv4GB6f6e8/0.jpg)](https://youtu.be/5Bv4GB6f6e8) <br>
(8:02 minutes)

- **Lecture Slides:** [Slides](https://drive.google.com/file/d/1aq6fj3Gv5wW31j9GN1y5u6-7JrGBi7lk/view?usp=sharing)
- **References:** 
  - [Understanding Logistic Regression in Python](https://www.datacamp.com/community/tutorials/understanding-logistic-regression-python)
  
- **Concept Quiz:** [Quiz](https://docs.google.com/forms/d/e/1FAIpQLSdAKzqIyvtUTpI0XxUGd--umW-7nXbXIwx6JWlD4IOD7bBZig/viewform?usp=sf_link)
  
#### **Topic 8:** Gradient Descent

- **Lecture Video:** <br>
[![Alt text](https://img.youtube.com/vi/DxT29iy6rOo/0.jpg)](https://youtu.be/DxT29iy6rOo) <br>
(9:45 minutes)

- **Lecture Slides:** [Slides](https://drive.google.com/file/d/1EVGhfpPU_tl1EuI0XkZRfvCO89FqLmLE/view?usp=sharing)
- **References:** 
  - [Understanding the Mathematics behind Gradient Descent](https://towardsdatascience.com/understanding-the-mathematics-behind-gradient-descent-dde5dc9be06e)
- **Concept Quiz:** [Quiz](https://docs.google.com/forms/d/e/1FAIpQLSdVrZMtU6-4C9ml6O3x2geQMqXv8ACY8yoSxy_5JgZa9dQWig/viewform?usp=sf_link)

#### **Topic 9:** Evaluating and Interpreting Classifiers

- **Lecture Video:** <br>
[![Alt text](https://img.youtube.com/vi/UZTf43p3ejE/0.jpg)](https://youtu.be/UZTf43p3ejE) <br>
(7:50 minutes)

- **Lecture Slides:** [Slides](https://drive.google.com/file/d/1UNFyt42euWHJ_3bE5uhfLv04yThag9_2/view?usp=sharing)
- **References:** 
  - [Interpreting the Imapact Size of Logistic Regression Coefficients](https://medium.com/ro-data-team-blog/interpret-the-impact-size-with-logistic-regression-coefficients-5eec21baaac8)
- **Concept Quiz:** [Quiz](https://docs.google.com/forms/d/e/1FAIpQLSdBE5V-_xHRbxAdoI564IY3T4OFyoFSBTeosq7y5PdSa0wX2w/viewform?usp=sf_link)
- **Exploratory Notebooks:** [Notebook on Classification](https://deepnote.com/project/8f461b17-dac5-4061-ac40-1437b36c846a)

#### **Topic 10:** Non-Probabilistic Models for Classification

- **Lecture Video:** <br>
[![Alt text](https://img.youtube.com/vi/TPiSr1wbUtg/0.jpg)](https://youtu.be/TPiSr1wbUtg) <br>
(9:45 minutes)

- **Lecture Slides:** [Slides](https://drive.google.com/file/d/1taP00yHX7aLVDwMNBkrnBWd3IMimERVi/view?usp=sharing)
- **References:** 
  - [Decision Trees in Machine Learning](https://towardsdatascience.com/decision-trees-in-machine-learning-641b9c4e8052)
  - [The Simple Math Behind 3 Decision Tree Splitting Criterions](https://towardsdatascience.com/the-simple-math-behind-3-decision-tree-splitting-criterions-85d4de2a75fe)
  - [Machine Learning Basics with the KNN Algorithms](https://towardsdatascience.com/machine-learning-basics-with-the-k-nearest-neighbors-algorithm-6a6e71d01761)
- **Concept Quiz:** [Quiz](https://docs.google.com/forms/d/e/1FAIpQLScU_kxRK5uNThepAtAf52Yhreg2FZMaiolSbV612bbssJr1Gg/viewform?usp=sf_link)
    
#### **Topic 11:**  Hyper-parameter Selection and Variance Reduction

- **Lecture Video:** <br>
[![Alt text](https://img.youtube.com/vi/5lBjG8tJubM/0.jpg)](https://youtu.be/5lBjG8tJubM) <br>
(9:42 minutes)
- **Lecture Slides:** [Slides](https://drive.google.com/file/d/14W13NJCXSVH1pl6Xx_Yj7Ybwp1wzXAQR/view?usp=sharing)
- **References:** 
  - [A Gentle Introduction to K-fold Cross Validation](https://machinelearningmastery.com/k-fold-cross-validation/)
  - [Understanding Random Forest](https://towardsdatascience.com/understanding-random-forest-58381e0602d2)
- **Concept Quiz:** [Quiz](https://docs.google.com/forms/d/e/1FAIpQLScTtjpHg4svVZ6DETiyW9gaHghrTg63wSOyjWzrFkd-AAtEtQ/viewform?usp=sf_link)
    
#### **Topic 12:** Evaluating Classifiers

- **Lecture Video:** <br>
[![Alt text](https://img.youtube.com/vi/vJFnbAsmZaE/0.jpg)](https://youtu.be/vJFnbAsmZaE) <br>
(14:46 minutes)

- **Lecture Slides:** [Slides](https://drive.google.com/file/d/1oTrqQw0doU3kwj_zofU1GBfV_-hE07xf/view?usp=sharing)
  
- **References:** 
  - [Handling imbalanced datasets in machine learning](https://towardsdatascience.com/handling-imbalanced-datasets-in-machine-learning-7a0e84220f28)
  - [20 Popular Machine Learning Metrics](https://towardsdatascience.com/20-popular-machine-learning-metrics-part-1-classification-regression-evaluation-metrics-1ca3e282a2ce)  
- **Concept Quiz:** [Quiz](https://docs.google.com/forms/d/e/1FAIpQLSe6yDU-_h_hsxEdZeV6d8boYE5DuXzzFs7-jjave0Exh-AEBQ/viewform?usp=sf_link)
- **Exploratory Notebooks:** [Non Probabilistic Classifiers and Model Evaluation](https://deepnote.com/project/aa4ceb92-4323-4985-bc06-aa8df6ee45ca)


#### **Topic 13:** Neural Networks for Regression

- **Lecture Video:** <br>
[![Alt text](https://img.youtube.com/vi/_XWdu5ip4n4/0.jpg)](https://youtu.be/_XWdu5ip4n4) <br>
(14:28 minutes)
- **Lecture Slides:** [Slides](https://drive.google.com/file/d/1-oDJEzReIyNsmakv6LtS0dP27tmU3V1v/view?usp=sharing)
- **References:** 
  - [The Math behind Artificial Neural Networks](https://towardsdatascience.com/the-heart-of-artificial-neural-networks-26627e8c03ba)
  - [Deep Learning: An Introduction for Applied Mathematicians](https://arxiv.org/pdf/1801.05894.pdf)
- **Concept Quiz:** [Quiz](https://docs.google.com/forms/d/e/1FAIpQLSd7Ynz47sC_1_EHdSp1IusBF2Ulo5hdTZt-S2xfNVQhYMLmCw/viewform?usp=sf_link)

#### **Topic 14:** Optimizing Neural Networks

- **Lecture Video:** <br>
[![Alt text](https://img.youtube.com/vi/wabJS4Nkxeg/0.jpg)](https://youtu.be/wabJS4Nkxeg) <br>
(6:17 minutes)

- **Lecture Slides:** [Slides](https://drive.google.com/file/d/1JqUUfqj81ioExFhyTwBw8HYpbj__7uMF/view?usp=sharing)
- **References:** 
  - [Gradient Descent Algorithm and Its Variants](https://towardsdatascience.com/gradient-descent-algorithm-and-its-variants-10f652806a3)
- **Concept Quiz:** [Quiz](https://docs.google.com/forms/d/e/1FAIpQLSd3z0gXS7ep0CTjmsTGUXf5rsbAW-gfuMwJtVcj7qB-fFAXAQ/viewform?usp=sf_link)

#### **Topic 15:** Implementing Neural Networks in `keras`
- **Lecture Video:** <br>
[![Alt text](https://img.youtube.com/vi/sbg9y4L1sKo/0.jpg)](https://youtu.be/sbg9y4L1sKo) <br>
(6:13 minutes)

- **Lecture Slides:** [Slides](https://drive.google.com/file/d/1OsENAg2OdIVoJwE50g6Q37i_msEZxRzC/view?usp=sharing)
- **References:** 
  - [Building Neural Network using keras for Regression](https://medium.com/datadriveninvestor/building-neural-network-using-keras-for-regression-ceee5a9eadff)
- **Concept Quiz:** [Quiz](https://docs.google.com/forms/d/e/1FAIpQLSdJvWwrhGIpQJv6AbIdLkPW0Y2BRTJ944MYhgyzoQLfIshdqQ/viewform?usp=sf_link)
- **Exploratory Notebooks:** [Neural Networks for Regression](https://deepnote.com/project/523bbc1e-4b14-424b-917a-c39eced4f667)

#### **Topic 16:**  Neural Networks for Classification
- **Lecture Video:** <br>
[![Alt text](https://img.youtube.com/vi/2xyFziFxqys/0.jpg)](https://youtu.be/2xyFziFxqys) <br>
(6:39 minutes)

- **Lecture Slides:** [Slides](https://drive.google.com/file/d/1zlxz605k9Ge-SDcr9i2McN7sZiGtXjJ0/view?usp=sharing)
- **References:** 
  - [Building our first neural network in keras](https://towardsdatascience.com/building-our-first-neural-network-in-keras-bdc8abbc17f5)
- **Concept Quiz:** [Quiz](https://docs.google.com/forms/d/e/1FAIpQLSc3IULZB3DpHRhnh_5yT6Rgt7fO5xonwLCccUfyjMKWvHN7dw/viewform?usp=sf_link)
  
#### **Topic 17:**  Interpreting Neural Networks
- **Lecture Video:** <br>
[![Alt text](https://img.youtube.com/vi/iTdhBhvEa0g/0.jpg)](https://youtu.be/iTdhBhvEa0g) <br>
(7:56 minutes)

- **Lecture Slides:** [Slides](https://drive.google.com/file/d/1xRGszrVXXdtpJiur2yL9-mQKH2y63ia9/view?usp=sharing)
- **References:** 
  - [Interpretable Neural Networks](https://towardsdatascience.com/interpretable-neural-networks-45ac8aa91411)
  - [The Mythos of Model Interpretability](https://arxiv.org/pdf/1606.03490.pdf)
  - [Towards A Rigorous Science of Interpretable Machine Learning](https://arxiv.org/pdf/1702.08608.pdf)
  - [Interpretable Machine Learning](https://christophm.github.io/interpretable-ml-book/)
- **Concept Quiz:** [Quiz](https://docs.google.com/forms/d/e/1FAIpQLSduOiRxej0nPsLk3Zc-0XPGqjiEzQN2OXnh7SHHFpa60eSvfQ/viewform?usp=sf_link)
  
#### **Topic 18:**  Regularization for Neural Networks
- **Lecture Video:** <br>
[![Alt text](https://img.youtube.com/vi/kIpkiFxjd-A/0.jpg)](https://youtu.be/kIpkiFxjd-A) <br>
(5:09 minutes)

- **Lecture Slides:** [Slides](https://drive.google.com/file/d/1WcCm8DBUHQ8NLYKNFg5YPPRXR4bExGyw/view?usp=sharing)
- **References:** 
  - [A Quick Guide on Basic Regularization Methods for Neural Networks](https://medium.com/yottabytes/a-quick-guide-on-basic-regularization-methods-for-neural-networks-e10feb101328)
  - [L1 and L2 Regularization](https://towardsdatascience.com/l1-and-l2-regularization-methods-ce25e7fc831c)
- **Concept Quiz:** [Quiz](https://docs.google.com/forms/d/e/1FAIpQLSfXWRXSTJNsKSg4e0CLXsc9YqyfuuJZunKGtSEkE9_Cu-VSug/viewform?usp=sf_link)
- **Exploratory Notebooks:** [Neural Networks for Classification](https://deepnote.com/project/89d5670d-7b6d-418f-ba40-d044773a4988)
