# Shresht Venkatraman
-UCSD Economics Major, Data Science Minor
-Open for full time positions and internships


**Click on the links below to view the repository of the project**

# [INDONESIA SOVEREIGN DEBT SUSTAINABILITY ANALYSIS](https://github.com/Shrsht/Indonesia-Debt-Sustainability-Analysis)
### *(FINANCIAL MODELLING, VISUALISATION)*
­	Researched and built a Debt Sustainability Analysis model for Indonesia from scratch, using publicly available macroeconomic and gross public debt data. Designed and coded accompanying visualizations of Debt-Creating Flows, Public Debt Composition and gross financing needs using Python. Model framework and visualizations closely align with the IMF’s new DAS framework for Lower Scrutiny Market Access countries.
­	Created a debt-composition heat map breaking-down Indonesia’s debt profile, gross financing needs and annual changes in public sector debt.
­	Developed in 3 days for personal research interests through reverse-engineering of publicly available

<img width="1068" alt="Screenshot 2023-06-15 at 8 20 45 AM" src="https://github.com/Shrsht/Shresht_Portfolio/assets/102553723/be2c9bc5-ef86-4d87-a6d1-8fbbe36dc452">


# [S&P 500 STOCK RECOMMENDATION PROJECT](https://github.com/Shrsht/LSTM-Google-Stock-Prediction)
### *(ML,LSTM,NLP,DEEP LEARNING, FINANCIAL MODELLING, VISUALISATION)*
**(WIP)** This is an ongoing project as part of the UCSD *Data Science Student Society(DS3) Projects Committee 2023*. This project began with a dataset of historical S&P 500 data and an original goal of building a stock recommendation system - i.e using AI and ML models to predict the Opening Price movement of a given stock. Given this background, we appraoched this challenge in 2 ways:

* **Financial Modelling** - Predicted Opening Stock Price of Google Stocks (GOOGL)  using- Random Forests, LSTMs, Koopman Neural Networks, all implemented in Python with TensorFlow and scikit-learn packages.
* **Scraping News Websites** -  We used the Twitter API to perform Sentiment Analysis on tweets that referenced a given stock and tried to build a system to analyse whether the Twitter sentiment has an effect on the opening Price of the stock.
* **Graphing the Efficient Frontier** - ­	Using Modern Portfolio Theory, we calculated and graphed the Efficient Portfolio Frontier by simulating 2500 portfolio combinations and selecting the portfolios that minimized the portfolio risk and maximized the Sharpe Ratio. 

