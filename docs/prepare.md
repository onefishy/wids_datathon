# Preparing for the Workshop
Since the 2021 Datathon workshop will be happening virtually, pedagogical materials addressing the technical background necessary for the Datahon challenge will be delivered through pre-recorded videos and structured notebooks. We've prepared instructional materials with a range of different depths. We ask that participants review the materials that are complementary to their backgrounds before coming to the workshop - depending on your background, you may find that the materials cover concepts with which you are already familiar or you may find that only some of the materials cover concepts that are new to you. The best way to see if you need to brush up on a concept is to take the concept quiz (which follows every topic) or run through the exploratory DeepNote notebooks (which follows every 2-3 topics).

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
2. [Video Walk through of the Global 2021 Starter Code (notebook)](https://youtu.be/znWhRooRjWQ)
2. [The Official WiDS Cambridge 2021 Starter Code (notebook)](https://deepnote.com/project/bb1228b2-8df8-4e09-b078-7b81911b3da5)

**Important:** We ask that all participants work through the [Official WiDS Cambridge 2021 Starter Code](https://www.kaggle.com/usharengaraju/widsdatathon2021-catboost-starter) and the [Official WiDS Cambridge 2021 Starter Code](https://deepnote.com/project/bb1228b2-8df8-4e09-b078-7b81911b3da5) prior to attending the workshop meetings.

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

1. [Topics on Regression](./regression.html)
2. [Topics on Uncertainty, Variance and Bias](./uncertainty.html)
3. [Topics on Classification: Logistic Regression](./logistic.html)
4. [Topics on Classification: Additional Models](./classifier.html)
5. [Topics on Neural Networks for Regression](./nn_regression.html)
6. [Topics on Neural Networks for Classification](./nn_classify.html)
7. [Topics on Transforming and Manipulating Data](./transform.html)
