# Bitcoin Investment Checker

[![GitHub license](https://img.shields.io/github/license/onurcangnc/THM-Python-Project2.svg)](https://github.com/onurcangnc/THM-Python-Project2/blob/main/LICENSE)

Monitor your Bitcoin investment and receive notifications when it falls below $30,000.

## Project Overview

This simple program helps you keep track of your Bitcoin investment. It performs the following tasks:

1. Converts the amount of Bitcoin you own to its equivalent value in USD.
2. Calculates the current value of your Bitcoin investment.
3. Checks if the investment value is below $30,000.
4. Displays a message based on the result of the check.

## Prerequisites

Before running the program, make sure you have the following information:

- The amount of Bitcoin you own (e.g., `investment_in_bitcoin`).
- The current value of 1 Bitcoin in USD (e.g., `bitcoin_to_usd`).

## Instructions

1. **Clone this repository** to your local machine.

    ```bash
    git clone https://github.com/onurcangnc/THM-Python-Project2
    ```

2. **Open the project directory** in your preferred code editor.

3. **Set the following variables** in the script to match your investment:

   - `investment_in_bitcoin`: The amount of Bitcoin you own.
   - `bitcoin_to_usd`: The current value of 1 Bitcoin in USD.

4. **Run the script**.

    ```bash
    python bitcoin_investment_checker.py
    ```

## Purpose of the Script

1. The program calculates the current value of your Bitcoin investment and checks if it's below $30,000.

2. Based on the result, it displays one of the following messages:

   - If your Bitcoin investment is below $30,000:
        - **Bitcoin fell below $30,000!**
   - If your Bitcoin investment is $30,000 or above:
        - **Bitcoin is above $30,000!**

Feel free to customize the project to meet your preferences and requirements.

Happy investing!