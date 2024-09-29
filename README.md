# FLUXA AI

Fluxa is an innovative AI-powered platform designed to help users generate recipes based on the contents of their fridge. By simply uploading a photo of their fridge, Fluxa uses advanced image recognition models to detect the ingredients and suggest relevant recipes. It employs a custom-trained YOLO (You Only Look Once) model to analyze the image and identify ingredients, making it easy to create delicious meals based on what you already have.

<img src="assets/refrigerator.png" alt="Fluxa Logo" width="400"/>

## Features

- **Ingredient Detection**: Utilizes a custom-trained YOLO model to accurately identify the ingredients in a photo of your fridge.
- **Recipe Generation**: Provides recipe recommendations based on detected ingredients, helping users minimize food waste and explore new meal options.
- **User-Friendly Interface**: Easy-to-use web application where users can upload a single image and get real-time recipe suggestions.

## How It Works

1. **Upload an Image**: The user takes a photo of their fridge's contents and uploads it to the platform.
2. **Ingredient Detection**: Fluxa employs a YOLO model to detect and classify the ingredients visible in the image.
3. **Recipe Suggestion**: Using the list of detected ingredients, Fluxa generates a variety of recipes for the user to choose from.

## Model Architecture

The ingredient detection model uses a custom-trained YOLO architecture optimized for identifying common household items and food ingredients. YOLO is a state-of-the-art object detection framework that performs real-time image analysis, making it highly efficient for this use case.

## Deployment

The application is deployed using a combination of Flask for the backend and React for the front end, ensuring a seamless user experience. The backend handles image processing and recipe generation, while the front end provides an intuitive interface for users to interact with.

## Access

The application is available online at [Fluxa](https://www.fluxa.pro/).

## Visual Assets

This project includes logos and visual assets, including a **Medium-size logo** located at `assets/logo.png`.

## License

This project is proprietary and closed-source.

For more information, please contact the project team.
"""
