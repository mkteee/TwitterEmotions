# TwitterEmotions

### Uses the BERT-Model to detect emotions from a given tweet-dataset.

__Relevant for the BERT-Model:__
* Sentiment_model\_+\_first_Sensitivity_model.ipynb
&rarr; This runs the sentiment prediction model and the extended sensitivity model (this includes constructing the feats).
* second_Sensitivity_model.ipynb
&rarr; This is just running the basic model on the standard DontTweetThis-dataset.

Note: The according datasets need to be extracted from the "data" folder or be referenced correctly inside the Notebook.

__The other Notebooks are not necessary for the execution, but show some background work:__
* StringCleaningURLandQuotations.ipynb
&rarr; This was used for deleting quotation marks and shorten the URLs.
* StringCleaning.ipynb
&rarr; This was used to manually show the indices of the rows which had abnormally large words.
* StringCleaningURLandQuotations.ipynb
&rarr; This is just to show how the confusion matrix in the report was made.

__Used data is described in another text file inside the data folder.__
