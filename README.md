# Booking.com Hotel Scraper

This project is designed to extract hotel data from [Booking.com](https://www.booking.com) using Python. It fetches hotel details such as name, location, price, rating, score, reviews, and booking links, and saves them in a structured CSV file format. The script leverages `requests` and `BeautifulSoup` for web scraping, along with error handling mechanisms and human-like behavior simulation to ensure ethical and efficient scraping.

## Project Overview

### Objective:
To develop a lightweight, reusable web scraper for collecting hotel-related data from Booking.com.

### Features:
- **Data Extraction:** Captures:
  - Hotel Name
  - Location
  - Price (removes currency symbol for consistency)
  - Rating (user rating given to hotels)
  - Score (numerical score assigned to hotels)
  - Review (short descriptions or feedback)
  - Link (URL for booking the hotel)
- **CSV Export:** Saves data in an organized CSV file for analysis.
- **Error Handling:** Manages incomplete or missing data to prevent script crashes.
- **Human-Like Behavior:** Implements random time delays and polite headers to reduce scraping detection.
  
## How It Works

### Code Flow:
1. **User Input:** Provide the target URL and file name for the output.
2. **HTTP Request:** Establish connection using `requests` with appropriate headers.
3. **HTML Parsing:** Utilize `BeautifulSoup` with the `lxml` parser to analyze webpage content.
4. **Data Extraction:** Locate and extract key data points from structured HTML containers.
5. **CSV Writing:** Save the extracted information into a CSV file.
6. **Completion:** Notify the user upon successful scraping.

### Example Workflow:
```bash
Please enter URL: <insert URL>
Please give a file name: hotels_data
⏳ Reading the content...
