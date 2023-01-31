# My thought process

## What I tried
I immeadiately knew that I wanted to train a machine learning model that could categorize the star type. I had been exploring Python and machine learning over the break and learned about the very basics of Tensorflow and building a neural network, so I initially decided to do that. However, my neural network resulted in very low accuracy, probably because I didn't fully understand neural networks and thus didn't design my neural network very well.

## Next Steps
I decided to explore other options. I decided to go with using a prebuilt, easy-to-use model instead. I looked into the [scikit-learn library](https://scikit-learn.org/stable/auto_examples/index.html#classification), which featured a wide variety of options. I decided that I wanted to try out the decision and the random forest because they were popular options for classification tasks. 

First, I trained a decision tree model on my dataset. It gave me a high accuracy of 97.8%, but I wanted to see if I could get a higher accuracy with random forest. I trained the random forest model and achieved an accuracy of 100%! Very impressive. 

## Using my model
Now that I had a trained model, I decided to test it out a little with my own input. I gave it data describing the sun to see if it would predict a main sequence star type of 3. It did. Yay

## Using another model
Next, I decided to do the suggested task and try and find the line of data most similar to the sun. For that, I used the nearest neighbors class of scikit-learn. I tried first scaling the data before giving it to the model, but actually produced a more accurate result without scaling. And after that, I was done!

# Sources
https://scikit-learn.org/stable/auto_examples/index.html#classification</br>
https://www.geeksforgeeks.org/advantages-and-disadvantages-of-different-classification-models/</br>
https://scikit-learn.org/stable/modules/neighbors.html </br>
https://stackoverflow.com/questions/42092448/accuracy-difference-on-normalization-in-knn

