# ImageCaptionGenerator
Steps involved :-
Loading the image-caption mappings.
Text cleaning - Removal of single-lettered words, removal of punctuations, removal of numbers/digits.
Text processing - Creation of corpus and vocabulary, addition of '<startseq>' and '<endseq>' tags to each of the captions.
Splitting data into train-validation-test sets.
Image Processing and Feature Extraction using Transfer Learning via InceptionV3 model.

Creation of data generator to attach image features and texts together to be fed into the RNN Model
Creation of RNN Model
image.png

Training the RNN Model
Generating caption using two methods - greedy search and beam search
Comparing Bleu Scores with beam width varying from 1 to 3.
Generating captions for images in the test set.
