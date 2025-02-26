# mars-challenge

## Overview

This project involves web scraping and data analysis using Python, BeautifulSoup, Splinter, and Pandas. You will collect and analyze data from two different sources related to Mars:

1. **Mars News Articles** – Scraping article titles and previews.
2. **Mars Weather Data** – Scraping, analyzing, and visualizing weather data.

By completing this challenge, you will enhance your skills in web scraping, data organization, and visualization.

---

## Deliverables

### **Deliverable 1: Scrape Mars News Titles and Previews**
- Use **Splinter** to automate browsing and access the Mars News website.
- Extract article titles and preview text using **BeautifulSoup**.
- Store the scraped data as a list of dictionaries, each containing:
  ```python
  {'title': "Article Title", 'preview': "Article preview text"}

  Print the list in Jupyter Notebook.
Optionally, export the results to a JSON file.
File: part_1_mars_news.ipynb

### **Deliverable 2: Scrape and Analyze Mars Weather Data**
- Use Splinter and BeautifulSoup to scrape the Mars weather table.
- Convert the extracted data into a Pandas DataFrame with appropriate column headers and data types:
  - id: Transmission ID
  - terrestrial_date: Earth date
  - sol: Martian day count
  - ls: Solar longitude
  - month: Martian month
  - min_temp: Minimum temperature (°C)
  - pressure: Atmospheric pressure
- Perform data analysis:
  - Count the number of months on Mars.
  - Determine how many Martian days are represented in the dataset.
  - Identify the coldest and warmest months (by average min temp) and visualize them with a bar chart.
  - Identify the months with the highest and lowest atmospheric pressure and visualize them with a bar chart.
  - Estimate the number of terrestrial days in a Martian year using a temperature plot.
  - Export the DataFrame to a CSV file.

### **Technologies Used:**
- Python – General scripting and data manipulation.
- Jupyter Notebook – Running and documenting code.
- Splinter – Automated web browsing.
- BeautifulSoup – HTML parsing for web scraping.
- Pandas – Data manipulation and analysis.
- Matplotlib – Data visualization.

### **Instructions**

1. Set Up Your Environment
Before running the code, ensure you have the necessary dependencies installed:
pip install splinter beautifulsoup4 pandas matplotlib

2. Run the Notebooks
Execute the Jupyter Notebooks in the following order:
  - Run part_1_mars_news.ipynb
    - Opens the Mars News website, scrapes article titles and previews, and stores them in a structured format.
  - Run part_2_mars_weather.ipynb
    - Opens the Mars Temperature Data site, extracts weather data, and performs data analysis.
Expected Outputs

Mars News Scraping
List of dictionaries containing news article titles and previews.
Optional: JSON file export.
Mars Weather Scraping and Analysis
DataFrame with structured Mars weather data.
Answers to analysis questions:
Number of Mars months and days in dataset.
Coldest and warmest months (bar chart).
Lowest and highest atmospheric pressure months (bar chart).
Estimated number of Earth days in a Martian year (temperature plot).
CSV file export of the DataFrame.

### **Notes:**
- This project focuses on web scraping best practices and data visualization.
- Ensure your ChromeDriver or preferred web driver is correctly set up for Splinter.
