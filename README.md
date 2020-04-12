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
```
Start
## Calculating selling session number 12
  This is the last selling session, we must sell no matter what
  Our expected value for this round is 100.00

## Calculating selling session number 11
  We must sell if the price is higher than 100.00
  Our expected value for this round is 105.12

## Calculating selling session number 10
  We must sell if the price is higher than 105.12
  Our expected value for this round is 108.00

## Calculating selling session number 9
  We must sell if the price is higher than 108.00
  Our expected value for this round is 109.90

## Calculating selling session number 8
  We must sell if the price is higher than 109.90
  Our expected value for this round is 111.25

## Calculating selling session number 7
  We must sell if the price is higher than 111.25
  Our expected value for this round is 112.29

## Calculating selling session number 6
  We must sell if the price is higher than 112.29
  Our expected value for this round is 113.10

## Calculating selling session number 5
  We must sell if the price is higher than 113.10
  Our expected value for this round is 113.76

## Calculating selling session number 4
  We must sell if the price is higher than 113.76
  Our expected value for this round is 114.30

## Calculating selling session number 3
  We must sell if the price is higher than 114.30
  Our expected value for this round is 114.76

## Calculating selling session number 2
  We must sell if the price is higher than 114.76
  Our expected value for this round is 115.14

## Calculating selling session number 1
  We must sell if the price is higher than 115.14
  Our expected value for this round is 115.49
```