##Welcome to My Mr_Clean project
##Task
Getting the Data: The script uses the Wikipedia API to retrieve the content of the specified article.
Cleaning: The retrieved content is cleaned to remove markup, URLs, and other irrelevant characters.
Tokenization: The cleaned text is tokenized into individual words.
Term Frequency: The frequency of each word is counted, and stopwords are removed to focus on meaningful words.
Visualizing: Finally, a bar chart is generated to visualize the frequency distribution of the top 25 most frequent words.

##Description
This Project analyzes the word frequency distribution in a Wikipedia article. It retrieves the content of the specified article from Wikipedia, cleans and tokenizes the text, and then generates a visualization of the top 25 most frequent words, excluding common English stopwords.

##Installation
Make sure you have Python installed (version 3.6 or higher).
Install the required Python packages using pip:
Importing Libraries:
re: This module provides regular expression matching operations.
requests: This library is used to send HTTP requests to the Wikipedia website.
numpy: NumPy is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a collection of mathematical functions to operate on these arrays.
matplotlib.pyplot: This module provides a MATLAB-like plotting framework.
seaborn: Seaborn is a Python visualization library based on matplotlib. It provides a high-level interface for drawing attractive statistical graphics.
bs4 (Beautiful Soup): This library is used for pulling data out of HTML and XML files.
Counter (from collections): This class is used to count hashable objects.
nltk: NLTK (Natural Language Toolkit) is a leading platform for building Python programs to work with human language data.

##Usage
Clone or download the script wikipedia_article_analyzer.py to your local machine.
Open a terminal or command prompt.
Navigate to the directory where the script is located.
Run the script 
