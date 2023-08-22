![line](https://media.cnn.com/api/v1/images/stellar/prod/230614113409-curiosity-marker-band-valley.jpg?c=original&q=w_1280,c_fill)
# Exploring Mars: Scraping and Analyzing News and Weather Data
This repository showcases a project that leverages Beautiful Soup, Splinter, and Pandas for data scraping, analysis, and visualization of Mars news and weather data.
1111111111111111111111111

## Project Overview

This project comprises two main components: the first part involves news scraping, while the second part focuses on collecting Mars weather data as a data frame and performing analysis on it.

### Part 1: Scraping Mars News: Unveiling the Mysteries

In this part, we'll gather the Mars news titles and summaries with Python, Splinter, and Beautiful Soup, saving them in a user-friendly  [JSON file](https://github.com/MahsaBakhtiari/data_scraping_challenge/blob/main/Resources/news.json) for easy access. 
The news data will be sourced from the website: [Mars News](https://website-name.com)


### Part 2: Unearthing Mars Weather Data: Gathering and Analyzing the Climate

We'll explore the Mars climate using Python, Splinter, Beautiful Soup, and Pandas visualizations. Highlights include:

- First, we'll scrape Mars weather data [Mars weather](https://static.bc-edx.com/data/web/mars_facts/temperature.html) and transform it into a convenient data frame.

- After analyzing the data frame turns out that Mars, like Earth, has approximately 12 months in a Martian year.

- There is 1867 Martian (not Earth) days' worth of data in the scraped dataset.
  

- Monthly weather on Mars: 
![line1](https://github.com/MahsaBakhtiari/data_scraping_challenge/blob/main/Resources/bar-plot1.png)
*On Mars, on average, the months of the Martian calendar equivalent to the 8th and 9th months are the coldest.*

- Coldest and hottest months at Curiosity's location.:
![line2](https://github.com/MahsaBakhtiari/data_scraping_challenge/blob/main/Resources/bar-plot2.png)
*On Mars, the 8th month of the Martian calendar is typically the coldest, while the 3rd month tends to be the hottest on average.*

- Average Martian monthly pressure:
![line3](https://github.com/MahsaBakhtiari/data_scraping_challenge/blob/main/Resources/bar-plot3.png)
*Average atmospheric pressure is lowest in the sixth month and highest in the ninth.*

- Estimating Earth days in a Martian year using peak-to-peak daily minimum temperatures:
![line3](https://github.com/MahsaBakhtiari/data_scraping_challenge/blob/main/Resources/line-plot.png)
*Mars' year is approximately 675 days based on the plot's peak-to-peak distance of around 1425-750, which is 675 days.*

- Exporting the scraped Mars weather dataframe to a [CSV file](https://github.com/MahsaBakhtiari/data_scraping_challenge/blob/main/Resources/data.csv).

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvement, please submit a pull  request or open an issue on the GitHub repository.

## Resources

- https://www.geeksforgeeks.org/python-encode-unicode-and-non-ascii-characters-into-json/
- https://matplotlib.org/2.0.2/examples/color/colormaps_reference.html
- https://stackoverflow.com/questions/25146121/extracting-just-month-and-year-separately-from-pandas-datetime-column
- https://stackoverflow.com/questions/23357798/how-to-draw-grid-lines-behind-matplotlib-bar-graph
