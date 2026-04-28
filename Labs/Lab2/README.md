# Lab 2 – Putting an AI Model on a Simulated Edge Device

## What I Did
In this lab, I implemented and deployed a simple neural network model using Google Colab. I trained the model using the MNIST dataset, then saved it and converted it into TensorFlow Lite format to simulate deployment on an edge device. I also tested the model by running inference using the TensorFlow Lite interpreter.

## What I Learned
This lab helped me understand the full process of deploying an AI model, not just training it. I learned how to:
- Set up and verify the development environment (Python and TensorFlow versions)
- Build and train a neural network model
- Convert a trained model into TensorFlow Lite format for edge devices
- Use a TensorFlow Lite interpreter to run predictions
- Understand the difference between training and deployment in real-world systems

I also learned how AI systems can operate on devices with limited resources, which is important for applications like smartphones, IoT devices, and security systems.

## Challenges
One challenge I faced was understanding warnings during model creation and interpreter setup. At first, I thought the warnings meant something was wrong, but I learned that some warnings (like deprecation or input shape warnings) do not stop the program from working.

Another challenge was understanding how to properly convert and run the model in TensorFlow Lite format. However, once I followed the steps carefully, the process worked correctly.

## Results
The model successfully trained with a high accuracy of around 97%, and I was able to convert it to TensorFlow Lite format. The model correctly predicted test images during inference, confirming that the full pipeline—from training to deployment—worked as expected :contentReference[oaicite:0]{index=0}.

## Summary
Overall, this lab strengthened my understanding of the complete AI deployment pipeline. I learned that building a model is only one part of the process, and that preparing it for real-world use on edge devices is equally important.
