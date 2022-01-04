# Using Neural Networks to Determine Edibility of Mushrooms

This project was inspired by the growing popularity of foraging in the United States. That knowledge combined with the likelihood of food scarcity becoming worse with climate change has given Foraging on Fleek a mission of getting more people into foraging. Foraging on Fleek wants to encourage millennials and gen z to get out and forage for the first time. One of the biggest barriers of entering foraging is the certainty of the edibility of each specimen. By building a neural network that can determine edibility status, I could eventually build an app that can with great certainty determine if a mushroom is edible or not. If I am able to accomplish this it can remove one of the biggest barriers of entry.

# Data and Workflow

This project was based on the growing popularity of foraging. Data was scraped directly from Mushroom World using Selenium and Beautiful Soup. Images and edibility status of 170+ types of mushrooms was gathered with a total of 905 images gathered. Images were resized and split into two sets for both training and validation. 

The baseline neural network preformed with an accuracy of .62, leaving room for improvement. The model was tuned by using transfer learning, various optimizers, adding additional layers and kernels. 

### The Final Model

The final model was a sequential neural network with 16 layers, and a SGD optimizer. The final performance of the model was acceptable with accuracy = .968 recall = .957. This model needs to be improved before being able to deploy an app confidently. 


