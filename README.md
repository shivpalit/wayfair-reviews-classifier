# Wayfair Reviews Product Category and Sentiment Classifier

## Project Overview
This project, developed as part of the Information Retrieval course in the M.S. in Data Science program at Johns Hopkins University, implements machine learning techniques to classify customer reviews by product category and sentiment. The study utilizes Amazon product reviews data across 10 product categories, exploring the effectiveness of different feature engineering approaches and classification models.

*For detailed methodology and results, please refer to the project paper: `project_paper.pdf`*

## Key Features & Methodology
- **Feature Engineering**:
  - TF-IDF and n-gram based feature generation
  - Comparative analysis with and without Part-of-Speech (POS) tagging
  - Feature selection using Chi-squared analysis
  
- **Classification Models**:
  - Support Vector Machines (SVMs)
  - Feed-forward Neural Networks with attention mechanisms
  - Top-K accuracy analysis for category classification

## Key Findings
- Neural Networks demonstrated superior performance compared to SVMs across evaluation metrics
- Limited impact observed from POS tagging on overall classification performance
- Attention mechanisms provided insights into feature importance
- Top-K accuracy analysis revealed model effectiveness in handling related product categories

## Technical Stack
- **Python** - Primary programming language
- **Scikit-learn** - Machine learning implementations
- **PyTorch** - Neural network development
- **NLTK** - Natural language processing and POS tagging

## Repository Structure
- `project_notebook.ipynb` - Main Jupyter notebook containing analysis
- `project_paper.pdf` - Detailed project paper and findings 