![Project Poster](https://github.com/Shrsht/Shresht_Portfolio/assets/102553723/2b0f22dd-b4fe-4187-9488-47fb3eb113f7)



# [PREDICTING POLITICAL PARTY BY STOCK PORTFOLIO](https://github.com/Shrsht/Stock-Trades-by-Members-of-the-US-House-of-Representatives.git)
### *(ML, DECISION TREES, RANDOM FOREST CLASSIFIERS,LINEAR ALGEBRA)*
This Project is an exploration of the 'House Stock Watcher" data set which tracks the stock trading activity of members of the House of Representatives. The dataset contains stock information spanning the period from 2020 to 2022 and was designed to explore the possibility of insider trading among members of Congress. 

Using a combination of techniques like Decision Trees and Random Forest Classifiers, we attempt to answer questions like:
* Which party makes the most trades of a given stock?
* Which congresspersons have made the most trades? 
* Given a stock portfolio, can we predict the Party of the member that owns the portfolio?
  

# [STATISTICAL LANGUAGE MODEL OF THE SHAKESPEARE CORPUS](https://github.com/Shrsht/Statistical-Language-Model-of-the-Ramayana)
### *(API SCRAPING, STATISTICAL LANGUAGE MODELS, LLMs, NLP)*
In this project, we build a Statistical Language Model using the public domain corpus of the English author, William Shakespeare.

Statistical Language Models (SLMs) attempt to capture the likelihood that a given sequence of words occur in a given "language" (the precise term is "corpus" or "corpora"). 
We use the Shakespeare corpus as found on Project Gutenberg for the pupose of this investigation. 

**As with all statistical models, the true data generating process is never known and thus we cannot know the true probability that a sequence of words will occur – however, we can estimate these probabilities via various methods, some of which are more reliable than others. For example, one might guess that the probability of a sentence is simply the product of the empirical probabilities (i.e., the number of times a word is observed in a dataset divided by the number of words in that dataset). This is one of the methods of estimating the probability of a sequence of words that we implement in this project.**

# [CALCULATING AND GRAPHING THE EFFICIENT FRONTIER OF A GIVEN STOCK PORTFOLIO](https://github.com/Shrsht/Graphing-Efficient-Frontier)
### *(ML,FINANCIAL MODELLING,PORTFOLIO THEORY)*
**WIP** In Modern Portfolio Theory, the 'Efficient Frontier' (or portfolio frontier) is an investment portfolio which occupies the "efficient" parts of the risk–return spectrum. Formally, it is the set of portfolios which satisfy the condition that no other portfolio exists with a higher expected return but with the same standard deviation of return (i.e., portfolio Risk). 

In this project I use an API to obtain stock data on a give portfolio of Stocks (Tesla, Google and Apple) and use thier given closing price to calculate 2 indices - Sharpe Ratio and Portfolio Variance. Using these indices we calculate the *"Efficient Frontier"*, i.e those Portfolios who's proportion of stocks have the highest Portfolio Return (measured by the Sharpe Ratio) and the lowest Portfolio Variance. 

# [SEC API TO GET COMPANY FINANCIAL REPORTS (10K and 10Q FILINGS)](https://github.com/Shrsht/Parsing-Financial-Statements-with-Python)
### *(NLP, FINANCIAL MODELLING)*
In this Project I make use of the SEC API to obtain JSON files of a companies financial statements (10-k and 10-Q filings) to convert them form JSON to a Pandas DataFrame. Using the Pandas dataframe I plan on building an automated LBO Model that will generate an LBO + DCF Model of a given company using Python without needing to build it manually over excel.

# [SENTIMENT ANALYSIS OF IMDB REVIEWS](https://github.com/Shrsht/IMDB_Sentiment_Analysis)
### *(NLP, MULTIVARIATE BAYES, GAUSSIAN MIXTURE MODELS)*
In our exploration, we make use of this data set to develop a Sentiment Analysis Model that predicts whether a given review has a 'positive' or 'negative' rating. We make use of 3 Probabalistic Machine Learning Models - 
* Naive Bayes
* Multivariate Bayes 
* Bernoulli Naive Bayes

# [Python Exploration of Car and Home Sales during the Peak of the COVID-19 Pandemic](https://github.com/Shrsht/Analysis-of-Luxury-Car-Sales-During-Covid)
### *(DATA VISUALISATION, LINEAR REGRESSION)*
The goal of this project was to study and identify correlations between COVID-19 positive cases and purchases of luxury cars and houses in the United States. We use COVID-19 positive cases as an approximation of severity of public health situation at a point of time since it is close to how COVID-19 pandemic was addressed in the news and by the officials. The idea of this question was driven by our prior knowledge of difference between luxury goods and necessities and their theoretical response to different economic situations. We found that there was no relationship between total number of COVID-19 cases and house sales or car sales based on the results of linear regression models.

# [Python BlackJack Simulation](https://github.com/Shrsht/Python-BlackJack-Simulation)
In this project, I implement a Python simulation of a Blackjack game using object-oriented programming techniques. Blackjack is a card game typically played at casinos where each player competes against the dealer to get a score closest to 21, without going over 21. At the start of the game, each player and the dealer are given 2 cards. A person's set of cards is referred to as their hand. The player's own cards (their hand) are visible to themselves and only one of the dealer's cards is visible to everyone. After everyone receives their cards, the dealer asks each player whether they would like to hit (take another card) or stand (keep their current cards). Each player can hit (take a card) as many times as they would like to get their score as close to 21 as possible, without going over. Afterwards, the dealer reveals their card and decides to hit or stand. Lastly, the final scores are calculated and the winner is announced


