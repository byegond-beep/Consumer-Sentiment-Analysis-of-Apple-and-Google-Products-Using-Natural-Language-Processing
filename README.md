# Consumer Sentiment Analysis of Apple and Google Products Using NLP

*A Natural Language Processing (NLP) project that analyzes Twitter conversations about Apple and Google products to classify customer sentiment and generate actionable business insights.*

## Project Overview

Understanding customer sentiment is essential for organizations seeking to improve products, strengthen customer relationships, and protect brand reputation. This project applies Natural Language Processing (NLP) and machine learning techniques to analyze Twitter conversations related to Apple and Google products and automatically classify sentiment as Positive, Negative, Neutral, or Unclear.

The project demonstrates how organizations can leverage social media data to monitor customer perceptions, identify emerging concerns, and support data-driven decision-making.

## Business Problem

Organizations receive large volumes of customer feedback through social media platforms. Manually reviewing thousands of customer comments is time-consuming and difficult to scale.

This project explores whether machine learning can automatically classify customer sentiment from tweet text and uncover the language patterns associated with positive and negative customer experiences.

### Stakeholders

* Product Managers
* Customer Experience Teams
* Marketing Teams
* Brand Managers

## Dataset

**Source:** CrowdFlower Twitter Sentiment Dataset

**Dataset Link:** https://data.world/crowdflower/brands-and-product-emotions

The dataset contains tweets discussing Apple and Google products together with manually assigned sentiment labels.

### Sentiment Categories

* Positive
* Negative
* Neutral
* Unclear

## Project Workflow

1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Text Vectorization
7. Model Development
8. Model Evaluation
9. Model Interpretability
10. Business Insights and Recommendations

## Technologies Used

### Data Manipulation

* Pandas
* NumPy

### Data Visualization

* Matplotlib
* Seaborn
* WordCloud

### Natural Language Processing

* NLTK
* Regular Expressions (Regex)

### Machine Learning

* Scikit-learn
* CountVectorizer
* TF-IDF
* Logistic Regression
* LinearSVC
* Random Forest

## Models Evaluated

| Model                                 | Weighted F1 Score |
| ------------------------------------- | ----------------: |
| Dummy Classifier                      |             0.441 |
| CountVectorizer + Logistic Regression |         **0.662** |
| Tuned TF-IDF + Logistic Regression    |             0.661 |
| TF-IDF + LinearSVC                    |             0.660 |
| TF-IDF + Logistic Regression          |             0.634 |
| TF-IDF + Random Forest                |             0.577 |

### Final Model

**CountVectorizer + Logistic Regression**

The selected model achieved the highest weighted F1-score while providing strong interpretability and computational efficiency.

## Key Findings

* Neutral sentiment dominated customer conversations.
* Positive sentiment was the second most common sentiment category.
* iPhone-related tweets exhibited the highest proportion of negative sentiment.
* Positive sentiment was associated with words such as *smart*, *cool*, *great*, and *excited*.
* Negative sentiment was associated with words such as *headache*, *fail*, *hate*, and *suck*.

## Recommendations

* Implement continuous sentiment monitoring across social media platforms.
* Prioritize products associated with elevated negative sentiment.
* Use positive customer feedback to guide product development and marketing initiatives.
* Incorporate sentiment analytics into customer experience management processes.

## Repository Structure

```text
data/
├── Dataset used for analysis

notebooks/
├── Consumer-Sentiment-Analysis-of-Apple-and-Google-Products-Using-NLP.ipynb
├── Consumer-Sentiment-Analysis-of-Apple-and-Google-Products-Using-NLP.pdf

presentation/
├── Consumer-Sentiment-Analysis-Presentation.pdf

README.md
.gitignore
```

## Repository Navigation

* The dataset is located in the `data/` folder.
* The project notebook and PDF version are located in the `notebooks/` folder.
* The project presentation is located in the `presentation/` folder.

## Additional Resources

* Project Notebook
* Project Report (PDF)
* Presentation (PDF)
* Dataset Source

```
```
