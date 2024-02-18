# Project Name: Audi Google Reviews Analysis

## Description:
This project aims to scrape Google reviews for Audi dealerships, adjust the reviews by removing translations, and preprocess the data for further analysis. It consists of three Jupyter Notebook files: 
1. `1_Google Reviews Scraping Eng-version.ipynb`: Scrapes Google reviews for Audi dealerships.
2. `2_Adjusting_Reviews.ipynb`: Adjusts the reviews by removing translations and extracts the year from the review date.
3. `3_Preprocessing.ipynb`: Preprocesses the scraped reviews by removing non-English reviews and stopwords.

## File Descriptions:
1. **1_Google Reviews Scraping Eng-version.ipynb:**
   - This file contains Python code to scrape Google reviews for Audi dealerships using Selenium and BeautifulSoup.
   - It extracts review data such as username, description, rating, date, etc., and stores it in an Excel file (`auidi_rew.xlsx`).
   - Selenium is used to automate web browsing, and BeautifulSoup is used for parsing HTML.

2. **2_Adjusting_Reviews.ipynb:**
   - This file adjusts the scraped reviews by removing translations and extracts the year from the review date.
   - It defines functions to check if a review is translated and to adjust the review text accordingly.
   - The adjusted reviews are stored in an Excel file (`audi_reviews_eng_adjusted.xlsx`).

3. **3_Preprocessing.ipynb:**
   - This file preprocesses the scraped reviews by removing non-English reviews and stopwords.
   - It utilizes NLTK and spaCy libraries for text processing tasks such as tokenization, lemmatization, and stopword removal.
   - The preprocessed reviews are stored in a new dataframe.

## Usage:
1. Clone the repository to your local machine:
git clone <repository_url>


2. Navigate to the project directory:
cd <project_directory>


3. Run the Jupyter Notebooks in the following order:
- `1_Google Reviews Scraping Eng-version.ipynb`
- `2_Adjusting_Reviews.ipynb`
- `3_Preprocessing.ipynb`

4. Ensure that you have the necessary input files (e.g., `Audi_url.xlsx`) and that the output files are generated as expected.

## Dependencies:
- Selenium
- BeautifulSoup
- pandas
- numpy
- NLTK
- spaCy

## License:
This project is licensed under the MIT License - see the LICENSE file for details.

## Author:
Mustafa Genc

Feel free to modify and enhance the project as needed. Contributions are welcome!
