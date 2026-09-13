# Reddit-STEM-Gender-Analysis-14200811
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

The notebooks folder contains the main analysis:

Reddit data filtering and corpus construction：
1. RC_clean_classify.ipynb
2. RS_clean_classify.ipynb
3. RC_RS_combine.ipynb

LDA topic modelling and topic analysis:
5. topic_modelling.ipynb; 
6. topic_model_validation.ipynb

VADER sentiment analysis:
7. sentiment analysis.ipynb; 
8. topicxsentiment.ipynb  ---(Comparison between submissions and comments)

Analysis of gendered narratives related to STEM careers:
9. RQ3 careers analysis.ipynb
