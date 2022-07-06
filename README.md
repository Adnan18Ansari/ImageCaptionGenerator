# ImageCaptionGenerator
Caption generation is a challenging artificial intelligence problem where a textual description must be generated for a given photograph i.e. generating captions to describe images. It requires both methods from computer vision to understand the content of the image and a language model from the field of natural language processing to turn the understanding of the image into words in the right order. Model is trained on Flickr8k dataset
## Steps involved :-
Loading the image-data.
Text cleaning - Removal of single-lettered words, removal of punctuations, removal of numbers/digits.
Text processing - Creation of corpus and vocabulary, addition of '<startseq>' and '<endseq>' tags to each of the captions.
Splitting data into train-validation-test sets.
Image Processing and Feature Extraction using Transfer Learning via InceptionV3 model.
Creation of data generator to attach image features and texts together to be fed into the RNN Model.
 
Creation and training of RNN Model.
Generating caption using two methods - greedy search and beam search. Model evaluated using Bleu Scores.
Generating captions for images in the test set.
Developing GUI for interaction using tkinter library.
