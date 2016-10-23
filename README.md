## Grouping European Cities by Tourism using K-means Clustering

![](city_clusters.png)

This project using descriptions of tourist attractions in European cities.  Data were previously scraped from Trip Advisor and Wikitravel and stored in json files.

After reading in the data, the text was cleaned to only include English words.  Term frequency over the entire corpus was plotted to identify when a word is overly common or overly rare (appearing only once).  

Words that are too common or too rare are removed, along with words that appear to have no relevant meaning.

Using sklearn's feature_extraction and KMeans tools, the cities are assigned to clusters.

The top words and a sample of the cities are printed for each cluster, and the clusters assignments are plotted on a map of Europe.
