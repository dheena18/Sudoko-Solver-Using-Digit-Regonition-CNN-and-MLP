# Sudoku Solver with Number Recognition

This repository demonstrates a project that leverages a number dataset to train a model capable of recognizing and writing digits, and subsequently applies this model to solve Sudoku puzzles from images. The project integrates deep learning techniques for image recognition with traditional algorithmic approaches for solving Sudoku puzzles.

## Overview

The project consists of two main stages:

1. **Digit Training:**  
   A number dataset is used to train a model that can accurately recognize and write digits. This trained model serves as the backbone for the digit recognition phase.

2. **Sudoku Solving:**  
   Using the trained digit recognition model, the system processes images of Sudoku puzzles (referred to as "sudolo images" in the project) to extract the digits from each cell. The recognized digits are then used to reconstruct the Sudoku board, which is subsequently solved using a Sudoku-solving algorithm.

## Features

- **Digit Recognition:**  
  Utilizes a custom-trained model on a number dataset to achieve high accuracy in digit recognition.
  
- **Image Processing:**  
  Processes Sudoku puzzle images to identify and extract digits from each cell.
  
- **Sudoku Solving:**  
  Integrates a solving algorithm that fills in the missing digits once the puzzle is reconstructed from the recognized numbers.
  
- **Interactive Notebook:**  
  An IPython Notebook (`.ipynb` file) is provided to showcase the project workflow, from data preparation and model training to digit recognition and puzzle solving.
