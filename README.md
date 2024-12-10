# Zomato Data Scraping Project

A Python project using Selenium to scrape restaurant data from the Zomato website. Extracts details like restaurant names, discounts, famous dishes, locations, ratings, and costs for two, saving the data to a CSV file for analysis.

## Features
- **Dynamic Scraping**: Extract restaurant details from Zomato in real-time.  
- **CSV Export**: Save data in a structured, reusable format.  
- **Reusable Script**: Clear and easy-to-follow script for beginners and professionals.

## Requirements
- **Python**: Version 3.7 or later.  
- **Libraries**: Selenium, Pandas.  
- **Browser**: Google Chrome and ChromeDriver (added to system path).  

## Installation
1. **Clone Repository**:
   ```bash
   git clone https://github.com/yourusername/zomato-scraper.git
   cd zomato-scraper
   ```
2. **Install Dependencies**:
   ```bash
   pip install selenium pandas
   ```
3. **Set Up ChromeDriver**:  
   [Download ChromeDriver](https://chromedriver.chromium.org/downloads) and add it to your system path.

## Usage
Run the script to start scraping:  
```bash
python ZomatoScraper.py
```
The scraped data will be saved to a `Zomato_restaurant_Pune.csv` file in the project directory.

## Example Output
| Restaurant Name | Discount | Famous Dishes    | Location | Rating | Cost for Two |
|-----------------|----------|------------------|----------|--------|--------------|
| Example Bistro  | 20% Off  | Pasta, Pizza     | Baner    | 4.5    | ₹1,200       |

## Disclaimer
This project is for educational purposes only. When scraping, ensure compliance with Zomato's terms of service.

## Contributing
Contributions are welcome! Open issues or submit pull requests to improve the project.
