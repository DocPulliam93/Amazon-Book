# Audible Best-Seller Scraper

This Python project automates the process of retrieving top-selling audiobook data from Audible. It uses web scraping techniques with Selenium to extract information such as title, author, and length from the Audible best-seller list.

## Features

*   Scrapes multiple pages of best-sellers.
*   Extracts book title, author, and length.
*   Handles common web scraping exceptions (e.g., elements not found, timeouts).
*   Saves the data to a CSV file (`audible_books.csv`).
*   Uses `webdriver-manager` for automatic ChromeDriver management.

## Installation

1.  **Clone the repository:**

    ```bash
    git clone [invalid URL removed]
    ```

    (Replace `YOUR_USERNAME` with your actual GitHub username.)

2.  **Navigate to the project directory:**

    ```bash
    cd audible-best-seller-scraper
    ```

3.  **Create a virtual environment (recommended):**

    ```bash
    python3 -m venv venv  # For Linux/macOS
    python -m venv venv    # For Windows
    ```

4.  **Activate the virtual environment:**

    ```bash
    source venv/bin/activate   # For Linux/macOS
    venv\Scripts\activate      # For Windows
    ```

5.  **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

    (Make sure you have a `requirements.txt` file in your project directory. A sample is provided below.)

## Usage

1.  **Run the script:**

    ```bash
    python audible_scraper.py
    ```

    (Assuming your main script file is named `audible_scraper.py`)

2.  The scraped data will be saved to a file named `audible_books.csv` in the same directory.

## Example `requirements.txt`
