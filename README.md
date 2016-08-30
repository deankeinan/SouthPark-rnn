# SouthPark-rnn
## Feeding a neural network 19 seasons of South Park

###Acknowledgments
This was my first time experimenting with anything machine learning and couldn't have been done without [torch-rnn](https://github.com/jcjohnson/torch-rnn), the help of this guide [here](http://www.jeffreythompson.org/blog/2016/03/25/torch-rnn-mac-install/) and of course the massive collection of data cleaned and compiled by Bob Adams [here](https://github.com/BobAdamsEE/SouthParkData).

### First attempt
After a series of hiccups setting up torch-rnn on my macbook, I decided to put it to the test and trained it on a single season of South Park at first. The results were hardly coherent with the occasional whole word or phrase shining through.

### Training a model on 19 Seasons
This took roughly 7 hours without enabling GPU acceleration. It didn't melt my macbook thankfully, and in fact I think I could have been using it to do other things dduring the process. But, for the sake of speed I just left it alone while it ran through the text.

