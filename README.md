## Phone Number Parser

A multithreaded parser written in Python using Selenium that collects phone numbers of apartment listings from [krisha.kz](https://krisha.kz/prodazha/kvartiry/).

##  Disclaimer !
> This tool is developed for **educational purposes only**. 
> The author does not encourage violating the Terms of Use of any website. 

## Features
- Multithreaded scraping with `ThreadPoolExecutor`
- Extracts phone numbers from listings
- Saves results to Excel with autosave support
- Handles pagination and allows custom page limits

## Tech Stack
- `Python 3.8+`
- `Selenium`
- `webdriver-manager`
- `tqdm`
- `openpyxl`

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/krisha-parser.git
   cd krisha-parser
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the parser**:
   ```bash
   python parser.py
   ```

4. **Enter a URL** from krisha.kz (example):
   ```
   https://krisha.kz/prodazha/kvartiry/almaty/
   ```

5. **Specify the number of pages** you want to scrape.

6. **Check the `autosave_results.xlsx`** for results.

   

## Contact
If you found this useful, feel free to connect or contribute!
