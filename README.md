# Predicting-Tourist-Growth-in-Saudi-Arabia
## Overview
#### This project aims to analyze tourist reviews across various cities in Saudi Arabia to evaluate public sentiment toward cultural heritage and modern attractions. By applying data analysis and sentiment modeling techniques, we extracted key insights regarding visitor satisfaction, common complaints, and performance differences between attraction types and locations. The goal is to provide data-driven recommendations to enhance tourism experiences and support cultural promotion strategies.
\n
\n
\n


### Data Analysis
#### We started by defining the categories of attractions (Cultural and Modern) and analyzing the sentiment of reviews associated with them. A sentiment distribution chart provided visual insight into tourist feedback volume and tone.
<p align="center">
  <img src="https://github.com/user-attachments/assets/d202f108-1b97-4bd4-8301-f315240eaade" width="45%" />
  <img src="https://github.com/user-attachments/assets/a72e4b90-62e5-45c2-8fe6-0f1cef2415d4" width="45%" />
</p>


<p align="center">
  <img src="https://github.com/user-attachments/assets/a1c50b5e-54ca-4c12-ba5a-c600983d01f3" width="45%" />
  <img src="https://github.com/user-attachments/assets/48fea56e-2b84-4363-9dc4-6b4f72ef4077" width="45%" />
</p>


### Modeling
#### In order to classify tourist reviews into positive and negative sentiments, we built a supervised machine learning pipeline using multiple models and evaluated their performance. The goal was to determine which model could best interpret public perception of Cultural Heritage and Modern Attractions across Saudi cities.

#### Three different models were implemented:
##### Random Forest outperformed all other models with an accuracy of 91%, making it the final model of choice for classification.
##### Logistic Regression achieved 87% accuracy, offering a more explainable decision boundary but slightly less predictive power.
##### SVM yielded around 85% accuracy, and while effective, its complexity was not justified over Random Forest.

### Testing and Improvements

#### Beyond numerical classification, we conducted a manual qualitative analysis of the negative reviews identified by the final model (Random Forest) to validate the model’s insights and uncover specific problem areas.
#### A number of recurring issues were identified in reviews of Modern Attractions:
#### Disappointment Relative to Expectations: Many tourists voiced frustration about high entrance fees not matching the quality or value of the experience. Example: “50 SAR just to see the fort and a tea house” was perceived as overpriced.
#### Accessibility and Navigation Issues: Several reviews mentioned the difficulty in locating attractions, such as “We drove around more than 3 times before finding the entrance.”
#### Operational Weaknesses: Staff behavior and customer service were frequently cited, with phrases like “very rude staff” appearing in multiple reviews.
#### Ambiance Without Substance: Some reviews acknowledged the attractiveness of the location but followed with “BUT” statements indicating that logistics, food, or service fell short. This mixed sentiment revealed an opportunity for improvement.

### Key Improvements
#### We conducted a city-wise performance analysis using the model’s output to see how sentiments vary across regions:
##### Riyadh: Modern Attractions received higher sentiment scores than cultural ones.
##### Jeddah: Cultural Heritage scored the highest sentiment-wise across all cities.
##### AlUla: Only Cultural Heritage reviewed — results showed strong satisfaction.
#### These results suggest that cities with preserved heritage receive more favorable sentiment, which could influence future tourism campaigns.

### Conclusion
#### This project successfully applied sentiment analysis techniques to evaluate tourist perceptions of Cultural Heritage and Modern Attractions across several cities in Saudi Arabia. Through the use of machine learning models—particularly Random Forest, which achieved the highest accuracy of 91%—we classified reviews with high confidence and extracted key insights about tourist satisfaction.
#### These findings emphasize the importance of not only increasing the number of tourist destinations but also ensuring high-quality visitor experiences, particularly in modern developments.

### Future Work
#### To build upon the current results and create a more comprehensive tourism analysis framework, several future directions are proposed:
##### Multilingual Sentiment Analysis: Extend the model to handle reviews in Arabic to capture a broader spectrum of local feedback.
##### Aspect-Based Sentiment Analysis: Identify specific topics within reviews (e.g., service, price, cleanliness) to generate more targeted improvement recommendations.
##### Advanced NLP Models: Apply transformer-based models like BERT or RoBERTa for higher classification accuracy and context-aware sentiment detection.
##### Integration with Real-Time Feedback: Develop a dashboard that ingests live reviews to provide continuous monitoring and alerting for tourism stakeholders.
#### City-Level Trend Analysis: Incorporate temporal and geographic trends to understand how sentiment evolves across different cities and seasons.

#### These enhancements will transform the system into a powerful decision-support tool for tourism stakeholders, enabling data-driven improvements in planning, service delivery, and overall visitor satisfaction throughout the Kingdom.

