# Wildfire-detector

This machine learning app detects fire by looking at a photo and notice if there is fire or not.

The problem is Wildfires spread fast, and spotting them early matters. The idea is to let a model check images and raise a flag when it sees fire, so a person does not have to look through every picture.

## How it works

1. You upload a photo, or pick one of the example images.
2. You click Submit.
3. The trained model analyses the image and gives a result such as **WILDFIRE DETECTED**, together with a confidence percentage.
4. The Flag button lets you mark results that look wrong, so they can be reviewed later.

The app can make mistakes, so always double check the result. This is a small prototype.

## Demo

The demo video tests the app with forest and trail photos, where no fire should be found, and with burning-forest photos, where it detects a wildfire.

## Tools

Python, a trained image classification model, and a simple web interface for testing.
