# custom model for image classifier
## 1. Before you begin

This codelab will not go into the specifics of how a model is built. Instead, you'll learn about the APIs from TensorFlow Lite Model Maker that make it easy.

If you want more of a general grounding in how custom vision models are created, check out the series "Machine Learning Foundations" on YouTube.

# 2. Get Started

All of the code to follow along has been prepared for you and is available to execute using Google Colab here. If you don't have access to Google Colab, you can clone the repo and use the notebook called CustomImageClassifierModel.ipynb which can be found in the ImageClassificationMobile->colab directory.
![alt text](image.png)

Zip that up and host it on a server, and you'll be able to train models with it. You'll use one that has been prepared for you in the rest of this lab.

This lab will assume you are using Google Colab to train the model. You can find colab at colab.research.google.com. If you're using another environment you may have to install a lot of dependencies, not least TensorFlow.


# 3. Install and import dependencies
Install TensorFlow Lite Model Maker. You can do this with a pip install. The &> /dev/null at the end just suppresses the output. Model Maker outputs a lot of stuff that isn't immediately relevant. It's been suppressed so you can focus on the task at hand.