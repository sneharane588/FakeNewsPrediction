# Fake News Prediction
#### To build a model to accurately classify a piece of news as REAL or FAKE.
#### Using sklearn, build a TfidfVectorizer on our dataset. Then, initialize a PassiveAggressive Classifier and fit the model.

There are more than millions of news contents published on the internet every day. If we include the tweets from twitter, then this figure will be increased in multiples. Nowadays, the internet is becoming the biggest source of spreading fake news. A mechanism is required to identify fake news published on the internet so that the readers can be warned accordingly. Some researchers have proposed the methods to identify fake news by analyzing the text data of the news based on the machine learning techniques. Here, we will also discuss the machine learning techniques that can identify fake news correctly.

![python-project-detecting-fake-news](https://user-images.githubusercontent.com/19407823/94550642-b23f8780-0271-11eb-9787-80cc22884555.jpg)

### Dataset

Dataset has a shape of 7796×4. The first column identifies the news, the second and third are the title and text, and the fourth column has labels denoting whether the news is REAL or FAKE.

### What is a TfidfVectorizer?

TF (Term Frequency): The number of times a word appears in a document is its Term Frequency. A higher value means a term appears more often than others, and so, the document is a good match when the term is part of the search terms.

IDF (Inverse Document Frequency): Words that occur many times a document, but also occur many times in many others, may be irrelevant. IDF is a measure of how significant a term is in the entire corpus.

The TfidfVectorizer converts a collection of raw documents into a matrix of TF-IDF features.

### What is a PassiveAggressiveClassifier?

Passive Aggressive algorithms are online learning algorithms. Such an algorithm remains passive for a correct classification outcome, and turns aggressive in the event of a miscalculation, updating and adjusting. Unlike most other algorithms, it does not converge. Its purpose is to make updates that correct the loss, causing very little change in the norm of the weight vector.

