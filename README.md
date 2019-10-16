# ML-Comp.-2019-20---Income-Prediction
TCD ML Individual competition 

I was using the kaggel kernel to complete this competition.
Download the code and upload it to the kaggel kernel inorder to run the code.

Inorder to predict the income I used the sklearn machine learning library.

I was using the sklearn pipeline to bind all the preprocessing and normalisations applied to the dataset.

I was using sklearn simple imputer and standard scalar librabry to normalize my numerical instances present in the data set.

And for the categorical instances i was using the sklearn onehot encoding.

Then i used sklearn train and split library to split my dataset to 70% as training and 30% as testing data.

Then i imported the testing dataset and applied the same preprocessing that i have applied to training dataset.

I uesd the model used in training dataset to predict the income values in testing dataset.
