# WikiSentAnalysis
A project in which ml sentiment analysis is used to determine how current events affect the language used on Wikipedia

## Abstract
Sentiment analysis is a powerful tool that can be used to evaluate if a given sample has a positive, negative, or neutral sentiment. Within this paper, a bidirectional RNN trained to analyze sentiment was given sentences  from Wikipedia article revisions over a certain time period corresponding to before and after a major current event which involved the subject in question. Based on the findings, analysis suggests that political issues were more likely to experience a negative shift in sentiment. This sentiment change was often sharp and sudden.

## For use
To make sure main.py and wikiscraper.py function, ensure the following dependencies are installed:

Torch (pip install torch)
Torchmetrics (pip install torchmetrics)
NumPy (pip install numpy)
spaCy (pip install spacy && python -m spacy download en_core_web_lg)
Requests (pip install requests)
BeautifulSoup (pip install beautifulsoup4)

Then, replace all the text within the Python notebooks <THAT LOOKS LIKE THIS> with whatever is necessary (such as file paths, variable names, etc)
