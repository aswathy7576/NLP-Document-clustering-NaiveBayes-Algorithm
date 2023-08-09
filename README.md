# NLP-Document-clustering-NaiveBayes-Algorithm



Table of contents

    Introduction
    The Naive Bayes algorithm
    Dealing with text data
    Working Example in Python (step-by-step guide)
    Bonus: Having fun with the model
    Conclusions

1. Introduction

Naive Bayes classifiers are a collection of classification algorithms based on Bayes’ Theorem. It is not a single algorithm but a family of algorithms where all of them share a common principle, i.e. every pair of features being classified is independent of each other.

Naive Bayes classifiers have been heavily used for text classification and text analysis machine learning problems.

Text Analysis is a major application field for machine learning algorithms. However the raw data, a sequence of symbols (i.e. strings) cannot be fed directly to the algorithms themselves as most of them expect numerical feature vectors with a fixed size rather than the raw text documents with variable length.

In this article I explain a) how Naive Bayes works, b) how we can use text data and fit them into a model after transforming them into a more appropriate form. Finally, I implement a multi-class text classification problem step-by-step in Python.

Let’s get started !!!

