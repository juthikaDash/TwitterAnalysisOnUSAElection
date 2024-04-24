### Twitter Analysis on USA election

**Author**
Juthika Dash
#### Executive summary
 NLP is a fascinating field of study that deals with processing and analyzing unstructured text data using machine learning algorithms. With the help of libraries such as NLTK and TextBlob, computers can now mathematically process and make sense of language inputs. It's amazing how these tools can help us extract insights from massive amounts of text data that would have otherwise been impossible to analyze manually.
 •	Twitter sentiment analysis analyzes the sentiment or emotion of tweets. It uses natural language processing and machine learning algorithms to classify tweets automatically as positive, negative, or neutral based on their content.  Currently, the US election is a very hot topic and to do a sensitive analysis on election 2024 in the USA is very interesting for me and to many other people as well. 

#### Rationale
Why should anyone care about this question?
Given the current high-profile US election, conducting a sentiment analysis on the 2024 US election would be an intriguing task for me and many others.

#### Research Question
What are you trying to answer?
1. Positive and negative emotions for both Biden and Trump
2. Sensitive Analysis on both of their tweets using traditional nlp models
4. find performance score for traditional model 
3. How to perform better than traditional model?

#### Data Sources
What data will you use to answer you question?
Twitter data typically includes the date, user_id, and tweet content. To extract only the data related to the 2024 US election, Trump or Biden
I used below tweets for both the candidates:
 "https://raw.githubusercontent.com/edvinmolla/dotfiles/master/Trumpall2.csv"
 "https://raw.githubusercontent.com/edvinmolla/dotfiles/master/Bidenall2.csv"

#### Methodology
What methods are you using to answer the question?
I used Tokenization to break down the tweets
Removed the stopwors
Then used Stemming to find out the root of words to get list unique words
Calculated word frequency
visualize the positive and negative emotions used in the tweets. 
In traditional models, I tried using "Naive Bayed" and "Logistic regression" and got test score

#### Results
What did your research find?
naive_bayes model's accuracy  for Trump data= 74.62%
naive_bayes model's accuracy  for Biden data= 40.31%
Logistic regression model's accuracy  for Trump data= 76.74%
Logistic regression model's accuracy  for Biden data= 44.19%
In my conclusion, both naive bayes and LR model, the accuracy is pretty similar for both Trum and Biden tweets. 

#### Next steps
What suggestions do you have for next steps?
I want to add regularization to improve the performance. 
Use improved techniques liuke LAMA2 to compare the score against traditional models. 
More visualization for sensitive analysis

#### Outline of project

- Traditional analysis: https://github.com/juthikaDash/TwitterAnalysisOnUSAElection/blob/master/traditionalNLPAnalysis.ipynb
- Morden NLP technology: #TODO
- Data processing: TODO
- GUI for visualization: TODO
- My README file : https://github.com/juthikaDash/TwitterAnalysisOnUSAElection/blob/master/README.md


##### Contact and Further Information
Below are my reference that I used for this project:
1. https://www.nltk.org/
2. https://medium.com/@aaltanim/introducing-natural-language-processing-nlp-building-a-basic-chatbot-with-nlp-and-incorporating-57bd3ffb63e7
