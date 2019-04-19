# NBA Shot-Type Prediction

What if you could predict the type of shot to play in basketball? You could be the greatest player of all time. You could possibly beat Lebron James, Stephen Curry or even Michael Jordan. 

Let's take a look at how this can be done.

## Install

This project requires python 3.6 or any other higher versions of python along with the following libraries installed:

* Numpy
* Pandas
* matplotlib
* scikit-learn
* Seaborn
* Keras

You also need a software to run this python notebook, "Jupyter Notebook". It is hghly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included.

## Description of the repository

This repository contains 1 notebook:

* "NBA.ipynb" : This notebook contains neural network implementation using keras on the dataset.

## Attribute information

* GAME_ID : Unique id for each game played.
* MATCHUP : Names of the teams playing and date of match.
* LOCATION : Match played at home ground or away.
* W : Won or Lost
* FINAL_MARGIN : Final margin of victory.
* PERIOD : Period (quarter) a which shot was played.
* GAME_CLOCK : Time at which shot was played.
* SHOT_CLOCK : Seconds remaining before shot was played.
* DRIBBLES : Number of dribbles made before shooting.
* TOUCH_TIME : Number of seconds player held the ball.
* SHOT_DIST : Distance between the shot being played from and the basket.
* PTS_TYPE : Type of shot played.
* SHOT_RESULT : Did the shot get in or not.
* CLOSEST_DEFENDER : Name of the closest defender from the player holding the ball.
* CLOSEST_DEFENDER_PLAYER_ID : Id of the closest defender.
* CLOSE_DEF_DIST : Distance of the closest defender from the player who is about to make a shot.
* FGM : Field Goal Margin, a result of 'SHOT_RESULT'.
* PTS : Points scored.

## Output Variable (desired target)

* PTS_TYPE - categorical - Tells us what type of shot is to be played.

## Models trained on:

Training Model | Accuracy
-------------- | --------
Neural Network | 87.88%