# Flipkart Web Scraping

This repository contains a Jupyter Notebook that demonstrates how to scrape product information from Flipkart using BeautifulSoup and Requests libraries.

## Files
- `webscraping_flipkart.ipynb`: The main Jupyter Notebook containing the code for web scraping product details such as the title and price from Flipkart.

## Dependencies
- Python 3.x
- BeautifulSoup4
- Requests
- smtplib (for sending email notifications)

You can install the required packages using:
```bash
pip install beautifulsoup4 requests
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/Flipkart_Web_Scraping.git
   ```
2. Navigate to the directory:
   ```bash
   cd Flipkart_Web_Scraping
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook webscraping_flipkart.ipynb
   ```
4. Update the URL and headers in the notebook to the product page you wish to scrape.
5. Run all cells to scrape product details and print the output.

## Functionality
- Connects to a specified Flipkart product page.
- Extracts the product title and price.
- Displays the extracted information.
