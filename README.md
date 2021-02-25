# Fake-News-Detection-using-Python to build a model to accurately classify a piece of news as REAL or FAKE.
The project aims to build a model for detecting fake news from a given dataset.
This high level python undertaking of distinguishing counterfeit news manages phony and genuine news. Utilizing sklearn, we construct a TfidfVectorizer on our dataset. At that point, we introduce a PassiveAggressive Classifier and fit the model. Eventually, the precision score and the disarray lattice disclose to us how well our model admissions.
TF (Term Frequency): The number of times a word appears in a document is its Term Frequency. A higher value means a term appears more often than others, and so, the document is a good match when the term is part of the search terms.

IDF (Inverse Document Frequency): Words that occur many times a document, but also occur many times in many others, may be irrelevant. IDF is a measure of how significant a term is in the entire corpus.

The TfidfVectorizer converts a collection of raw documents into a matrix of TF-IDF features.
Passive Aggressive algorithms are online learning algorithms. Such an algorithm remains passive for a correct classification outcome, and turns aggressive in the event of a miscalculation, updating and adjusting. Unlike most other algorithms, it does not converge. Its purpose is to make updates that correct the loss, causing very little change in the norm of the weight vector.
The dataset we’ll use for this python projecti is called news.csv and this dataset has a shape of 7796×4. The first column identifies the news, the second and third are the title and text, and the fourth column has labels denoting whether the news is REAL or FAKE
