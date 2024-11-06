# Mars_Challenge
# Mars-Challenge
## Part 1: Scrape Titles and Preview Text from Mars News
This project scrapes titles and preview text from Mars News articles using Python.The scraper accesses the Mars News website, extracts article titles and previews, and stores them in a list of dictionaries, providing a structured way to analyze Mars-related news.Optional: Data can be saved to a JSON file for easy sharing or analysis.
Prerequisites: Install the following Python packages:
splinter – for automated browser control
BeautifulSoup from bs4 – for HTML parsing
requests – for HTTP requests
json – for saving data as JSON (optional)
Installation command:
Open the Jupyter Notebook part_1_mars_news.ipynb.
Run each cell in order:
Splinter opens the Mars News website and BeautifulSoup parses the HTML.
Article titles and previews are extracted and stored in a dictionary format with keys title and preview.
Each dictionary is appended to a list.
## Optional: Save data to mars_news.json by running the final cell for later access.
The data list is printed for quick review at the end of the notebook.
The notebook provides a flexible template for web scraping, allowing for adjustments to other sites by modifying the URL and parsing parameters.
## Part 2: Scrape and Analyze Mars Weather Data
## The Mars Weather Analysis:

The Mars Weather Analysis project extracts and analyzes data on Martian temperature and atmospheric pressure over several sols (Martian days). It explores patterns in temperature, atmospheric conditions, and seasonal changes to deepen our understanding of Martian climate.
## Data Collection
Data was scraped from the Mars Temperature Data Site. This dataset includes:

id: Transmission ID from the Curiosity rover.
terrestrial_date: The Earth date of the transmission.
sol: The elapsed sols (Martian days) since Curiosity's landing.
ls: Solar longitude, indicating the position of Mars in its orbit.# Mars-Challenge
## Part 1: Scrape Titles and Preview Text from Mars News
This project scrapes titles and preview text from Mars News articles using Python.The scraper accesses the Mars News website, extracts article titles and previews, and stores them in a list of dictionaries, providing a structured way to analyze Mars-related news.Optional: Data can be saved to a JSON file for easy sharing or analysis.
Prerequisites: Install the following Python packages:
splinter – for automated browser control
BeautifulSoup from bs4 – for HTML parsing
requests – for HTTP requests
json – for saving data as JSON (optional)
Installation command:
Open the Jupyter Notebook part_1_mars_news.ipynb.
Run each cell in order:
Splinter opens the Mars News website and BeautifulSoup parses the HTML.
Article titles and previews are extracted and stored in a dictionary format with keys title and preview.
Each dictionary is appended to a list.
## Optional: Save data to mars_news.json by running the final cell for later access.
The data list is printed for quick review at the end of the notebook.
The notebook provides a flexible template for web scraping, allowing for adjustments to other sites by modifying the URL and parsing parameters.
## Part 2: Scrape and Analyze Mars Weather Data
## The Mars Weather Analysis:

The Mars Weather Analysis project extracts and analyzes data on Martian temperature and atmospheric pressure over several sols (Martian days). It explores patterns in temperature, atmospheric conditions, and seasonal changes to deepen our understanding of Martian climate.
## Data Collection
Data was scraped from the Mars Temperature Data Site. This dataset includes:

id: Transmission ID from the Curiosity rover.
terrestrial_date: The Earth date of the transmission.
sol: The elapsed sols (Martian days) since Curiosity's landing.
ls: Solar longitude, indicating the position of Mars in its orbit.
month: The Martian month.
min_temp: The minimum temperature in Celsius for each sol.
pressure: The atmospheric pressure at Curiosity's location.
## Data Preparation
After scraping, data types were converted as follows to facilitate analysis:
terrestrial_date to datetime
sol, ls, and month to integer
min_temp and pressure to float
Data Analysis
1. Number of Martian Months
Result: There are 12 distinct months on Mars, similar to Earth’s monthly structure.
2. Martian Days (Sols) in the Dataset
Result: The dataset covers data for 1867 sols, providing a comprehensive view of Martian weather over several years.
3. Average Minimum Temperature by Month
The minimum temperature was averaged for each Martian month, revealing patterns in temperature fluctuations.
Visualization: A bar chart displays the coldest and warmest months on Mars, with months 3 and 4 being the coldest.
4. Average Atmospheric Pressure by Month
Atmospheric pressure was averaged by Martian month to explore seasonal pressure variations.
Visualization: A bar chart shows the months with the highest and lowest atmospheric pressures, with month 9 having the highest average pressure.
5. Estimation of Earth Days in a Martian Year
By analyzing temperature cycles over time, an approximate length of a Martian year was determined in Earth days. A plot of daily minimum temperatures aids in identifying the repeating seasonal cycle.
Open part_2_mars_weather.ipynb in Jupyter Notebook.
Execute each cell sequentially to scrape data, process it, and generate visualizations.
Results
The results show:
Seasonal temperature and pressure patterns, with clear distinctions between warmer and colder months.
Estimated length of a Martian year, illustrating the extended seasonal cycles compared to Earth.
month: The Martian month.
min_temp: The minimum temperature in Celsius for each sol.
pressure: The atmospheric pressure at Curiosity's location.
## Data Preparation
After scraping, data types were converted as follows to facilitate analysis:
terrestrial_date to datetime
sol, ls, and month to integer
min_temp and pressure to float
Data Analysis
1. Number of Martian Months
Result: There are 12 distinct months on Mars, similar to Earth’s monthly structure.
2. Martian Days (Sols) in the Dataset
Result: The dataset covers data for 1867 sols, providing a comprehensive view of Martian weather over several years.
3. Average Minimum Temperature by Month
The minimum temperature was averaged for each Martian month, revealing patterns in temperature fluctuations.
Visualization: A bar chart displays the coldest and warmest months on Mars, with months 3 and 4 being the coldest.
4. Average Atmospheric Pressure by Month
Atmospheric pressure was averaged by Martian month to explore seasonal pressure variations.
Visualization: A bar chart shows the months with the highest and lowest atmospheric pressures, with month 9 having the highest average pressure.
5. Estimation of Earth Days in a Martian Year
By analyzing temperature cycles over time, an approximate length of a Martian year was determined in Earth days. A plot of daily minimum temperatures aids in identifying the repeating seasonal cycle.
Open part_2_mars_weather.ipynb in Jupyter Notebook.
Execute each cell sequentially to scrape data, process it, and generate visualizations.
Results
The results show:
Seasonal temperature and pressure patterns, with clear distinctions between warmer and colder months.
Estimated length of a Martian year, illustrating the extended seasonal cycles compared to Earth.






