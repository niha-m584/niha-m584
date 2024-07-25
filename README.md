## Hi there 👋 I'm Niha

# Welcome to My GitHub Profile!

## About Me
I am pursuing my Master's in Information and Data Science at UC Berkeley. 

## My Repositories
Here are some of my key projects:

- [Pain Level Estimation Project](https://github.com/niha-m584/2022-2023_HDSI_Project): HDSI Scholarship for 2022-2023. Using Computer Vision to Detect Pain Level Estimation for Patients. This project aims to estimate the pain levels of hospital patients using a convolutional neural network (CNN) to predict a pain score ranging from 0 to 7. Developed with the Keras framework in Python, this model provides a robust classification solution for healthcare applications. Initially, a complex model with over 2.5 million parameters was used but was found to overfit the data. By simplifying the model and removing three layers, we achieved a balance between complexity and performance, resulting in an accuracy of 78% on the test data. This trial with reduced model complexity demonstrated that a simpler model could be more effective.
  
- [Google Rating Prediction](https://github.com/niha-m584/google_rating_prediction): This project examines a dataset of Google restaurant reviews, including user IDs, business IDs, ratings, text reviews, and attached images. Notably, the ratings are skewed towards higher values, with 68% being 5-star ratings, as shown in a pie chart. The dataset includes 9782 businesses and 200,000 records from 169,380 users. Our primary task was to predict a user’s rating for a business based on features such as review text. We experimented with various models, including logistic regression with TF-IDF for text processing, SVD, and ALS. The logistic regression model, particularly with a TF-IDF vector length of 750 and a regularization constant of 7, achieved the highest accuracy of 73.1%. This model outperformed the baseline models, highlighting the significance of incorporating textual data into predictive modeling. The project's findings emphasize the importance of feature selection and model tuning in achieving high prediction accuracy.
  
- [Drug Review Analysis Project](https://github.com/niha-m584/DrugReviewAnalysisProject): The project was chosen due to the growing importance of data analysis in understanding patient experiences and outcomes associated with pharmaceutical treatments. The project leverages machine learning to identify trends in drug reviews, using natural language processing techniques to analyze sentiment in user evaluations. Developing an effective prediction model for assessing drug evaluations can help identify and address negative experiences while building on positive ones. Our results showed that a logistic regression model with TF-IDF vectorization of review texts achieved the highest accuracy of 73.1%, outperforming simpler baseline models. This indicates the significant impact of incorporating textual data into predictive modeling. Additionally, attempts with other models, such as decision tree regressors and neural networks using BERT word embeddings, highlighted the importance of feature selection and model tuning. These findings underscore the potential of ML and NLP in transforming patient feedback into actionable insights for pharmaceutical companies.

- [Taxi Travel Time Prediction](https://github.com/niha-m584/kaggle_competition_sp23): This project aims to predict taxi travel times in Porto, Portugal, using a regression model that minimizes RMSE. The dataset includes 1.7 million entries with details such as taxi ID, call type, and timestamps. Various preprocessing steps, including cleaning and feature extraction, were conducted to prepare the data. A multi-layer linear model was developed using PyTorch, experimenting with different architectures and regularization techniques to enhance performance. The final model, optimized with PyTorch's SGD optimizer, achieved a test loss of 700.8 seconds. This model can potentially improve taxi dispatch efficiency and trip planning accuracy in Porto's taxi system.






