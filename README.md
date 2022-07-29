# TwitterEmotions

### Uses the Machine Learning BERT-Model to detect emotions from a given tweet-dataset and incorporates this data into a new dataset to test if it is possible to achieve higher accuracy in predicting sensitivity exposure there.

#### This was used to write a report (Exploring the Role of Privacy Exposure in Twitter), which is included as a pdf and has additional information on how this experiment was constructed, executed and evaluated. 

#### Additionally this was further optimized and examined in a published paper: https://doi.org/10.1145/3524010.3539501
\
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
