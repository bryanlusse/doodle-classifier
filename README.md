<div align="center">

# Doodle-classifier

![Badge](https://img.shields.io/github/languages/code-size/bryanlusse/doodle-classifier)
![Badge](https://img.shields.io/github/languages/count/bryanlusse/doodle-classifier)
![Badge](https://img.shields.io/github/last-commit/bryanlusse/doodle-classifier)

[Overview](#scroll-overview)
•
[Model](#chart_with_upwards_trend-model)
</div>

## :bookmark_tabs: Menu

- [Overview](#scroll-overview)
- [Model](#chart_with_upwards_trend-model)
- [Requirements](#exclamation-requirements)
- [Folder Structure](#open_file_folder-folder-structure)
- [Author](#smiley_cat-author)

## :scroll: Overview

This web app enables users to draw doodles depending on a given prompt. A [deep learning algorithm](https://github.com/bryanlusse/doodle-classifier) predicts the class of the doodle while drawing. The aim of the game is to let the model correctly guess all drawings.

At the moment, 10 classes are supported. The prompt given for the drawings are therefore randomly drawn from these classes. The classes are: 'banana', 'calculator', 'cat', 'fish', 'hamburger', 'headphones', 'house', 'house plant', 'mushroom' and 'windmill'.

Later updates will use more classes.

## :chart_with_upwards_trend: Model

|Title | Dataset | Notebooks |
| --- | --- | --- | 
| Doodle Classifier | [QuickDraw!](https://quickdraw.withgoogle.com/data) | [![TensorFlow](https://img.shields.io/badge/Tensor-Flow2.0-orange)](doodle_classifier.ipynb) |


## :exclamation: Requirements

- [Python](https://www.python.org/)
- [Tensorflow](https://www.tensorflow.org)
- [Numpy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Pillow](https://python-pillow.org/)
- [Quickdraw](https://quickdraw.readthedocs.io/en/latest/)
- [Jupyter Notebooks](http://jupyter.org)
- [Google Colab](https://colab.research.google.com/)

## :open_file_folder: Folder Structure

```
.
├── dataset
├── doodle_classifier.ipynb
├── doodle_classifier_colab.ipynb       # Notebook for running on Colab GPU's
├── LICENSE
├── Network.png              
├── saved_models                        # Folder with all saved models
│   ├── combined_v2_28                  # Model predicting 10 classes
│   └── improved_30_28_20_epochs        # Model predicting 30 classes   
├── training_1                          # Training checkpoints
└── README.md
```

## :smiley_cat: Author

- [@bryanlusse](https://github.com/bryanlusse)

Made with &nbsp;❤️&nbsp;