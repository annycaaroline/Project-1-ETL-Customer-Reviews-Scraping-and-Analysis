### ETL Project Overview: 

This project scrapes customer reviews of British Airways from airlinequality.com, processes the data, and creates visualizations to analyze customer reviews.

Web Scraping:  

  - Uses Python requests and BeautifulSoup to scrape data from the web (​https://www.airlinequality.com/airline-reviews/british-airways​/).
  - Method:  
    - Fetch page HTML using requests.
    - Parse review list to extract all review URLs with BeautifulSoup.
    - Visit each review URL to scrape:
      - Review text content.
      - Metadata (reviews, published data, origin customers, etc.)
        
Data Pipeline:

  - Collected data saved as local CSV files.
  - Stored in MongoDB for extraction, filtering and cleaning.
  - Data cleaning performed with Pandas and NumPy.
  -  Structured data stored in Neon PostgreSQL for analysis.

Visualization:
- Visualizations with Matplotlib and Seaborn.
- Interactive visualizations using Plotly. 

### Required Technologies 

- Python 3.13.2
- MongoDB
- PostgreSQL (Neon)
- Virtual environment tool (conda) 
