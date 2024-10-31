# StackExchange_Scraper

First, enter your login information to request-keys.json if you want to scrape stackexchange or to usrpass.txt if you want to scrape stocktwits.

### StackExchange Scraping
1. Enter your login information in `request-keys.json`:
    ```json
    {
        "key": "your key",
        "client_id": "your client_id"
    }
    ```

2. Open and run the `stackexchange.ipynb` notebook in Jupyter Notebook.

### StockTwits Scraping
1. Enter your login information in `usrpass.txt`:
    ```
    enter your email
    enter your password
    ```

2. Open and run the `stocktwits.ipynb` notebook in Jupyter Notebook.

## Files
- `communities.txt`: List of communities to scrape.
- `messages.json`: JSON file to store scraped messages from StockTwits.
- `request-keys.json`: JSON file for StackExchange login credentials.
- `requirements.txt`: List of required Python packages.
- `stackexchange_data.json`: JSON file to store StackExchange data.
- `stackexchange.ipynb`: Jupyter notebook for scraping StackExchange.
- `stocktwits.ipynb`: Jupyter notebook for scraping StockTwits.
- `usrpass.txt`: Text file for StockTwits login credentials.
