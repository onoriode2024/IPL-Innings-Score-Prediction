
# **IPL Innings Score Predition**

Cricket is one of the most cherished outdoor sports globally, and among its most celebrated tournaments is the Indian Premier League (IPL). Established in 2008 by the Board of Control for Cricket in India (BCCI), the IPL is a professional Twenty20 (T20) cricket league that has rapidly gained international acclaim. Every year, eight franchise teams representing different Indian cities compete in this high-octane 20-over format, making it one of the most-watched sporting events in the world.

The IPL Inning Score Prediction Project is designed to estimate the final first-innings score of a match based on real-time and historical data. A cricket match, particularly in the T20 format, is influenced by a complex interplay of variables such as player performance, game dynamics, and pitch conditions. This project aims to capture these factors using data mining and machine learning techniques to provide accurate and insightful score predictions.

The model incorporates a variety of features that are crucial in determining the outcome of an innings:
1. Number of wickets left
2. Number of balls remaining
3. Current scores of the batsmen at the crease
4. Team's average score over the last 5 years
5. Wickets lost in the last 5 overs
6. Nature of the pitch (batting-friendly, bowling-friendly, etc.)
7. Relative strength of the batting and bowling sides
8. These features reflect both current match conditions and historical team performance trends, enhancing the robustness of the predictive model.

The dataset was collected from Kaggle, comprising comprehensive IPL data including player statistics, match venues, and ball-by-ball data. The data was preprocessed and split into training and testing sets as follows:
* 80% Training Set
* 20% Testing Set

The final dataset used for training the model includes the following attributes:
* Venue: Location where the match is being played
* Bat Team: Team currently batting
* Bowl Team: Team currently bowling
* Batsman: Name of the batsman on strike
* Bowler: Name of the current bowler
* Runs: Runs scored so far
* Wickets: Wickets lost so far
* Overs: Overs completed
* Runs_last_5: Runs scored in the last 5 overs
* Striker: Runs scored by the batsman on strike
* Non-Striker: Runs scored by the non-striker
* Total: Target variable – the final first innings score


## Installation

To install the libraries used in this project, follow the below steps

```bash
pip install numpy
pip install pandas
pip install matplotlib.pyplot
pip install seaborn
pip install pickle
pip intall flask
pip install sk-learn
```
    
![Logo](https://github.com/onoriode2024/IPL-Innings-Score-Prediction/blob/main/appview.png?raw=true)


## Running Flask API

To run a Flask deployment tests, run the following command

```bash
  python app.py
```

## Running Heroku Tests

To run a Heroku deployment tests, run the following link



```bash
  python app.py
```

## Deployment

Steps To Deploy The App:

prepare your dataset:

```bash
  1. Data Extraction
  2. Exploratory Data Analysis(EDA)
  3. Feature Engineering
  4. Model Building and Tuning 
  5. Building Flask API
  6. Pushing code to Github
  7. Connecting to your Heroku account
  8. Deploy App
```

