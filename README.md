# Fintech_Module_19_Homework_Crypto_Wallets
# Darcy Davis
A repo for my homework assignment for Module 19

# Python Cryptocurrency Utilities

## Overview

This repository contains two Python scripts that serve different purposes within the realm of cryptocurrency management and automation.

## Scripts

### `crypto_wallet.py`

This script is a simple interface for managing a cryptocurrency wallet, allowing users to check their balance and initiate send/receive transactions.

#### Features

- **Generate Ethereum Account**: Generate an ethereum account based on a mnemonic seed phrase.
- **Check Balance**: View how much currency is available in the wallet.
- **Send A Transactiony**: Transfer cryptocurrency to another wallet.


### `krypto_jobs.py`

An automation tool for scheduling cryptocurrency-related jobs. It is designed to execute tasks based on specific conditions, such as price changes.

#### Features

- **Account View**: Keep an eye on the wallet address and balance of your Ether account.
- **Wage Cost Calculator**: Has a basic input that calculates the expected wage cost of using a particular worker.  It takes the hourly rate from our database and multiplies it by the selected amount of hours.
- **Transaction Initiation**: Automatically initiate transactions based on the user's selection.

## Usage Instructions

### Running `crypto_wallet.py`

Execute the script via the command line to manage your cryptocurrency wallet operations:
```python crypto_wallet.py```

The script provides prompts for necessary information such as wallet details and transaction parameters.

### Running `krypto_jobs.py`

Launch this script via command line to bring up the StreamLit GUI

```streamlit run krypto_jobs.py```


The script will execute in your default browser, allowing you to perform simple tasks such as calculate the Ether that each labour option will cost; then send the calculated amount to the freelance hire to take on their services.

See below gif for how the Streamlit GUI interface performs successfully in practice:

![GUI and Ganache live](https://github.com/darcy5d/Fintech_Module_19_Homework_Crypto_Wallets/blob/main/screengrabs/ganche_streamlit_live2.gif?raw=true)
To see in full resolution go to the [Vimeo link](https://vimeo.com/881344422?share=copy)

## Configuration

- **crypto_wallet.py**: Input the relevant wallet information directly into the script to allow it to interface with your cryptocurrency holdings.
- **krypto_jobs.py**: Define the job conditions such as specific time frames in the Streamlit interface

## License

The scripts are provided under the MIT License. Refer to the `LICENSE` file for the full text.

## Disclaimer

These scripts was created for educational purposes. Exercise caution and ensure secure handling of all sensitive information. Test thoroughly before any live use.
