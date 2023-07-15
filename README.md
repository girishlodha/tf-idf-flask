# Leetcode Question Search

This project aims to scrape Leetcode, a popular coding platform, to extract a large number of questions and provide a search interface for users to find relevant questions based on input keywords. The web scraping is performed using Python with the help of BeautifulSoup and Selenium libraries, while the TF-IDF algorithm is utilized to rank the importance of keywords in the scraped questions. The project also includes a web interface implemented using Flask, enabling users to search for questions efficiently.

## Features

- Scrapes over 2000 questions from Leetcode using web scraping techniques
- Retrieves, comprehends, and processes question data from Leetcode web pages
- Utilizes BeautifulSoup and Selenium libraries for efficient web scraping
- Implements the TF-IDF algorithm to analyze and rank the importance of keywords in the scraped questions
- Provides a user-friendly web interface for searching relevant Leetcode questions
- Enables searching for questions based on input keywords
- Returns a list of matching questions ranked by their relevance to the input keywords

## Requirements

To run this project locally, make sure you have the following dependencies installed:

- Python 3.7 or higher
- BeautifulSoup 4
- Selenium
- Flask

You can install these dependencies using the following command:

```shell
pip install beautifulsoup4 selenium flask
```

You will also need the appropriate web drivers for Selenium to interact with your preferred web browser. Make sure to download the compatible driver and add it to your system's PATH.

## Usage

1. Clone the repository and navigate to the project directory.

```shell
git clone https://github.com/your-username/leetcode-question-search.git
cd leetcode-question-search
```

2. Run the `app.py` file to start the Flask web server.

```shell
python app.py
```

3. Open your web browser and go to `http://localhost:5000` to access the web interface.

4. Enter your desired keywords in the search bar and click the "Search" button.

5. The application will display a list of Leetcode questions related to the input keywords, ranked by relevance.

## Credits

This project was created by [Your Name] as a demonstration of web scraping techniques, natural language processing, and web development using Python.

## Disclaimer

This project is intended for educational purposes only. The scraping of websites may violate their terms of service, so please ensure that you comply with the relevant terms and policies. The creators of this project take no responsibility for any misuse or unethical use of the provided code.
