# Movie_Recommendation_System

STEP 1:Data Scraping

Data was Scraped from IMDB website(using beautiful soup and requests).Refer Web Scraping_new.py script in this repository.
This dataset consists of top 1000 movies based on popularity and the range(count) of movies can be modified in the above mentioned python script based on preference.

STEP 2:Creating a Content Based Recommendation system(Refer Content based recommendation.py file)

Content-based filtering uses item features to recommend other items similar to what the user likes, based on their previous actions or explicit feedback.

![image](https://user-images.githubusercontent.com/64595758/130803753-2211bcc9-a9f2-4bf8-952f-b9f044130f33.png)

STEP 3:Creating a frontend for model serving

For this application I have created a front end based on streamlit.
This application fetches input from the user and provides top 5 similar movies based on the input.This is all done with the help of recommendation system that we have created in the above step.

STEP 4:Model Deployment

Created model has been containerized using docker and its been pushed to container repository.
Its then deployed in Kubernetes to manage and increase scalability of the application.

![image](https://user-images.githubusercontent.com/64595758/130807050-ab633c7c-5f54-448a-9fc7-aa680756736d.png)

Application url- http://35.230.8.59/





