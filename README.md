# Cognitive-Behavioural-and-Social-Data

## Table of contents

* [Overview and motivation](#overview-and-motivation)
* [Technologies](#technologies)
* [Datasets](#datasets)
* [Methods](#methods)
* [Experiments](#experiments)
* [Results](#results)
## Overview and motivation

In this project, we are trying to gain insight into the impact different feature selection methods
have on classification algorithms. Our core idea is to implement the most used variable extraction
methods, both model dependent and model agnostic, on 13 different datasets. We then compare
our results with a number of tuned classification models. Using psychological tests with varying
number of items, we look at the impact the calculations done on these studies have on the questions
retained on the final version of the tests. Hence, our main goal involves searching for techniques
that have a good trade-off between replicability and result quality, by showcasing the relationship
between model evaluation metrics and the correlation coefficient of highlighted features.

## Technologies
Project created in google colab with:
* python 3.8.10

Main libraries:
* optuna
* numpy
* pandas
* sklearn
* matplotlib

## Datasets
A number of studies have been conducted on volunteers, in which they have to answer honestly and dishonestly to a various questions regarding personal traits. These include, but are not limited to, the Dark Triad, five dimensions of human personality, signs of PTSD and memory impairment. Then, regardless of the topic, researchers try to select the most effective questions in order to pass them to the final version. 

While some questionaries have very obvious skewness in distribution of the dishonest answers (as the violin plots below of the labeled answer distribution on the PTST dataset show), some have a very hard to notice difference from performing EDA alone.

The datasets can be found [here](csbd-data)
## Methods
## Experiments
## Results
