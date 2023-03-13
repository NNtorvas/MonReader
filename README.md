# MonReader

## Background:

The goal of this project is to create a model to determine if the page on the picture is being flipped.

## Data Description:

We collected page flipping video from smart phones and labelled them as flipping and not flipping.

We clipped the videos as short videos and labelled them as flipping or not flipping. The extracted frames are then saved to disk in a sequential order with the following naming structure: VideoID_FrameNumber

## Conclusion:

We have a model with f1-score: 0.99 that can predict if in an image shown, there is a flip of a page.
The fastai library was used and Convolutional neural network as our model.