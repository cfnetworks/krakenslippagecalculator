# Kraken Slippage Calculator

This project provides a simple web-based slippage calculator for cryptocurrency trading pairs on the Kraken exchange. It uses Kraken's public API to fetch order book data and calculates the potential slippage for a given order size and trading side (buy/sell).

## Features
- Real-time slippage calculation using Kraken's API.
- Supports any trading pair available on Kraken (e.g., `XXBTZUSD`).
- Easy-to-use interface with input fields for trading pair, order size, and side.

## Requirements
- A modern web browser.
- Internet connection to fetch data from Kraken's API.

## Installation
1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/krakenslippagecalculator.git
    ```
2. Navigate to the project directory:
    ```bash
    cd krakenslippagecalculator
    ```
3. Open the `index.html` file in your web browser.

## Usage
1. Enter the trading pair in the `Trading Pair` input field (e.g., `XXBTZUSD`).
2. Specify the order size in the `Order Size` field.
3. Select the trade side (`Buy` or `Sell`).
4. Click the `Calculate Slippage` button.
5. View the results, including the slippage percentage and effective price, in the output area.

## Project Structure
```
.
├── index.html       # Main HTML file with the slippage calculator code.
├── README.md        # Project documentation.
```

## Technical Details
- **API Used:** Kraken Public API for fetching order book data.
- **Logic:** The slippage is calculated by iterating through the order book levels until the desired order size is fulfilled.
- **Languages:** HTML, JavaScript.

## Example
### Input
- Trading Pair: `XXBTZUSD`
- Order Size: `1`
- Side: `Buy`

### Output
```
Timestamp: 2024-12-19T15:23:00Z
Symbol: XXBTZUSD
Order Size: 1
Slippage: 0.03%
```
## Demo

[Live Demo](https://cfnetworks.github.io/krakenslippagecalculator/)

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bugfix:
    ```bash
    git checkout -b feature-name
    ```
3. Commit your changes and push them to your fork.
4. Create a pull request.

## Acknowledgements
- [Kraken API Documentation](https://docs.kraken.com/)
- Thanks to the open-source community for their support!

## License

This project is open-source and available under the [MIT License](LICENSE).

## Author

Developed by [Christian Fiebich](https://github.com/cfnetworks/).
