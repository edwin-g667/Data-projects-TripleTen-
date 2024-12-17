# Machine Learning for Texts Project

## Description
The Film Junky Union, a new edgy community for classic movie enthusiasts, is developing a system for filtering and categorizing movie reviews. The goal is to train a model to automatically detect negative reviews. You'll be using a dataset of IMBD movie reviews with polarity labelling to build a model for classifying positive and negative reviews. It will need to have an F1 score of at least 0.85. 

- Model 1 did well overall however, it struggled to give some obviously good reviews a higher score. 
for example: (0.53: i was really fascinated with the movie)
what model 1 did not struggle with was making sure the bad reviews had really low scores with the highest scoring bad review being 0.16.
example:(0.16: well i was bored and felt asleep in the middle of the movie)

- Model 3 did not do as well it struggled way more with negative and positive reviews even mistakenly labeling a good review as bad.
example:(0.19:  i didn t expect the reboot to be so good writers really cared about the source material)

- Model 4 was horrible at identifying negative reviews showing signs of possible overfitting toward positive reviews which leads to question if it was actually able to predict the positive reviews or just shotgunned positive labels on a majority of the reviews.
## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Contact Information](#contact_information)
## Installation
1. Clone the repo
   
bash
   git clone https://github.com/yourusername/projectname.git
   
2. Install dependencies
   
bash
   npm install
   
## Usage
To start the application, run:
bash
npm start

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Contact Information
https://github.com/edwin-g667
