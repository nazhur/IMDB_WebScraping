# IMDb Top 250 Movies List Web Scraping

## Overview

This project focuses on scraping data from the IMDb website to compile a list of the top 250 movies according to user ratings. The goal is to create a comprehensive dataset that includes essential information about each movie, such as title, release year and ratings.

## Tools Used

The web scraping process is accomplished through the use of three key Python libraries:

1. **Requests**: Utilized for sending HTTP requests to the IMDb website, enabling access to the desired web pages.

2. **BeautifulSoup**: Employed to parse and extract relevant information from the HTML content of the IMDb pages. This library facilitates the navigation and extraction of specific data points.

3. **Pandas**: Used to organize and structure the scraped data into a convenient tabular format. The resulting dataset can be easily manipulated and analyzed for further insights.

## How to Use

To replicate this web scraping project, follow these steps:

1. Clone the repository to your local machine.
   ```bash
   git clone https://github.com/your-username/imdb-top-250-webscraping.git
   ```

2. Install the required Python libraries.
   ```bash
   pip install requests beautifulsoup4 pandas
   ```

3. Run the main Python script.
   ```bash
   python scrape_imdb_top250.py
   ```

   This script initiates the web scraping process, extracting data from the IMDb website and storing it in a Pandas DataFrame.

4. Explore the dataset.
   Once the script completes, you can analyze the generated dataset using Pandas or export it to various formats for further use.

5. Please note, use your User-Agent in the header in requests.get() method, as it will bypass anti-scrape block.
## Notes

- Ensure compliance with IMDb's terms of service and policies while using this script.
- Customize the script according to your specific requirements or add additional features for a more personalized experience.
## Important Note

If  GitHub throws "unable to render the code block" error please use nbviewer to view the code.

## link to nbviewer:
https://nbviewer.org/github/nazhur/IMDB_WebScraping/blob/main/IMDB%20WebScraping%20Project.ipynb

Feel free to contribute to the project by submitting pull requests or reporting any issues you encounter. Happy scraping!
