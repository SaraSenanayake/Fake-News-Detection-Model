The importance of fake news detection is increasingly recognized in today's society. With the rise of social media and online platforms, misinformation spreads rapidly, influencing public opinion and decision-making processes. 
Detecting and fighting fake news is crucial for preserving the integrity of information and promoting informed discussion. 
It helps safeguard against manipulation, dishonesty, and the decline of trust in media sources, ultimately contributing to a more informed and strong society.

Throughout this study, I'm developing a data model is to spot fake news. 
Initially, news articles were obtained by scraping Google News, and some fake websites. 
However, due to limited access and restrictions on fake news web sites, a fake news dataset was obtained from Kaggle to supplement the dataset. 
By merging the web scraped data with the Kaggle dataset, a comprehensive dataset was created to train the fake news detection model.

Logistic regression emerged as the best-performing model for the fake news detection task, achieving the highest accuracy among the tested algorithms. 
This approach utilizes a logistic function to model the probability of a binary outcome, making it well-suited for classification tasks like identifying fake news. 
By fitting a logistic regression model to the training data, the algorithm learns to make predictions based on the relationship between the input features and the target variable.



