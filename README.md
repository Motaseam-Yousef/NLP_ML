# NLP_ML
# Movie Review Project

This repository showcases a comprehensive project on analyzing movie reviews, building predictive models, and deploying the best model as an API using Flask.

## Objective:

The primary goal of this project is to develop a model that can accurately classify movie reviews. Upon achieving satisfactory results, the model is deployed as a web API using Flask for real-time prediction of movie review sentiment.

## Tasks Completed:

- **Data Analysis:** Conducted a thorough analysis of the movie reviews dataset, including understanding the distribution of sentiments, most common words, and relationships between different features.

- **Data Preprocessing:** Cleaned and preprocessed the reviews, including tasks such as text normalization, removing stop words, and vectorizing the text.

- **Model Building:** Developed various models to predict the sentiment of movie reviews. This included simple models like Naive Bayes, as well as more complex models like Support Vector Machines and Deep Learning models.

- **Model Evaluation:** Evaluated each model based on appropriate metrics to determine their performance.

- **Model Selection:** Chose the best performing model based on the evaluation results.

- **Model Deployment:** Deployed the best performing model as a Flask API, enabling real-time sentiment prediction of movie reviews.

## Results:

This project successfully implements the entire process of data analysis, machine learning model building, and deployment as an API. The deployed model can accurately predict the sentiment of movie reviews, which could be used in real-world applications such as recommendation systems, customer feedback analysis, and more. Detailed steps and results can be found in the included Jupyter notebook.

## How to Use:

To use this project, clone the repository and run the Jupyter notebook:

```bash
git clone https://github.com/your-repo/movie-review-project.git
cd movie-review-project
jupyter notebook
```

To interact with the deployed model API, send a POST request with the movie review to be analyzed to the provided endpoint.

Explore this project and feel free to suggest improvements or adapt it to your own needs. Enjoy learning!

## Dependencies:

- Python 3
- Flask
- Sklearn
- NLTK
- Keras/TensorFlow
