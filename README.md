# Machine-learning
Sentiment Analysis with Deep Learning using BERT


To achieve that, you have to make the answers more personalized. One way to learn more about the customers you’re talking to is to analyze the polarity of their answers. By polarity here I mean detecting if the sentence (or group of sentences) is written with the intention of being perceived as a positive or negative statement. This means we are facing a binary classification problem. A lot of methods exist to solve this NLP task. I tested some and the one which really outperformed the others was BERT.

Project Structure The hands on project on Sentiment Analysis with Deep Learning using BERT is divided into following tasks:

BERT OVERVIEW BERT (Bidirectionnal Encoder Representations for Transformers) is a “new method of pre-training language representations” developed by Google and released in late 2018 (you can read more about it here). As it is pre-trained on generic datasets (from Wikipedia and BooksCorpus), it can be used to solve different NLP tasks. This includes sentence level classification (as we do here), question answering or token level classification (eg. part of speech tagging), and BERT is able to achieve state-of-the-art performances in many of these tasks.

FINE-TUNING WITH BERT BERT recently provided a tutorial notebook in Python to illustrate how to make sentiment detection in movie reviews. The tutorial notebook is well made and clear, so I won’t go through it in detail — here are just a few thoughts on it. First, the notebook uses the IMDb dataset, that can be downloaded directly from Keras. This dataset contains 50000 movie reviews split in two equal parts, one for training and one for testing. Each dataset is balanced, with 12500 positive reviews and 12500 negative ones.

Task 1: An introduction to some basic theory behind BERT, and the problem we will be using it to solve Task 2: Explore dataset distribution and some basic preprocessing Task 3: Split dataset into training and validation using stratified approach Task 4: Loading pretrained tokenizer to encode our text data into numerical values (tensors) Task 5: Load in pretrained BERT with custom final layer Task 6: Create dataloaders to facilitate batch processing Task 7: Choose and optimizer and scheduler to control training of model Task 8: Design performance metrics for our problem Task 9: Create a training loop to control PyTorch finetuning of BERT using CPU or GPU acceleration Task 10: Load in a pre-saved finetuned BERT model and evaluate its performance, and some final thoughts
this is a small change which can be altered later on by the master of project.
