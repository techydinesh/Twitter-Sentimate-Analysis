# twitter_sentiment_analysis
twitter sentiment analysis using various classification methods

The file name starting with final is the final notebook please review it


Datset contains nearly 31k tweets along with the tweet and the label associated with them
here label 1 means tweet is racist/sexist and label 0 means it is not raicist/sexist
library used pandas, numpy ,matplotlib.pyplot,seaborn for the general text pre-processing and operation on the datset
then imported string,nltk and regular expression(re) from nltk for text preprocessing
text preprocessing involved removal of special words like words containing @ and added a new column into the origional datset
then replaced the characters apart from A-Z and a-z.
split the whole tweet into individual word by applying lambda function
then apply stemming on each word to reduce the number of words
now join all the individual words to make a single clean and preprocessed sentenceand further add all clean tweets to make a single string
data visualization is done using wordCloud here the size of word represents the frequency of apearance of that words in the positve and negative tweets list and plot using matplotlib
now extract the hashtags from the indiviadul tweets to analyse the unique tweet hashtag in diffrent types of tweets
now we will make a frequency dataframe for each words by using nltk.freqDist for poritive as well as negative tweets hashtags
visualize the top15 tweets based on the frequency of that hashtag on barplot of seaborn library
we will now do feature extraction by using bag of words and also usinf TF-IDF to obtain a vector crossponding to each word
now we will split our data into train and test having 20% data as test data
now we have applied diffrent diffrent classification model and compared its accuracy and f1 score and classifiction report
model applied are logistic regression,gradientboosting classifier ,SVC, naive bias 



