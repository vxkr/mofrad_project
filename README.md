# Data Analysis / Machine Learning Methods Guide - Mofrad Lab

By Vyom Thakkar, Sumiran Thakur

Often many machine learning methods are treated as a blackbox, though in many cases certain models fit well while others aren't the appropriate choice. The goal of this guide is to show how a cursory understanding of models and their charecteristics and strengths can allow someone to quickly determine which models are most applicable and which ones aren't suitable to the model at hand. Here we give an introduction to the derivation of each method along with some mathematical intuition behind each process. Alongside each method, we discuss the underlying assumptions and applicable types of data/problems, as well as best practices in evaluating the models and setting hyperparameters. Finally, with application to research in mind, many of the methods also include examples of visualizations. We also contextualize the visuals, with the goal in mind of allowing people to easily refer to the guide for explanations of the methods and the visuals, for ease of use in future research projects in the Mofrad Lab.

## Outline of Methods

### I. Regression
1. Ordinary Least Squares

2. Ridge Regression

3. Weighted Least Squares

4. Total Least Squares

### II. Correlation
1. Principal Component Analysis

      a. Examples
      
2. Canonical Correlation Analysis
      
3. PCA vs CCA Comparison with Multilabel Classification

### III. Classification
1. K Nearest Neighbors

      a. Examples
      
2. K Means

      a. Examples  
      
3. Support Vector Machines Intro with examples

      a. Implementation for SVM
