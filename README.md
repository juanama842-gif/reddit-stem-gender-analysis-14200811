# reddit-stem-gender-analysis-14200811
Code and dataset for MSc dissertation on gendered narratives of STEM fields on Reddit
The number after each .ipynb file is the order for running.
Gendered Narratives of STEM Fields on Reddit

This repository contains the Python code used for my MSc dissertation, "Gendered Narratives of STEM Fields on Reddit: A Computational Analysis of Online Discussions."

# Project Overview

This study examines how gender and STEM are discussed on Reddit. It focuses on the main gendered narratives, sentiment patterns, differences between submissions and comments, and gendered discussions related to STEM careers.

# Methods

The analysis includes:

Keyword-based data filtering
Text preprocessing
Latent Dirichlet Allocation (LDA) topic modelling
VADER sentiment analysis
Chi-square tests
Career-related keyword and co-occurrence analysis
Repository Structure

The notebooks folder contains the main analysis：
Ⅰ：Reddit data filtering and corpus construction：
1. RC_clean_classify.ipynb
2. RS_clean_classify.ipynb
3. RC_RS_combine.ipynb
Ⅱ：LDA topic modelling and topic analysis
4. topic_modelling.ipynb
5. topic_model_validation.ipynb
Ⅲ：VADER sentiment analysis
6. sentiment analysis.ipynb
7. topicxsentiment.ipynb  ---(Comparison between submissions and comments)
Ⅳ： Analysis of gendered narratives related to STEM careers
8. RQ3 careers analysis.ipynb
