# Sentiment-Analysis-and-QA
  
  Sentiment analysis is a common NLP task, which involves classifying texts or parts of texts into a pre-defined sentiments. A large amount of unstructered data that is gathered from news articles, posts on social media. We have a large amount of text which can be classified into variety of  sentiments like anger, joy, fear and so on.
Given the test we first fount the releveant segemnts in the text or selected text that provides us with correct sentiment of the whole text.
For example "i do feel that running is a divine experience and that i can expect to have some type of spiritual encounter". This is an joyful statement which can be clearly stated from the words divine experience. We used "DistilBERT" to find that relevant text and it was able to predict it. It produced the result "i do feel that running is a divine experience".
  
  Then use GRU arhictecture to predict the right sentiments based on the sentence.
  
