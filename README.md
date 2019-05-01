# Poker Hand Prediction
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Data Description

### Attribute Information:
1) S1 “Suit of card #1”
  Ordinal (1-4) representing {Hearts, Spades, Diamonds, Clubs}

2) C1 “Rank of card #1”
  Numerical (1-13) representing (Ace, 2, 3, ... , Queen, King)

3) S2 “Suit of card #2”
  Ordinal (1-4) representing {Hearts, Spades, Diamonds, Clubs}

4) C2 “Rank of card #2”
  Numerical (1-13) representing (Ace, 2, 3, ... , Queen, King)

5) S3 “Suit of card #3”
  Ordinal (1-4) representing {Hearts, Spades, Diamonds, Clubs}

6) C3 “Rank of card #3”
  Numerical (1-13) representing (Ace, 2, 3, ... , Queen, King)

7) S4 “Suit of card #4”
  Ordinal (1-4) representing {Hearts, Spades, Diamonds, Clubs}

8) C4 “Rank of card #4”
  Numerical (1-13) representing (Ace, 2, 3, ... , Queen, King)

9) S5 “Suit of card #5”
  Ordinal (1-4) representing {Hearts, Spades, Diamonds, Clubs}

10) C5 “Rank of card 5”
  Numerical (1-13) representing (Ace, 2, 3, ... , Queen, King)

11) CLASS “Poker Hand”
  Ordinal (0-9)

  0: Nothing in hand; not a recognized poker hand 
  1: One pair; one pair of equal ranks within five cards
  2: Two pairs; two pairs of equal ranks within five cards
  3: Three of a kind; three equal ranks within five cards
  4: Straight; five cards, sequentially ranked with no gaps
  5: Flush; five cards with the same suit
  6: Full house; pair + different rank three of a kind
  7: Four of a kind; four equal ranks within five cards
  8: Straight flush; straight + flush
  9: Royal flush; {Ace, King, Queen, Jack, Ten} + flush

## Algorithms used:
1) SVM
2) Decision Tree
3) Naive Bayes
4) Random Forest
5) Artificial Neural Network(Deep Learning)
6) AdaBoost Classifier

## Analysis:
### Naive Bayes
- - - -
#### Barchart
![NB Barchart](https://github.com/Somil112/Poker-Hand-Prediction/blob/master/visualizations/nb_bar.png)

#### Heat Map of Confusion Matrix
![NB HeatMap](https://github.com/Somil112/Poker-Hand-Prediction/blob/master/visualizations/nb_heatmap.png)
### Random Forest
- - - -
#### Barchart
![RF Barchart](https://github.com/Somil112/Poker-Hand-Prediction/blob/master/visualizations/rf_bar.png)

#### Heat Map of Confusion Matrix
![RF HeatMap](https://github.com/Somil112/Poker-Hand-Prediction/blob/master/visualizations/rf_heatmap.png)

### Decision Tree
#### Barchart
![DT Barchart](https://github.com/Somil112/Poker-Hand-Prediction/blob/master/visualizations/dt_bar.png)

#### Heat Map of Confusion Matrix
![DT HeatMap](https://github.com/Somil112/Poker-Hand-Prediction/blob/master/visualizations/dt_heatmap.png)

### AdaBoost Classifier
#### Barchart
![AB Barchart](https://github.com/Somil112/Poker-Hand-Prediction/blob/master/visualizations/ab_bar.png)

#### Heat Map of Confusion Matrix
![AB HeatMap](https://github.com/Somil112/Poker-Hand-Prediction/blob/master/visualizations/ab_heatmap.png)


## Results:
 SNo.|Accuracy  |  Model Name
 --- |--------- | --------------
 0   | 48.00    | Decision Tree
 1   | 49.16    | AdaBoost
 4   | 50.13    | Naive Bayes 
 3   | 56.79    | Random Forest 
 2   | 94.50    | ANN 


## Conclusion:
### ANN works best giving an accuracy of 94.5%

