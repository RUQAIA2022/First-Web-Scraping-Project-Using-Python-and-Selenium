# First-Web-Scraping-Project-Using-Python-and-Selenium

Book Data Scraping Project from "Books to Scrape" Website.

This project uses web scraping techniques to collect book data from [Books to Scrape](https://books.toscrape.com/), a website specifically designed for practicing web scraping.

# Key Features

1. Data Collection: The project extracts the following information for each book:
   - Title
   - Price
   - Availability (In stock/Out of stock)
   - Star rating

2. Data Analysis: The project calculates:
   - Total number of books
   - Average book price

3. **Data Storage**: The data is saved in a CSV file named `books_page1.csv` for later use.

# Technologies Used

- Selenium: For web automation and data collection
- Pandas: For data processing and CSV export
- Python: The main programming language used in the project

## How to Use

1. Ensure requirements are installed:
   ```bash
   pip install selenium pandas
   ```
2. Run the code to start the scraping process.

3. Results will be saved in `books_page1.csv`.

# Expected Output

The script will print the first 5 books with their details, plus:
- Total number of books (20 books on the first page)
- Average book price (approximately £38.05)

# Potential Applications

This project can be extended to:
- Track book prices over time
- Compare book prices across different websites
- Build a book recommendation system

# Notes

- This project is for educational purposes only.
- Please respect the website's terms of service when performing scraping activities.
