# Flipkart Review Scraper

This project is a web scraper designed to extract customer reviews from products listed on Flipkart. The extracted reviews can be used for sentiment analysis, market research, or any other data analysis task.

## Features

- Extracts reviews from Flipkart product pages.
- Stores the reviews in a structured format (CSV/JSON).
- Handles pagination to retrieve multiple pages of reviews.
- Can filter reviews based on ratings (e.g., only 5-star reviews).
- Uses BeautifulSoup for HTML parsing and Requests for sending HTTP requests.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/MuhammadPA/Flipkart_review_scrapper.git
   cd Flipkart_review_scrapper

2.Install the required dependencies
pip install -r requirements.txt

To scrape reviews for a product, run the script with the product URL:
python scraper.py <flipkart_product_url>



