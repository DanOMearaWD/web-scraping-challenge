# Mars Data Analysis Project

This project is a web scraping and data analysis exercise focused on Mars. The goal is to scrape data from multiple sources, organize and analyze the information, and draw insights about Martian weather patterns and news.

## Table of Contents

- [Background](#background)
- [Project Files](#project-files)
- [Deliverables](#deliverables)
- [Part 1: Scraping Mars News](#part-1-scraping-mars-news)
- [Part 2: Scraping and Analyzing Mars Weather Data](#part-2-scraping-and-analyzing-mars-weather-data)
- [Analysis and Insights](#analysis-and-insights)
- [Technologies Used](#technologies-used)

## Background

This project applies web scraping techniques to gather data from HTML elements, using Python libraries such as Splinter and Beautiful Soup. The focus is on data collection, organization, and visualization, all aimed at providing insights into Mars' environment.

## Project Files

- **part_1_mars_news.ipynb**: A Jupyter Notebook for scraping Mars news titles and preview text.
- **part_2_mars_weather.ipynb**: A Jupyter Notebook for scraping and analyzing Mars weather data.
- **data.csv**: The cleaned and processed weather data saved in a CSV file.

## Deliverables

1. **Deliverable 1**: Scrape titles and preview text from Mars news articles.
2. **Deliverable 2**: Scrape and analyze Mars weather data.

## Part 1: Scraping Mars News

In `part_1_mars_news.ipynb`, the following tasks are completed:

- Automated browsing using Splinter to visit the [Mars news site](URL).
- Use Beautiful Soup to extract the titles and preview text of news articles.
- Store the data in a list of dictionaries, each containing a `title` and `preview` key.

**Example Output:**

```python
{
    'title': "NASA's MAVEN Observes Martian Light Show Caused by Major Solar Storm",
    'preview': "For the first time in its eight years orbiting Mars, NASA’s MAVEN mission witnessed two different types of ultraviolet aurorae simultaneously, the result of solar storms that began on Aug. 27."
}
```


# Mars Weather Data Analysis

## Part 2: Scraping and Analyzing Mars Weather Data

This project involves scraping Mars temperature data from the Mars Temperature Data Site and conducting an analysis to understand Martian weather patterns. The analysis is completed in the `part_2_mars_weather.ipynb` notebook, which includes the following tasks:

### Tasks Completed

1. **Automated Browsing**: Used automated browsing to scrape Mars temperature data.
2. **Data Extraction**: Utilized Beautiful Soup to extract HTML table data and convert it into a Pandas DataFrame.
3. **Data Cleaning**: Cleaned and converted data to appropriate data types for analysis.
4. **Key Analysis**:
   - Determined the number of months on Mars.
   - Calculated the total number of Martian days with recorded data.
   - Identified the months with the lowest and highest temperatures.
   - Found the months with the lowest and highest atmospheric pressures.
   - Estimated the approximate length of a Martian year in Earth days.

### Analysis and Insights

- **Minimum Temperature**:
  - **Coldest Month**: March, with an average temperature of -83.31°F, highlights Mars' extreme winter conditions.
  - **Warmest Month**: August, averaging -68.38°F, still demonstrates the cold and harsh Martian environment.

- **Atmospheric Pressure**:
  - **Lowest Pressure**: June, with an average pressure of 745.05, suggesting significant seasonal variation.
  - **Highest Pressure**: September, with an average pressure of 913.31, indicating atmospheric changes on Mars.

- **Year Length**: 
  - The analysis of temperature patterns reveals that a Martian year is approximately 730 Earth days, with a 6% margin of error compared to NASA's official value of 687 days.

### Technologies Used

- **Python**: Core programming language for data analysis and web scraping.
- **Jupyter Notebook**: Interactive environment for writing and testing code.
- **Beautiful Soup**: Library for extracting data from HTML and XML files.
- **Splinter**: Tool for automated browsing.
- **Pandas**: Data analysis and manipulation library.
- **Matplotlib**: Library for creating visualizations.

## Conclusion

This analysis provides valuable insights into Martian weather patterns and helps in understanding the extreme conditions on Mars. The combination of web scraping and data analysis techniques allows for a comprehensive examination of the collected data.
