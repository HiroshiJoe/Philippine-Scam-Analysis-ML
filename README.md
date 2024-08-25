![Scam Analysis and Machine Learning](scam_guard.png)
# Scam Detection Using Text Analysis and Machine Learning

## Overview

This repository contains the analysis and models used to differentiate between "Scam" and "Non-scam" messages. The data was initially extracted from images using OCR (Optical Character Recognition) as part of the ScamGuard project, which focused on developing an image-based identification app for phishing and scam messages. This research builds upon the previous work by exploring sentiment analysis and machine learning models to enhance scam detection capabilities.

## Table of Contents

- [Project Description](#project-description)
- [Methodology](#methodology)
- [Results](#results)
- [Research Limitations](#research-limitations)
- [Recommendations](#recommendations)
- [How to Run the Code](#how-to-run-the-code)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Contact Information](#contact-information)

## Project Description

This project aims to analyze and classify messages as "Scam" or "Non-scam" using various text and sentiment analysis techniques. We evaluated different machine learning models, including logistic regression and XGBoost, to determine the most effective approach for scam detection.

## Methodology

### Data Preprocessing

1. **Text Vectorization**: Utilized TF-IDF vectorization to convert text into numerical features.
2. **Feature Engineering**: Added features such as sentiment scores and text length to the model.
3. **Model Training**: Tested various models, including logistic regression and XGBoost, to find the most accurate classifier.

### Evaluation Metrics

- **Accuracy**
- **Precision, Recall, and F1-Score**
- **Confusion Matrix**
- **Histograms of Sentiment Scores**

## Results

### Model Performance

- **XGBoost Model**: Achieved the highest accuracy in classifying scam and non-scam messages.
  - Accuracy: 93.75%

### Sentiment Analysis

- **Scam Messages**: Mean sentiment score of 0.18.
- **Non-scam Messages**: Mean sentiment score of 0.16.

### Word Frequency Analysis

- **Scam Messages**: Top words include "free," "money," "link," etc.
- **Non-scam Messages**: Top words include "lazada," "peso," "sale," etc.

## Research Limitations

- **Dataset Constraints**: The dataset derived from images and OCR preprocessing may contain inaccuracies or artifacts introduced during text extraction, potentially affecting the accuracy of the sentiment analysis and model performance.
- **Model Generalization**: The study focused on text extracted from specific types of images (scam-related messages), which may limit the generalizability of the findings to other forms of text data or different types of scams not covered in this dataset.
- **Regional Specificity**: The data used in this study is Philippine-based, which might not be representative of scam messages in other regions. The regional context and language nuances may impact the applicability of the results to other geographic locations or cultural contexts.

## Recommendations

1. **Enhanced Filtering Techniques**: Implement advanced filters and update them regularly to detect and filter out scam messages based on key terms and sentiment patterns.
2. **User Education**: Educate users about common scam tactics and red flags through awareness campaigns and best practice guidelines.
3. **Sentiment and Emotional Analysis Integration**: Utilize sentiment and emotion-based classification as part of the screening process for scam detection.
4. **Local Language Considerations**: Adapt filters for local languages and collaborate with local experts to refine detection techniques.

## How to Run the Code

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/repository-name.git
   ```
2. Navigate to the project directory:
   ```bash
   cd repository-name
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the analysis script:
   ```bash
   python analyze.py
   ```

## Data Access

The dataset used in this research is private and intended for research purposes only. To obtain access to the data, please contact Heroshi Joe Abejuela directly at joeheroshi2807@gmail.com. 

## License

See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **Heroshi Joe Abejuela**: Researcher and author of this study.
- **ScamGuard Project**: Previous work on image-based identification app for phishing.

## Contact Information

For any inquiries or further information, please contact:

- **Heroshi Joe Abejuela**
- **Email**: joeheroshi2807@gmail.com
- **GitHub**: [HiroshiJoe](https://github.com/HiroshiJoe)
