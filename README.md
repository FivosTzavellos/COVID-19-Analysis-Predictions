# COVID-19-Analysis-Predictions

The project aims to showcase different graphs using data from Covid-19 patients around the world (as of April 2020), while also predicting future cases using ML Methods explained in detailed in the following sections and in the code.

In the Plots-Visualisations Notebook we extract and preprocess data concerning Covid-19 confirmed cases, deaths and recoveries per countries and create some tables containing useful information like the confirmed cases' percentage change per week, while also creating some insightful visualisations like bar charts, map plots, heat maps, scatter plots and tree maps utilising tools like Plotly, Folium, Matplotlib and Seaborn. For the last part of the plotting we extract Covid-19 patient data and plot some sex - age - BMI histograms as well as some government sentiment data.

In the Plots-Predictions Notebook we use data for confirmed cases, deaths and recoveries per day per country, again plotting some instances of the preprocessed data and using Support Vector Machines and Linear Regression to predict the number of cases for the next 10 days.

In the Covid-19 Sentiment Analysis Notebook we create a stream listener for tweets that contain the words 'Coronavirus Trump' using the Twitter Developer API and Tweepy, preprocess them, store them using a MySQL local database and calculate and graph out the sentiment regarding this topic. We use RE and NLTK to visualise the frequency distribution of words in tweets and the geographic distribution of tweets and combine them, along with the sentiment, in a real time covid-19 mentions tracker-dashboard.
Lastly we predict the sentiment of tweets concerning the US Government using Random Forest Classifier.

Co-authored by Athanasios Papanikolaou
