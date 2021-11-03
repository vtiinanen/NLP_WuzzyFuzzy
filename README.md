# README
- To install all the needed dependencies
```
python -m pip install -r requirements-with-version.txt
´´´
- To scrape the data, run request_scrape.ipynb and/or selenium_scrape.ipynb[1] notebooks, these will create the request scrapes for Google, BBC and The Register and selenium scrape for Google.
- Manually scraped data can be downloaded by loading the NLP_Carbon_Footprint_Google.csv file.
- To run the program, run the Processing.ipynb notebook. 
- Processing.ipynb contains all the functions to process and visualize of the data

[1] Selenium requires following debian packages 
- psmisc
- chromium-driver=90.0.4430.212-1~deb10u1
see further details from init.ipynb
