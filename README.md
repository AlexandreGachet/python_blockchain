# Python Blockchain

## Description

This project is a Python blockchain implementation, command-line interactive.

## Setup

In order to run the project locally, make sure to meet the following requirements:

* Make sure you have python 3 and pip installed

* Run the following command to install required packages (where `pip` refers to pip bin path):

```bash
pip install pycrypto
```

* The run the project, simply run (`python` refers to python bin path):

```bash
python node.py
```
## Usage

The user is prompted the following possible actions:

1. Add a new transaction value (recipient, amount)
2. Mine a new block
3. Output the blockchain blocks
4. Check transactions validity
5. Create a wallet
6. Load an existing wallet
7. Save keys

The execution can stopped by pressing "q" (quit).

## Features

* Chain building
* Block mining
* Block hashing
* Analyze & verify chain
* Transactions signing
* Store chain to disk
* Wallet handling