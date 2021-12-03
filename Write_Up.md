# Classifying Mushrooms as Edible or Poisonous using Deep Learning
Emily Ubbelohde

## Abstract
The goal of this project was to use Deep Learning to build a model that successfully classifies mushrooms as either edible or poisonous based on images. 

My next steps to add onto this project would be to build an app that identifies with great certainty if a mushroom is edible or not. This would allow new foragers to forage for mushrooms for the first time with confidence. 

## Design
This project was inspired by the growing popularity of foraging in the United States. That knowledge combined with the likelihood of food scarcity becoming worse with climate change has given Foraging on Fleek a mission of getting more people into foraging. Foraging on Fleek wants to encourage millennials and gen z to get out and forage for the first time. One of the biggest barriers of entering foraging is the certainty of the edibility of each specimen. By building an app that can with great certainty determine if a mushroom is edible or not, it can remove one of the biggest barriers of entry.

## Data
The data I gathered was scraped from Mushroom World using both Selenium and Beautiful Soup. A total of 905 images were scraped. After scraping images were split into a training/validation set of 668 images, and 237 training images. All images were then sorted into edible and inedible classes. 

## Algorithms

- Preprocessing images 
- Categorizing Images
- Resizing all images


**Models**
-------

A simple sequential NN was used to originally get a precision of XX. From there I iterated through many training methods, adding more layers, more filters, and more kernels. Precision and Accuracy did not improve from any of those methods. I then tried transfer learning with various optimizers. Changing the optimizer to SGD gave me the best results with a precision of XX only misclassifying XX poisonous mushrooms as edible.


***Best Model***
------- 

   - The best model was using VGG16 with a transfer learning, and SGD as the optimizer.
   - This gave precision of XX
   

   
## Tools
- Numpy and Pandas for data manipulation
- Tensorflow and Keras for modeling
- MatplotLib and Seaborn for visualizing

## Summary
- The model produced could be improved. The has a total precision of XX. In order to bring an app to market the precision needs to be as close to 100% as possible. This model will need further tuning, and additional data prior to bringing an app to market. 

## Communication
Slides and visuals presented 


