Adversarial Image Generation using FGSM

This Python script demonstrates the generation of adversarial images using the Fast Gradient Sign Method (FGSM) on a pre-trained MobileNetV2 model. The script loads a local image, applies FGSM to perturb the image, and visualizes the original and perturbed images along with the model predictions.
Prerequisites

Ensure you have the following libraries installed:

bash

pip install tensorflow matplotlib

Usage

    Open the script in a Python environment.
    Update the image_path variable with the path to your local image file.
    Run the script.

The script will display the original image, model predictions, and a set of perturbed images with varying epsilon values.
Description

    The script uses TensorFlow and Matplotlib for image processing and visualization.
    MobileNetV2, a pre-trained model, is employed for image classification.
    The Fast Gradient Sign Method (FGSM) is used to generate adversarial perturbations on the input image.
    The script visualizes the original image, model predictions, and perturbed images to showcase the impact of adversarial attacks.

Feel free to experiment with different epsilon values to observe the varying degrees of perturbation and their effects on the model predictions.

Note: Make sure the specified image path is valid and points to a local image file.
