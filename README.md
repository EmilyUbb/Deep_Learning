# Using Neural Networks to Determine Edibility of Mushrooms
Emily Ubbelohde

## Abstract
The goal of this project was to use Deep Learning to build a model that successfully classifies mushrooms as either edible or poisonous based on images. 

My next steps to add onto this project would be to build an app that identifies with great certainty if a mushroom is edible or not. This would allow new foragers to forage for mushrooms for the first time with confidence. 

I created a fictional company, Foragers on Fleek, for communication as well as creating a business use case.

## Design
This project was inspired by the growing popularity of foraging in the United States. That knowledge combined with the likelihood of food scarcity becoming worse with climate change has given Foraging on Fleek a mission of getting more people into foraging. Foraging on Fleek wants to encourage millennials and gen z to get out and forage for the first time. One of the biggest barriers of entering foraging is the certainty of the edibility of each specimen. By building an app that can with great certainty determine if a mushroom is edible or not, it can remove one of the biggest barriers of entry.

## Data
The data I gathered was scraped from Mushroom World using both Selenium and Beautiful Soup. A total of 905 images were scraped. After scraping images were split into a training/validation set of 668 images, and 237 training images. All images were then sorted into edible and inedible classes. 


**Models**
-------

A simple sequential NN was used to originally get a precision of 62%. From there I iterated through many training methods, adding more layers, more filters, and more kernels. In addition I worked with transfer learning and various optimizers. After iterating through many models I determined the best one from those options was a Sequential Neural Network with a total of 16 layers.


***Best Model***
------- 

   - The best model was a sequential NN with nine hidden Convolutional 2D layers, three hidden Max Pooling 2D layers, and two hidden Dense layers.
   - The metrics for the final model were as follows:
      - Precison: 87.85%
      - Recall: 98.19% 
      - F Score: 92.75%

## Model Evaluation
- The model produced could be improved. The has a total precision of 91.9%. In order to bring an app to market the precision needs to be as close to 100% as possible, without sacrificing recall, or the F score. This model will need further tuning, and additional data prior to bringing an app to market. 


