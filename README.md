<h1 align="center">Sentiment Analysis on Hespress Website Comments</h1>

<p>This project focuses on analyzing the sentiment of comments posted on the Hespress website, a popular news portal in Morocco. Leveraging various technologies and libraries, including web scraping, natural language processing (NLP), and machine learning, the project aims to classify comments into positive, negative, or neutral sentiments.</p>

<h3>Technologies Used:</h3>
<ul>
  <li><strong>Web Scraping:</strong> Utilized the <code>requests</code> library along with <code>BeautifulSoup</code> for extracting comments from the Hespress website.</li>
  <li><strong>Data Processing:</strong> Employed <code>pandas</code> for data manipulation and preprocessing tasks, such as cleaning and organizing the comment data.</li>
  <li><strong>Language Detection:</strong> Integrated the <code>langdetect</code> library to identify the language of comments, facilitating multi-lingual sentiment analysis.</li>
  <li><strong>Tokenization:</strong> Utilized the <code>stanza</code> library for tokenizing comments, a crucial step in preparing text data for sentiment analysis.</li>
  <li><strong>Sentiment Analysis Model:</strong> Leveraged the <code>transformers</code> library to deploy a pre-trained sentiment analysis model (<code>nlptown/bert-base-multilingual-uncased-sentiment</code>), capable of analyzing text in multiple languages.</li>
</ul>

<h3>Workflow Overview:</h3>
<ol>
  <li><strong>Data Collection:</strong> Comments were scraped from the Hespress website using web scraping techniques.</li>
  <li><strong>Preprocessing:</strong> Comments underwent preprocessing steps such as language detection and tokenization to prepare them for sentiment analysis.</li>
  <li><strong>Sentiment Analysis:</strong> A pre-trained sentiment analysis model was applied to classify comments into positive, negative, or neutral sentiments.</li>
  <li><strong>Result Visualization:</strong> Visualized the sentiment analysis results, providing insights into the overall sentiment distribution among the comments.</li>
</ol>

<p>This project serves as a practical demonstration of applied data science techniques, showcasing the process of sentiment analysis on real-world data sourced from online platforms.</p>
