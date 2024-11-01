# Applied Machine Learning Project - COMP1804

This repository contains my MSc Data Science coursework for the Applied Machine Learning module, focusing on two primary tasks: topic classification and text clarity classification. These tasks aim to explore and implement machine learning techniques suitable for text classification in response to a hypothetical client’s needs.

## Project Overview
The coursework involves consulting for a client who manages a text-based platform and wishes to use machine learning to automate text classification tasks. Specifically:
- **Task 1**: Classify text into five topics, including "Artificial Intelligence" and "Philosophy," using Logistic Regression with word embeddings.
- **Task 2**: Develop a prototype model to assess text clarity (labelled as "clear enough" or "not clear enough") using TF-IDF vectorisation and Logistic Regression.

## Repository Contents
- **Notebook (`applied_ml_project.ipynb`)**: Contains code for data exploration, preprocessing, model training, and evaluation for both tasks. This file is structured for easy understanding and can be opened in any Jupyter environment.
- **Report (`project_report.pdf`)**: Detailed analysis of the project, including data exploration, model performance, and ethical considerations for the clarity classification model.

## Key Features
1. **Data Preprocessing**:
   - Duplicate removal, entity encoding, and handling class imbalances using oversampling.
2. **Model Selection and Evaluation**:
   - Task 1: Topic classification with Logistic Regression using spaCy word embeddings.
   - Task 2: Text clarity classification using TF-IDF features and an ethical discussion on automated content rejection.
3. **Ethical Considerations**:
   - Discusses potential biases and ethical risks associated with clarity-based content rejection.

## Usage Instructions
1. Clone the repository.
2. Open the notebook (`applied_ml_project.ipynb`) in Jupyter or Google Colab.
3. Follow the code cells to reproduce the analysis.

## Results
Both models perform above baseline, meeting the client's success criteria, with further refinement suggested for enhanced generalisation and clarity evaluation.
