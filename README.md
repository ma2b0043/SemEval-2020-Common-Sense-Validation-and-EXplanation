# SemEval-2020-Common-Sense-Validation-and-EXplanation

# Introduction
SemEval 4 Common Sense Explanation and Validation by CodaLab is an ongoing NLP competition in which many people from around the globe have taken
part in the competition . We were offered to choose to choose from the one of the following as our AI semester project
1: SemEval 4 Common Sense Explanation and Validation
2: SentiMix Hindi-English
And I choose the 1st project, due to its challenging aspects and because many few people have successfully completed this project due to its complexity and precision requirements.

# How to run the code
To run my code, you’ll need all of the subtask_A train, dev and test dataset along with their answers. You’ll need to mount your google drive to store the end
results i.e the subtaskA_answer.csv . The code also requires google colab’s cuda gpu to run in 30-40 min depending on the number of epochs in the training dataset.
The notebook contains Sub headings to guide the viewer.

# Implementation
I decided to simpletransformers library to accomplish my task, which is a transformers library having most of the hugging face transformers model.
Simple Transformer models are built with a particular Natural Language Processing (NLP) task in mind. Each such model comes equipped with features and functionality
designed to best fit the task that they are intended to perform. The high-level process of using Simple Transformers models follows the same pattern.
I used the roberta base model for binary text classification. The config I used were mostly the standard configuration of roberat base except for the following:

# Results
The results of my model on dev_set are:
Accuracy: 88.46539618856569
Total Loss: 1.0306488707725294

The results of my model on test_set are:
Accuracy: 87.7
Total Loss: 1.0707464737138652
