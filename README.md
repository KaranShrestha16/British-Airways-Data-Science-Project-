
# British Airways Sentiment Analysis

## Description
This project involves analyzing customer reviews of British Airways (BA) to understand their experiences and sentiments. The analysis is performed on data scraped from the Skytrax website, focusing on reviews specifically about the airline. The goal is to provide insights that can inform business decisions, improve customer service, and ultimately enhance the customer experience.

## Installation
To replicate this analysis, you need to have the following installed on your system:

- Python (version 3.6 or higher)
- Jupyter Notebook
- Required Python packages (listed in `requirements.txt`)

To install the necessary Python packages, run:
```sh
pip install beautifulsoup4 nltk textblob urllib3 wordcloud matplotlib pandas seaborn requests

```

## Usage
1. **Data Scraping**:
   - The project includes code for scraping customer reviews from the Skytrax website using BeautifulSoup and Requests libraries.
   - Example function: `fetch_html_content(url)` retrieves HTML content, and `parse_reviews(html_content)` parses reviews from the content.

2. **Data Cleaning**:
   - The raw text data is cleaned by removing HTML tags, punctuation, and stopwords, and by tokenizing the text. The NLTK library is used for text processing.

3. **Data Analysis**:
   - **Sentiment Analysis**: Sentiments are analyzed using the TextBlob library to determine the polarity of the reviews.
   - **Word Cloud**: A word cloud is generated to visualize the most frequent terms in the reviews using the WordCloud library.
   - **Statistical Analysis**: Various statistics such as mean, median, standard deviation, and interquartile range of the sentiment scores are computed.

4. **Visualization**:
   - Histograms and box plots are created to visualize the distribution of sentiment scores using Seaborn and Matplotlib.
   - Word clouds visualize the most frequent words in the reviews.

## Data Sources
The primary data source for this project is the [Skytrax](https://www.airlinequality.com/) website, from which customer reviews were scraped.

## Methodology
1. **Web Scraping**: 
   - Extracted reviews using BeautifulSoup to parse HTML and Requests to handle HTTP requests.
2. **Text Preprocessing**: 
   - Used NLTK for tokenization and removal of stopwords.
   - Applied regular expressions for cleaning text data.
3. **Sentiment Analysis**: 
   - Implemented using TextBlob for polarity scoring.
4. **Visualization**: 
   - Created visualizations including word clouds, histograms, and box plots to present data insights.

## Results
Key findings from the analysis include:
- **Sentiment Distribution**: The sentiment scores showed a range of emotions, with visualizations providing insight into overall customer sentiment.
- **Word Cloud**: Highlighted frequent words like "service," "staff," "flight," indicating key areas of customer concern and satisfaction.
- **Statistical Summary**: Provided descriptive statistics on sentiment scores, offering a quantitative summary of customer feedback.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes. For major changes, please open an issue to discuss what you would like to change.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact Information
For any questions or inquiries, please contact:
- Name: Karan Shrestha 	
- Email: karanxhrestha@gmail.com
