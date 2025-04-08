# NLP-project
NLP Unsupervised Clustering Project (Disney Characters)
Summary:

This project performs Natural Language Processing (NLP) on Disney character data obtained through an API. It involves scraping Disney character information, processing the text data, and applying unsupervised machine learning techniques to uncover underlying clusters or groups of characters. The project uses clustering algorithms and visualizations to better understand the patterns and relationships between the characters.

API Dataset Details:

The dataset used in this project is scraped from the Disney API, which provides data on various Disney characters. Each character is associated with several attributes, including their name, unique ID, and the list of films in which they appear.

API Dataset Link:
https://disneyapi.dev/docs/

Fetching API Dataset:
https://api.disneyapi.dev/character?page={page_number}

Project Overview:

The goal of this project is to explore Disney character data from the API and apply an unsupervised learning method, such as K-Means clustering, to identify clusters or groups of Disney characters. The key steps involved include:

Data Acquisition: Scrape character data from the Disney API.
Data Preprocessing: Clean and prepare the text data (i.e., film titles) for analysis.
Feature Extraction: Vectorize the cleaned text using the TfidfVectorizer.
Clustering: Apply K-Means clustering to group similar characters together.
Dimensionality Reduction: Use PCA (Principal Component Analysis) for visualizing the clusters in 2D and 3D.
Analysis: Analyze the resulting clusters and identify the characteristics of each group.
Output and Results:

Clusters: The characters will be grouped into clusters based on their appearances in films.
Visualizations: The clusters will be visualized in 2D and 3D using PCA.
Top Words: For each cluster, the top 10 most frequent words associated with the films will be displayed to help identify the themes or characteristics of the cluster.
Conclusion:

By applying clustering to the Disney character data, we can uncover groups of characters that share similarities in terms of the films they appear in. These clusters can provide insights into potential themes or types of characters in the Disney universe, which can be useful for various applications such as content recommendation or market analysis.
