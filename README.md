# BBox-IOAI-selection
This repository contains the implementation of a Convolutional Neural Network (CNN) for bounding box detection, developed as part of the selection program for the Malaysian National Team for the International Olympiad in Artificial Intelligence (IOAI).


Project Overview
The project implements a simplified Fully Convolutional Network (FCN) architecture for object detection, specifically designed to detect people in images by predicting bounding box coordinates and objectness scores.

Key Features
Custom CNN Architecture: Modified ResNet34 backbone with a 1×1 convolutional head for bounding box regression

Grid-based Detection: Implements cell-based object detection where each spatial cell predicts bounding box parameters

Multi-channel Output: 5 output channels representing (x_offset, y_offset, width, height, objectness)

Custom Dataset Handling: Specialized PyTorch dataset for bounding box annotation processing

Visualization Tools: Comprehensive plotting utilities for bounding box visualization and model predictions
