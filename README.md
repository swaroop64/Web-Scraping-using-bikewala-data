# Royal Enfield Bikes Scraper

This is a Python project that scrapes bike details (such as names, prices, ratings, images, and links) for Royal Enfield models from the website [BikeWale](https://www.bikewale.com/royalenfield-bikes/). The data is then stored in a CSV file for easy access and further analysis.

## Features

- Scrapes the following details of Royal Enfield bikes:
  - **Name**
  - **Price**
  - **Rating**
  - **Image URLs**
  - **Bike Details Links**
- Stores the scraped data in a structured format using Pandas.
- Saves the data to a CSV file (`Bikes.csv`).

---

## Prerequisites

- Python 3.6 or higher.
- Required Python libraries:
  - `requests`
  - `pandas`
  - `beautifulsoup4`

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/royal-enfield-bikes-scraper.git
   ```

2. Navigate to the project directory:
   ```bash
   cd royal-enfield-bikes-scraper
   ```

3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

---

## How to Use

1. Run the script:
   ```bash
   python bike_scraper.py
   ```

2. The script will:
   - Fetch data from the website.
   - Parse and extract bike details.
   - Save the data into a CSV file named `Bikes.csv` in the current directory.

3. Open the `Bikes.csv` file to view the scraped data.

---

## Example Output (in Console)

```plaintext
                 Names       Price Ratings  ...
0  Royal Enfield Bullet ₹1,50,000   4.5/5  ...
1  Royal Enfield Classic ₹1,90,000   4.6/5  ...
...
```

---

## Notes

- The script scrapes the first 10 entries from the website.
- Modify the URL or scraping logic to fetch additional data or from different pages.
- Ensure compliance with the website's **terms of service** when scraping data.

---

## File Structure

```plaintext
.
├── bike_scraper.py       # The main script
├── requirements.txt      # Dependencies file
├── Bikes.csv             # Output file containing scraped data
```

---


Feel free to customize the README further to align it with your preferences!
