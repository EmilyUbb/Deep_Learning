# Using Neural Networks to Identify Edibility of Mushrooms

This project was based on the growing popularity of foraging. Data was scraped directly from Mushroom World using Selenium and Beautiful Soup. Images and edibility status of 170+ types of mushrooms was gathered with a total of 905 images gathered. Images were resized and split into two sets for both training and validation. 

The baseline neural network preformed with an accuracy of .62, leaving room for improvement. The model was tuned by using transfer learning, various optimizers, adding additional layers and kernels. 

### The Final Model

The final model was a sequential neural network with 16 layers, and a SGD optimizer. The final performance of the model was acceptable with accuracy = .968 recall = .957.


