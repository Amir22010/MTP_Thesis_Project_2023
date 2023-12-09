# Hospital Service Quality Aspect based Sentiment Analysis

## 1. Introduction and Background

Sentiment analysis involves the extraction of opinions, emotions, and attitudes related to specific aspects, which, in our case, is assessing the quality of service in hospitals from a patient's perspective. We aim to analyze user sentiments within specific aspects mentioned in patient reviews, providing a fine-grained and nuanced approach.

### Objective:
- Assess the overall quality of a hospital from a patient's viewpoint by extracting fine-grained sentiment expressions.

## 2. Literature Survey

### 2.1 Web Scraping
- Automated extraction of data from websites using web scraping techniques.

### 2.2 Text Pre-processing
- Essential NLP steps like tokenization, lowercasing, and removal of special characters, enhancing sentiment analysis.

### 2.3 Automated Data Annotation
- Utilization of advanced pre-trained models like BERT for intelligent data annotation.

### 2.4 Model Training Evaluation
- Using dedicated test datasets to assess model performance, employing metrics like Precision, Recall, and F1 Score.

### 2.5 KeyBERT
- Utilizing BERT embeddings for keyword extraction within a sentence or document.

## 3. Problem Definition and Objective

- Implementing automated web scraping to gather hospital reviews for NLP analysis.
- Applying NLP techniques for text pre-processing, aspect-level data annotation, model development, and training.
- Creation of annotated training datasets using KeyBERT-based pre-trained model checkpoints.
- Comparative analysis of annotation methods for effective sentiment analysis.

## 4. Methodology

### 4.1 Data Collection and Preparation
- Employing Python-based web scraping on MouthShut.com, resulting in a dataset of 56,080 reviews for analysis.

### 4.2 Text Cleaning for Aspect Extraction
- A detailed process involving the removal of HTML tags, special characters, and stop words for enhancing the dataset quality.

### 4.3 Data Annotation for Aspect-Based Sentiment Analysis
- Automatic annotation methods leveraging advanced models like E2EABSA and KeyBERT.

### 4.4 Model Development for Aspect-Sentiment Analysis
- Usage of a powerful text generative base model to derive aspects and their corresponding sentiments.

### 4.5 Model Training
- Fine-tuned training of the model on 'english,' 'multilingual,' and 'KeyBERT' datasets.

### 4.6 Model Evaluation
- Comprehensive evaluation using precision, recall, and F1 scores on different datasets.

### 4.7 Demo Test Result
![Test](https://github.com/Amir22010/MTP_Thesis_Project_2023/blob/main/Test%20Image/demo.png?raw=true)

### 4.7 Results on Training, Validation, and Test Data
- Detailed evaluation results on training, validation, and test data.

### 4.8 Comparative Assessment
- Comparison of different trained models to understand their performance differences.
