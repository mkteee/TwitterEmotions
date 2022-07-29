Explanation of files:

1. train_original.csv - The original WASSA-dataset, which was given to me and where the string-cleaning operations where executed on.

Cleaning "train_original" through automatic (URL and quotation removal) and manual (@USERNAME shortenage) lead to the second file:

2. train_cleanFull3.csv - The WASSA-dataset cleaned. THIS WAS USED IN THE CODE, so if you execute the code, this version should be used. 

3. experiment.tsv - The original dataset from the DontTweetThis-Paper. The basic classifier was used on this dataset.

4. experiment_withFeats.tsv - The extended dataset with the predicted sentiments. This was used by the extended classifier.