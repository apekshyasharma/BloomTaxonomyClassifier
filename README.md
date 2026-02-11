# Bloom's Taxonomy Classifier 

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![NLP](https://img.shields.io/badge/NLP-Text%20Classification-orange.svg)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Project Overview
The **Bloom's Taxonomy Classifier** is a Natural Language Processing (NLP) tool designed to automatically categorize educational questions or learning objectives into the six levels of Bloom's Taxonomy: **Remember, Understand, Apply, Analyze, Evaluate, and Create**.

This tool helps educators and instructional designers ensure a balanced cognitive challenge in assessments and curriculum design by identifying the depth of knowledge required for various tasks.

---

##  Features
* **Automated Categorization**: Uses machine learning to assign text to cognitive levels.
* **Text Preprocessing**: Includes tokenization, stop-word removal, and lemmatization for optimized text analysis.
* **Multi-Class Classification**: Supports all six hierarchical levels of the Revised Bloom's Taxonomy.
* **Performance Insight**: Evaluates model accuracy using confusion matrices and F1-scores.

---

## Repository Structure
```bash
├── data/                  # Labeled dataset of questions/objectives
├── notebooks/             # EDA and Model Training (Jupyter Notebooks)
├── src/                   # Source code for preprocessing and prediction
├── models/                # Trained model binaries (.pkl, .sav, or .pt)
├── requirements.txt       # Necessary Python libraries
└── README.md              # Project documentation
