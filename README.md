[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/ambv/black)

## Purpose and definitions
Simple script to solve Animal Crosing's Stalk Market game.

## Install
Tested with Python 3.6.

## Usage
``` 
python solver.py
```

## Preliminary results
### When selling, assuming selling prices are independent and equiprobable
The average selling price using this strategy will be 115.49 and the average buying price will be 89.49 if we decide to buy at all (which happens 88% of the time)
```
## Calculating selling session number 12
  This is the last selling session, we must sell no matter what
  Our expected sell value for this round is 100.00
## Calculating selling session number 11
  We must sell if the price is higher than 100.00
  Our expected sell value for this round is 105.12
## Calculating selling session number 10
  We must sell if the price is higher than 105.12
  Our expected sell value for this round is 108.00
## Calculating selling session number 9
  We must sell if the price is higher than 108.00
  Our expected sell value for this round is 109.90
## Calculating selling session number 8
  We must sell if the price is higher than 109.90
  Our expected sell value for this round is 111.25
## Calculating selling session number 7
  We must sell if the price is higher than 111.25
  Our expected sell value for this round is 112.29
## Calculating selling session number 6
  We must sell if the price is higher than 112.29
  Our expected sell value for this round is 113.10
## Calculating selling session number 5
  We must sell if the price is higher than 113.10
  Our expected sell value for this round is 113.76
## Calculating selling session number 4
  We must sell if the price is higher than 113.76
  Our expected sell value for this round is 114.30
## Calculating selling session number 3
  We must sell if the price is higher than 114.30
  Our expected sell value for this round is 114.76
## Calculating selling session number 2
  We must sell if the price is higher than 114.76
  Our expected sell value for this round is 115.14
## Calculating selling session number 1
  We must sell if the price is higher than 115.14
  Our expected sell value for this round is 115.49

The average selling price will be 115.49

## Calculating buying session number 4
  This is the last buying session, we buy only if the price is better than our estimation of the selling value: 115.49
Proba of buying in the last round 0.88
  Our expected buy value for this round is 97.50
## Calculating buying session number 3
  We must buy if the price is lower than 97.50
  Our expected buy value for this round is 93.55
## Calculating buying session number 2
  We must buy if the price is lower than 93.55
  Our expected buy value for this round is 91.14
## Calculating buying session number 1
  We must buy if the price is lower than 91.14
  Our expected buy value for this round is 89.49

The average buying price will be 89.49


The average gain per turnip is 26.00
```

## Theory
![calculs](calculs.png)