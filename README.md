<!DOCTYPE html>
<body>
    <h1>Instructions for Mars Data Analysis</h1>
    <h2>Part 1: Scrape Titles and Preview Text from Mars News</h2>
    <p>Open the Jupyter Notebook in the starter code folder named <code>part_1_mars_news.ipynb</code>. Follow the steps below to scrape the Mars News website:</p>
    <ol>
        <li>Use automated browsing to visit the Mars news site. Inspect the page to identify which elements to scrape.</li>
        <li>Create a Beautiful Soup object and use it to extract text elements from the website.</li>
        <li>Extract the titles and preview text of the news articles. Store each title-and-preview pair in a Python dictionary with two keys: <code>title</code> and <code>preview</code>. Store all dictionaries in a Python list.</li>
        <li>Print the list in your notebook.</li>
    </ol>
    <h2>Part 2: Scrape and Analyze Mars Weather Data</h2>
    <p>Open the Jupyter Notebook in the starter code folder named <code>part_2_mars_weather.ipynb</code>. Follow the steps below to scrape and analyze Mars weather data:</p>
    <ol>
        <li>Visit the Mars Temperature Data Site. Inspect the page to identify which elements to scrape.</li>
        <li>Create a Beautiful Soup object and use it to scrape the data in the HTML table.</li>
        <li>Assemble the scraped data into a Pandas DataFrame with appropriate column headings.</li>
        <li>Examine and, if necessary, convert the data types of each column.</li>
        <li>Analyze the dataset to answer various questions about Mars' weather.</li>
        <li>Export the DataFrame to a CSV file.</li>
    </ol>
    <h3>Analysis Questions</h3>
    <ul>
        <li>How many months exist on Mars?</li>
        <li>How many Martian days worth of data exist in the dataset?</li>
        <li>Determine the coldest and the warmest months on Mars.</li>
        <li>Identify which months have the lowest and the highest atmospheric pressure.</li>
        <li>Estimate the number of terrestrial days in a Martian year.</li>
    </ul>

</body>
</html>
