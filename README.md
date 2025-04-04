# Booking.com Hotel Scraper

This project is a Python-based web scraping tool designed to extract hotel data from [Booking.com](https://www.booking.com). The script utilizes `requests` and `BeautifulSoup` to fetch and parse data, saving the extracted information into a CSV file. It mimics human-like behavior with randomized delays to prevent detection while maintaining a polite request header.

## Features:
- Extract details like:
  - **Hotel Name**
  - **Location**
  - **Price**
  - **Rating**
  - **Score**
  - **Review**
  - **Booking Link**
- Save the data in a well-structured CSV file.
- Includes error handling for missing or incomplete data fields.

## Prerequisites:
Make sure to have the following installed:
- Python 3.x
- Required Python libraries:
  ```bash
  pip install requests beautifulsoup4 lxml
