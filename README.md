# Introduction
In this notebook, you will build a deep neural network that functions as part of an end-to-end machine translation pipeline. Your completed pipeline will accept English text as input and return the French translation.

# Setup

This project requires GPU acceleration to run efficiently. Support is available to use either of the following two methods for accessing GPU-enabled cloud computing resources.

## Udacity Workspaces (Recommended)

Udacity Workspaces provide remote connection to GPU-enabled instances right from the classroom. Refer to the classroom lesson for this project to find an overview of navigating & using Jupyter notebook Workspaces.

## Amazon Web Services (Optional)

Please refer to the Udacity instructions for setting up a GPU instance for this project, and refer to the project instructions in the classroom for setup. The recommended AMI should include compatible versions of all required software and libraries to complete the project. [link for AIND students](https://classroom.udacity.com/nanodegrees/nd889/parts/16cf5df5-73f0-4afa-93a9-de5974257236/modules/53b2a19e-4e29-4ae7-aaf2-33d195dbdeba/lessons/2df3b94c-4f09-476a-8397-e8841b147f84/project)

## Install
- Python 3
- NumPy
- TensorFlow 1.x
- Keras 2.x

# Submission
When you are ready to submit your project, do the following steps:
1. Ensure you pass all points on the [rubric](https://review.udacity.com/#!/rubrics/1004/view).
2. Submit the following in a zip file:
  - `helper.py`
  - `machine_translation.ipynb`
  - `machine_translation.html`

## Converting to HTML

There are several ways to generate an HTML copy of the notebook:

 - Running the last cell of the notebook will export an HTML copy

 - Navigating to **File -> Download as -> HTML (.html)** within the notebook

 - Using `nbconvert` from the command line

    $ pip install nbconvert
    $ nbconvert machine_translation.ipynb





=========================

Meets Specifications
Congratulation on passing the project! 🥳💯🎉

Submitted Files
The following files have been submitted: helper.py, machine_translation.ipynb, machine_translation.html

Awesome! All three files have been submitted successfully.

Preprocess
The function tokenize returns tokenized input and the tokenized class.

Perfect! The tokenize function returns the true tokenized input.

The function pad returns padded input to the correct length.

Fantastic! The pad function returns the correct output.

Models
The function simple_model builds a basic RNN model.

Well done! The submission trained the model for 10 epochs and the validation accuracy ends at 0.6163.

The function embed_model builds a RNN model using word embedding.

Great job! The submission trained the model for 10 epochs and the validation accuracy ends at 0.8407.

The Embedding RNN is trained on the dataset. A prediction using the model on the training dataset is printed in the notebook.

Awesome! The model is trained on the dataset and there is also a prediction using the same model.

The function bd_model builds a bidirectional RNN model.

Great! The bd_model model got trained for 20 epochs and the validation accuracy ends at 0.5987.

The Bidirectional RNN is trained on the dataset. A prediction using the model on the training dataset is printed in the notebook.

Fantastic! The model is trained on the dataset and there is also a prediction using the same model.

The function model_final builds and trains a model that incorporates embedding, and bidirectional RNN using the dataset.

Great job implementing the model_final. The model_final model got trained for 25 epochs and the validation accuracy ends at 0.9790.

Prediction
The final model correctly predicts both sentences.

Well done! The model_final model correctly predicts both sentences.


