# Solar Pannel Dust Classification Project

## Introduction
As an AI enthusiast, I am very interested in exploring the energy industry and how AI can help in the discovery of new tools to solve problems. In this project, I have focused on solving the problem of dusty solar panels that often affect the performance of solar plants.

MIT engineers have developed a [system](https://news.mit.edu/2022/solar-panels-dust-magnets-0311) that uses magnets to clean dust from solar panels without using water. However, this solution may not be affordable for smaller solar plant companies. Therefore, I propose a convolutional neural network that can recognize whether a solar panel has dust or not to help reduce maintenance efforts using an image capturing tool such as a drone.

## Problem
Solar panels are located in zones with high levels of sunshine throughout the year, and as a result, they are prone to dust accumulation, which reduces the efficiency of the panel. When sunlight enters a solar panel, energy from the sunlight is absorbed by the photovoltaic cells in the panel, creating electrical charges that move in response to an internal electrical field in the cell, causing electricity to flow.

## Data Preparation
I found the data for this project on Kaggle, and I used the data to train my neural network. The data consisted of images of dusty and clean solar panels. The data set had been split into 80% training data containing 2037 images and 20% testing data containing 525 images. I have made the data available as an open source and available for use in this repository.

## Repository Contents
This repository contains the following:

Data: This folder contains the data used for training and testing the neural network.

Solar_pannel_dust_classification.ipynb: This file contains the code for loading, preprocessing, and training the neural network model for predicting whether a solar panel is dusty or clean.

##Conclusion

This project demonstrates the potential of AI and machine learning in the energy industry. The trained model can be used to detect dusty solar panels, which can then be cleaned, improving the performance and efficiency of solar plants.
