# emojinator
### A simple Emoji Classifier for humans. It will detect the type of Emoji based on the gestures made by our hand using Convolution Neural Network.

## Description:
Emojis are ideograms and smileys used in electronic messages and web pages. Emoji exist in various genres, including facial expressions, common objects, places and types of weather, and animals. They are much like emoticons, but emoji are actual pictures instead of typographics.

## Functionalities:
Filters to detect hand.
CNN for training the model.

## Python Implementation:
Network Used- Convolutional Neural Network.

## Procedure:
First, you have to create a gesture database. For that, run CreateDataset.ipynb. Look at the contour frame and adjust your hand to make sure that you capture the features of your hand. Press 'c' for capturing the images. It will take 1200 images of one gesture. Try moving your hand a little within the frame to make sure that your model doesn't overfit at the time of training.
Repeat this for all the features you want.
Run CreateCSV.ipynb for converting the images to a CSV file
If you want to train the model, run Training.ipynb
Finally, run Emojinator.ipynb for testing your model via webcam.
