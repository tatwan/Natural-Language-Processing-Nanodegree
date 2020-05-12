# Natural Language Processing Nanodegree



![img](images/Natural%20Language%20Processing.png)

---

# Project 1:  Part of Speech Tagging with Hidden Markov Models

## Introduction

In this notebook, you'll use the [Pomegranate](https://github.com/jmschrei/pomegranate) library to build a hidden Markov model for part of speech tagging with a [universal tagset](http://www.petrovi.de/data/universal.pdf). Hidden Markov models have been able to achieve >96% tag accuracy with larger tagsets on realistic text corpora. Hidden Markov models have also been used for speech recognition and speech generation, machine translation, gene recognition for bioinformatics, and human gesture recognition for computer vision, and more.

The notebook already contains some code to get you started. You only need to add some new functionality in the areas indicated to complete the project; you will not need to modify the included code beyond what is requested. Sections that begin with **'IMPLEMENTATION'** in the header indicate that you must provide code in the block that follows. Instructions will be provided for each section, and the specifics of the implementation are marked in the code block with a `'TODO'` statement. Please be sure to read the instructions carefully!

**NOTE:** There is an optional warmup exercise to introduce the Pomegranate API included in the project files. Just launch the `HMM warmup (optional).ipynb` file first to get started there, then complete the `hmm tagger.ipynb` notebook. (Only the tagger will be submitted for review.)

## Getting Started

You can choose one of two ways to complete the project. The first method is to use the Workspace embedded in the classroom in the next lesson. The Workspace has already been configured with all the required project files for you to complete the project. Simply open the lesson, complete the sections indicated in the Jupyter notebook, and then click the "submit project" button.

**NOTE:** If you are prompted to select a kernel when you launch a notebook, choose the **Python 3** kernel.

Alternatively, you can download a copy of the project materials and then run a Jupyter server locally on your machine. Select the appropriate link for your program below, then follow the instructions in the readme to setup and complete the project.

**NOTE:** These steps are **not** required if you are using the project Workspace.

- AIND GitHub: [here](https://github.com/udacity/artificial-intelligence) (Projects/4_HMM Tagger)
- NLPND GitHub: [here](https://github.com/udacity/hmm-tagger)

## Evaluation

Your project will be reviewed by a Udacity reviewer against the project rubric [here](https://review.udacity.com/#!/rubrics/1429/view). Review this rubric thoroughly, and self-evaluate your project before submission. All criteria found in the rubric must meet specifications for you to pass.

## Submission

Once you have completed all of the code implementations, you need to finalize your work by exporting the iPython Notebook as an HTML document. Before exporting the notebook to html, all of the code cells need to have been run so that reviewers can see the final implementation and output. You must then export the notebook by running the last cell in the notebook, or by using the menu above and navigating to File -> Download as -> HTML (.html) Your submissions should include both the html and ipynb files.

Add the "hmm tagger.ipynb" and "hmm tagger.html" files to a zip archive and submit it with the button below. (**NOTE:** If you complete the project in the workspace, then you can submit directly using the "submit" button in the workspace.)

---

# Project 2 : Machine Translation

Machine translation is a popular topic in research with new papers coming out every year. Over the years of research, different methods were created, like [rule-based](https://en.wikipedia.org/wiki/Rule-based_machine_translation), [statistical](https://en.wikipedia.org/wiki/Statistical_machine_translation), and [example-based](https://en.wikipedia.org/wiki/Example-based_machine_translation) machine translation. With all this effort, it’s still an unsolved problem. However, neural networks have made a large leap forward in machine translation.

In this notebook, you will build a deep neural network that functions as part of an end-to-end machine translation pipeline. Your completed pipeline will accept English text as input and return the French translation.

---

# Project 3: DNN Speech Recognizer

In this notebook, you will build a deep neural network that functions as part of an end-to-end automatic speech recognition (ASR) pipeline!

We begin by investigating the [LibriSpeech dataset](http://www.openslr.org/12/) that will be used to train and evaluate your models. Your algorithm will first convert any raw audio to feature representations that are commonly used for ASR. You will then move on to building neural networks that can map these audio features to transcribed text. After learning about the basic types of layers that are often used for deep learning-based approaches to ASR, you will engage in your own investigations by creating and testing your own state-of-the-art models. Throughout the notebook, we provide recommended research papers for additional reading and links to GitHub repositories with interesting implementations.

# Tasks

The tasks for this project are outlined in the `vui_notebook.ipynb` in three steps. Follow all the instructions, which include implementing code in `sample_models.py`, answering questions, and providing results. The following list is a summary of the required tasks.



![img](images/pipeline.png)



## Step 1 - Feature Extraction

- Execute all code cells to extract features from raw audio

## Step 2 - Acoustic Model

- Implement the code for Models 1, 2, 3, and 4 in `sample_models.py`
- Train Models 0, 1, 2, 3, 4 in the notebook
- Execute the comparison code in the notebook
- Answer Question 1 in the notebook regarding the comparison
- Implement the code for the Final Model in `sample_models.py`
- Train the Final Model in the notebook
- Answer Question 2 in the notebook regarding your final model

## Step 3 - Decoder

- Execute the prediction code in the notebook