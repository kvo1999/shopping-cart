# Shopping Cart Project
[README.md adapted from Professor Rossetti's example]

Access the [Project Description](https://github.com/prof-rossetti/intro-to-python/tree/main/projects/shopping-cart).

## Prerequisites
    * Anaconda 3.7
    * Python 3.8
    * Pip

## Installation
Create a respository as described [here](https://github.com/prof-rossetti/intro-to-python/tree/main/projects/shopping-cart#repo-setup) or clone this [remote repository](https://github.com/kvo1999/shopping-cart) onto your own computer. 

Navigate to your own command line:

```sh
cd shopping-cart
```
Using Anaconda, create a new virtual environment called "shopping-env":

```sh
conda create -n shopping-env python=3.8 # (first time only)
conda activate shopping-env
```
Install package dependencies from inside virtual environment:
```sh 
pip install -r requirements.txt
```

## Setup
In the root directory of your local repository, create the new ".env" file that will contain the tax rate you'd like to use. If you are using, for example, an 8.75% tax rate:
```sh
touch .env
echo TAX_RATE=0.0875 >> .env
```

## Usage 
Run the program

```sh
python shopping_cart.py
```

