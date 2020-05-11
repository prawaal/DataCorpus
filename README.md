# DataCorpus
This contains 3 files on translation mapping - 
English-French
English-German
English-Spanish

The files are tab seperated and can be consumed by anyone

The initial data seed for these files have been created by movies for children. The vocabulary on those movies is designed for people with less exposure to complex words. The same can also been used for people with modest education.

Using this inital seed, and scanning the opus corpus on subttle data we have created this dataset. This is close to 250k mapped sentences.

We have limited to 250k sentenses since using tensor flow and python, this amount of data takes 12 hours to train on colab. Beyond this volume it goes beyond 12 hours which is not possible using colab (on free account).
