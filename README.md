# Black-Litterman Portfolio Optimization with Cryptocurrency-Related Views

This repository contains a Python implementation of the Black-Litterman model for portfolio optimization, specifically tailored for cryptocurrencies. The Black-Litterman model is a sophisticated method that combines investor views with market equilibrium to generate optimal portfolio weights.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Black-Litterman model is an advanced portfolio optimization framework that improves upon the traditional mean-variance optimization by incorporating investor views. This repository extends the Black-Litterman model to the cryptocurrency market, allowing users to incorporate their views on specific cryptocurrencies and adjust their portfolio accordingly.

## Features

- **Historical Data Processing:** Reads and processes historical cryptocurrency price data.
- **Black-Litterman Model:** Implements the Black-Litterman model to integrate market views and calculate implied equilibrium returns.
- **Portfolio Optimization:** Optimizes portfolio weights to maximize the Sharpe ratio.
- **Visualization:** Provides visual comparisons of optimal portfolio weights versus market capitalization weights.

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/yourusername/black-litterman-crypto.git
    cd black-litterman-crypto
    ```

2. Install the required dependencies:

    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Prepare your cryptocurrency price data in a CSV file.

2. Modify the script to point to your data file if necessary.

3. Run the script:

    ```sh
    python black_litterman_allocation_crypto_related_views.py
    ```

4. View the output and visualizations to analyze the optimal portfolio weights.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any features, bug fixes, or enhancements.

## License

This project is licensed under the MIT License.
