# Twitter-Api-Analysis
Analyzing tweets via the Twiiter Api to determine if this tweet has negative or positive feelings through the words of the tweet and the number of retweets and likes compared to my saved data for negative phrases which Twitter Api get Proccess and classified then the last part is anlaysis then produce a final report in shape of .csv file containing the last report about the tweet from el scale of negativity/postivity   from -10 to 10 based on the tweet and number of retweet. 


# Project - Part 1: Sentiment Classifier
We have provided some synthetic (fake, semi-randomly generated) twitter data in a csv file named project_twitter_data.csv which has the text of a tweet, the number of retweets of that tweet, and the number of replies to that tweet. We have also words that express positive sentiment and negative sentiment, in the files positive_words.txt and negative_words.txt.</br>

Your task is to build a sentiment classifier, which will detect how positive or negative each tweet is. You will create a csv file, which contains columns for the Number of Retweets, Number of Replies, Positive Score (which is how many happy words are in the tweet), Negative Score (which is how many angry words are in the tweet), and the Net Score for each tweet. At the end, you upload the csv file to Excel or Google Sheets, and produce a graph of the Net Score vs Number of Retweets.</br>

To start, define a function called strip_punctuation which takes one parameter, a string which represents a word, and removes characters considered punctuation from everywhere in the word. (Hint: remember the .replace() method for strings.)</br>

Next, copy in your strip_punctuation function and define a function called get_pos which takes one parameter, a string which represents one or more sentences, and calculates how many words in the string are considered positive words. Use the list, positive_words to determine what words will count as positive. The function should return a positive integer - how many occurrences there are of positive words in the text. Note that all of the words in positive_words are lower cased, so you’ll need to convert all the words in the input string to lower case as well.</br>

Next, copy in your strip_punctuation function and define a function called get_neg which takes one parameter, a string which represents one or more sentences, and calculates how many words in the string are considered negative words. Use the list, negative_words to determine what words will count as negative. The function should return a positive integer - how many occurrences there are of negative words in the text. Note that all of the words in negative_words are lower cased, so you’ll need to convert all the words in the input string to lower case as well.</br>

Finally, copy in your previous functions and write code that opens the file project_twitter_data.csv which has the fake generated twitter data (the text of a tweet, the number of retweets of that tweet, and the number of replies to that tweet). Your task is to build a sentiment classifier, which will detect how positive or negative each tweet is. Copy the code from the code windows above, and put that in the top of this code window. Now, you will write code to create a csv file called resulting_data.csv, which contains the Number of Retweets, Number of Replies, Positive Score (which is how many happy words are in the tweet), Negative Score (which is how many angry words are in the tweet), and the Net Score (how positive or negative the text is overall) for each tweet. The file should have those headers in that order. Remember that there is another component to this project. You will upload the csv file to Excel or Google Sheets and produce a graph of the Net Score vs Number of Retweets. Check Coursera for that portion of the assignment, if you’re accessing this textbook from Coursera.</br>

# Project - Part 2: Sentiment Analysis
Instructions for Submission: Using the resulting .csv file from your answers to part one of the Sentiment Classifier project, create a scatterplot of the Number of Retweets vs the Net Score using Excel, Google Sheets, or another software package of your choosing. Review the Introductory video for this project if you are unsure of how the graph should look, approximately. Be sure to correctly label your axes and give it a meaningful title! You will upload a screenshot of your scatterplot for submission, and review 3 other submissions to check other students work.</br>

Review criteria</br>

Instructions for Grading: You will be reviewing other students’ submissions to make sure that they have correctly constructed the scatterplot of Number of Retweets vs Net Score.</br>

For the scatterplot that your peer submitted, you will check to see if the following characteristics are true:</br>

The X axis represents the Net Score. The Y axis represents the Number of Retweets. The data appear as expected.</br>
