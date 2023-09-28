# Beaming Bog 💩 

Beaming Bog is a Python-based web scraping tool inspired by Screaming Frog. This is a command line tool which will scan a website and generate a CSV of the URL, Title, META Description and all H1 and H2 tags on the page.

## Installation

1. **Clone the Repository**
   ```sh git clone https://github.com/olleepalmer/beaming-bog.git
   cd beaming-bog
   ```

2. **Install Dependencies**
   ```sh pip install requests beautifulsoup4
   ```

## :rocket: Usage

1. **Run the Script**
   ```sh python beaming_bog.py
   ```
   
2. **Enter the Starting URL**
   ```sh
   Enter the URL: example.com
   ```

3. **Wait for the Script to Crawl and Scrape the Website**
   The script will print the URL of each scanned page.

4. **Check the Generated CSV File**
   Once the script finishes, a CSV file named `<sanitized_url>_scraped_results.csv` will be generated in the current directory.

