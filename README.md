<!-- Your Project title, make it sound catchy! -->

# Classification of Text according to the Cooperative Patent Classification System using natural language processing algorithms

<!-- Provide a short description to your project -->

## Description

There were 188,600 European patent applications made in 2021 (direct European applications and international (PCT) applications that entered the European phase). 

The European Patent Office (EPO) has shown that there is interest from several governmental agencies in trends associated with the filings of patents to specific areas such as ‘Green Plastics’.

Hence, there is a need for quick and robust methods of accurately classifying the plethora of patents being submitted to the EPO to highlight any trends in ‘Green Plastics’ filings, or filings in any other areas of interest (e.g., renewable energies, artificial intelligence, augmented reality, drug discovery etc.)

By employing artificial intelligence, in the form of machine learning, the cost, and likelihood of misclassification of patents, in any technical area, can be significantly reduced, while speeding up the process.
<!-- What should the students going through your exemplar learn -->

## Learning Outcomes

### What you'll learn from each Notebook:

#### Introduction

- Why we need to classify patents.
- What is Tensorflow?
- Loading datasets into your workspace.
- What Tokenisation, Vectorisation and Word Embeddings are in the context of NLP.
- Methods to analyse and understand a dataset.
- Training a model using the Term-Frequency - Inverse Document Frequency (TF-IDF) vectorisation technique with a Multinomial Bayes algorithm.

#### Multi-Layer Perceptron

- What a MultiLayer Perceptron is, and how they can be used for text classification.
- How to train a Multilayer Perceptron using Tensorflow's Keras.
- Making predictions using a Multilayer Perceptron.
- What are hyperparameters and how do they affect the training and performance of machine learning models.
- Optimise a model's training pipeline using Callbacks
- Visualise a model and plotting training loss curves.
- Visualising the structure of a compiled model.
- Evaluating the performance of a MultiLayer Perceptron.

#### Long Short Term Memory Networks (LSTMs)

- What a LSTM is, and how they can be used for text classification.
- How to train a LSTM using Tensorflow's Keras.
- Evaluating the performance of the LSTM.

#### One-Dimensional Convolutional Neural Networks (1D-CNN)

- What a 1D-CNN is, and how they can be used for text classification.
- How to train a 1D-CNN using Tensorflow's Keras.
- Evaluating the performance of the 1D-CNN.

#### Transformers

- What a Transformer is, and how they can be used for text classification.
- How to train a Transformer using Tensorflow's Keras and Object Oriented Programming.
- Evaluating the performance of the Transformer.

| Task       | Time    |
| ---------- | ------- |
| Reading    | 20 hours |
| Practising | 20 hours |

## Requirements

It would help a lot if you went through the following Graduate School courses before going through this exemplar:

Data Exploration and Visualisation:

https://www.imperial.ac.uk/students/academic-support/graduate-school/students/doctoral/professional-development/research-computing-data-science/courses/data-exploration-visualisation/

Data Processing with Python Pandas:

https://www.imperial.ac.uk/students/academic-support/graduate-school/students/doctoral/professional-development/research-computing-data-science/courses/data-processing-python-pandas/

Plotting in Python with Matplotlib:

https://www.imperial.ac.uk/students/academic-support/graduate-school/students/doctoral/professional-development/research-computing-data-science/courses/plotting-in-python-with-matplotlib/


### Academic


- Access to Google Colaboratory
- Basic Math (matrices, averages)
- Programming skills (python, pandas, numpy, tensorflow)
- Machine learning theory (at level of intro to machine learning course)

<!--### System

Instructions on how the student should start going through the exemplar.

Structure this section as you see fit but try to be clear, concise and accurate
when writing your instructions.

For example:
Start by watching the introduction video,
then study Jupyter notebooks 1-3 in the `intro` folder
and attempt to complete exercise 1a and 1b.

Once done, start going through through the PDF in the `main` folder.
By the end of it you should be able to solve exercises 2 to 4.

A final exercise can be found in the `final` folder.

Solutions to the above can be found in `solutions`.
-->

## Getting Started

<!-- An overview of the files and folder in the exemplar.
Not all files and directories need to be listed, just the important
sections of your project, like the learning material, the code, the tests, etc.

A good starting point is using the command `tree` in a terminal(Unix),
copying its output and then removing the unimportant parts.

You can use ellipsis (...) to suggest that there are more files or folders
in a tree node.

-->

## Project Structure

```log
.
├── examples
│   ├── ex1
│   └── ex2
├── src
|   ├── file1.py
|   ├── file2.cpp
|   ├── ...
│   └── data
├── app
├── docs
├── main
└── test
```
## License

This project is licensed under the [BSD-3-Clause license](LICENSE.md)
