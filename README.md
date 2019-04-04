# Text-Summariser
Required Modules:
1.Beautiful soup
2.urllib
3.lxml

We scrap all the paragraphs of a wikipedia articles and try to find the summary of that.

STEPS:


We then use the urlopen function from the urllib.request utility to scrape the data
To parse the data, we use BeautifulSoup object and pass it the scraped data object i.e. article and the lxml parser.
Removing Square Brackets and Extra Spaces
Removing special characters and digits
Converting Text To Sentences
Find Weighted Frequency of Occurrence
calculate the scores for each sentence by adding weighted frequencies of the words that occur in that particular sentence.
To summarize the article, we can take top N sentences with the highest scores.
