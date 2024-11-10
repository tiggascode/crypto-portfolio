# Crypto Portfolio Telegram Bot

This bot allows users to track their cryptocurrency portfolio directly in Telegram, calculating profit or loss based on real-time prices from CoinMarketCap.

## Setup

### Requirements

- Python 3.x
- `telebot` library
- `requests` library

### Installation

1. **Clone the repository**:
    ```bash
    git clone <repository_url>
    cd <repository_directory>
    ```

2. **Install dependencies**:
    ```bash
    pip install telebot requests
    ```

3. **Configuration**:

    Create a file named `config.py` in the root of the project directory. Inside `config.py`, add your API keys as follows:

    ```python
    # config.py
    TELEGRAM_TOKEN = "your_telegram_token"
    COINMARKETCAP_API_KEY = "your_coinmarketcap_api_key"
    ```

    - **TELEGRAM_TOKEN**: Obtain from [Telegram BotFather](https://t.me/BotFather).
    - **COINMARKETCAP_API_KEY**: Obtain from [CoinMarketCap API](https://coinmarketcap.com/api/).

4. **Run the bot**:
    ```bash
    python main.py
    ```
    
## License

This project is open-source and available under the MIT License.
