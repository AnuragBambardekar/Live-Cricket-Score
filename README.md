# Live Cricket Score

This Python script uses Selenium to scrape live cricket scores from ESPN Cricinfo.

## Prerequisites

Before running the script, make sure you have the following installed:

- Python 3.x
- Chrome browser

## Usage

1. Run the script:

    ```bash
    python cricket_score_scraper.py
    ```

   This will launch a Chrome browser window, navigate to the ESPN Cricinfo live cricket score page, and scrape the relevant information.

2. Wait for the script to finish. It will print details of ongoing matches, including team names, scores, descriptions, and results.

3. The script will automatically close the browser when done.

## Script Details

- `scrape_match_info.py`: The main script file containing the Selenium code to scrape live cricket scores.

## Configuration

- The script is currently set to wait for 5 seconds after opening the browser. You can adjust this wait time if needed.

## Acknowledgements

- ESPNcricinfo
