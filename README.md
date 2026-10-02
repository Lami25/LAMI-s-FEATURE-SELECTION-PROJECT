# LAMI-s-FEATURE-SELECTION-PROJECT
I worked on the replication of codes from some Feature Selection study resources I got access to. Check it out.


# Student Resource 3

## Description

> **Student Resources contained two study materials on Feature Selection which I studied, replicated and documented. Check it out below.**

---

## About the Project

**Student Resource 3** is a learning resource centered on **Feature Selection in Machine Learning**. It examines why feature selection is important, how relevant variables can be identified, and the different techniques that can be used to reduce unnecessary features in a dataset.

The project is organized into **Version 1** and **Version 2**. While both versions focus on Feature Selection, they approach the subject from different angles. Version 1 introduces several individual feature selection techniques, while Version 2 expands the discussion by categorizing feature selection approaches and examining their strengths and limitations.

---

# Version 1 — Introduction to Feature Selection

## What It Covers

Version 1 establishes the foundation for understanding Feature Selection in machine learning. It explains why using every available feature may not always be beneficial and introduces methods for identifying variables that are more useful to a model.

The version also considers how the nature of the input and target variables influences the statistical method used during feature selection.

### Main Areas Covered

* Features and their role in machine learning
* Definition and purpose of Feature Selection
* Reasons for removing unnecessary features
* Feature Selection and model performance
* Curse of Dimensionality
* Computational efficiency
* Variance Threshold
* K-Best feature selection
* Statistical approaches to feature selection
* Recursive Feature Elimination (RFE)
* Boruta Feature Selection
* Feature importance
* Shadow features
* Categorical and numerical variables
* Selecting features before model and hyperparameter tuning
* Avoiding unnecessary features and data leakage

### Techniques Studied

**Variance Threshold**

This approach examines how much a feature varies within the dataset. A feature with no variation, or extremely little variation, may not provide useful information for a predictive model.

**K-Best Feature Selection**

K-Best identifies a specified number of features based on their statistical relevance to the machine learning task. The scoring technique used depends on the types of the input and target variables.

**Recursive Feature Elimination (RFE)**

RFE repeatedly evaluates feature importance using a machine learning estimator and removes less important variables until the required number of features remains.

**Boruta**

Boruta evaluates the relevance of original features by comparing their importance against randomized **shadow features**. Features that demonstrate sufficient importance can be retained while weaker features are eliminated.

---

# Version 2 — Feature Selection Methods

## What It Covers

Version 2 builds upon the foundation established in Version 1 by providing a broader classification of Feature Selection techniques.

It introduces **Supervised and Unsupervised Feature Selection** and examines three major supervised approaches: **Filter, Wrapper, and Embedded Methods**.

The version also looks at the advantages and limitations associated with the different approaches.

### Main Areas Covered

* Purpose of Feature Selection
* Definition of Feature Selection
* Benefits of reducing unnecessary features
* Curse of Dimensionality
* Computational requirements
* Feature Selection statistics
* Categorical and numerical variables
* Supervised Feature Selection
* Unsupervised Feature Selection
* Filter Methods
* Wrapper Methods
* Embedded Methods
* Strengths and limitations of different approaches

### Techniques Studied

#### Filter Techniques

Filter methods assess features using statistical or mathematical properties of the dataset rather than directly depending on a machine learning model.

The techniques explored include:

* Information Gain
* Chi-Squared Test
* Fisher's Score
* Missing Value Ratio

#### Wrapper Techniques

Wrapper methods use a machine learning model to evaluate different feature subsets and determine which combination produces useful model results.

The techniques covered include:

* Forward Selection
* Backward Selection
* Exhaustive Feature Selection
* Recursive Feature Elimination (RFE)

#### Embedded Techniques

Embedded methods incorporate feature selection into the model-training process itself.

The techniques explored include:

* L1 Regularization / Lasso
* L2 Regularization / Ridge
* Elastic Net
* Decision Tree-based techniques
* Random Forest-based techniques

---

# Combined Topics and Techniques

Across both versions, the project covers several important areas of Feature Selection:

| Category                   | Topics / Techniques                                                       |
| -------------------------- | ------------------------------------------------------------------------- |
| **Fundamentals**           | Features, Feature Selection, relevance of features                        |
| **Dimensionality**         | Curse of Dimensionality                                                   |
| **Statistical Techniques** | Variance Threshold, K-Best, Information Gain, Chi-Squared, Fisher's Score |
| **Missing Data**           | Missing Value Ratio                                                       |
| **Model-Based Techniques** | RFE, Wrapper Methods                                                      |
| **Automated Selection**    | Boruta, Shadow Features                                                   |
| **Sequential Approaches**  | Forward Selection, Backward Selection                                     |
| **Subset Evaluation**      | Exhaustive Feature Selection                                              |
| **Regularization**         | Lasso, Ridge, Elastic Net                                                 |
| **Tree-Based Methods**     | Decision Trees, Random Forests                                            |
| **Selection Categories**   | Supervised and Unsupervised Feature Selection                             |
| **Variable Types**         | Categorical and Numerical Inputs and Outputs                              |

---

# Repository Structure & Navigation

> **Add your repository navigation guide here.**

Use this section to explain how the repository is organized and how someone should move through the files.

You can include information such as:

* The location of Version 1
* The location of Version 2
* The purpose of each notebook, script, dataset, or documentation file
* The recommended sequence for studying the materials
* Any supporting resources included in the repository

---

# Key Learning Points

## Version 1 Takeaways

Version 1 demonstrates that:

* Having more features does not automatically result in a better machine learning model.
* Feature Selection can help identify variables that are more useful for prediction.
* Eliminating unnecessary features can reduce computational requirements.
* The appropriate statistical technique depends on the types of the input and target variables.
* **Variance Threshold** can remove features with insufficient variation.
* **K-Best** can be used to retain a predetermined number of highly relevant features.
* **RFE** progressively removes less important features using model-based importance.
* **Boruta** uses shadow features as a reference for assessing the importance of original features.

## Version 2 Takeaways

Version 2 highlights that:

* Feature Selection can be performed using either **Supervised or Unsupervised** approaches.
* Supervised techniques make use of the target variable, while unsupervised techniques do not require one.
* **Filter methods** primarily rely on statistical characteristics of the data.
* **Wrapper methods** use a machine learning model to assess feature subsets.
* **Embedded methods** carry out feature selection as part of model training.
* Filter approaches are generally efficient and scalable but may not account for how features interact with a particular model.
* Wrapper approaches are more closely linked to model performance but can require substantial computational resources.
* Embedded techniques provide an approach where feature selection is integrated into the learning algorithm.

---

# Overall Learning Outcome

After working through both versions, the learner should have a stronger understanding of **how and why features are selected in machine learning**.

The resources provide exposure to statistical, model-based, and training-integrated approaches for determining which variables should remain in a dataset.

More importantly, the project demonstrates that Feature Selection is not simply about reducing the number of columns. The objective is to create a **more relevant feature set** by retaining variables that can provide meaningful information for the machine learning task.

---

# Final Summary

**Student Resource 3** provides a progressive study of **Feature Selection in Machine Learning**.

**Version 1** focuses on introducing the concept and exploring specific techniques such as Variance Threshold, K-Best, RFE, and Boruta.

**Version 2** takes a broader methodological approach by introducing Supervised and Unsupervised Feature Selection and examining Filter, Wrapper, and Embedded methods alongside their respective techniques, advantages, and limitations.

Together, the two versions provide a foundation for understanding how feature selection can be incorporated into the machine learning workflow and how different approaches can be chosen depending on the characteristics of the data and the modeling task.
