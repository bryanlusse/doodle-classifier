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

This repository holds models trained to classify hand-drawn doodles. The model is used in a [web app](https://github.com/bryanlusse/doodle-classifier-app) that classifies doodles that you can draw online

Currently, we have trained two different models that can classify 10 and 30 different classes of doodles. The specifics can be found in the Notebooks.

This repository might be updated with models able to classify more classes.

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
├── doodle_classifier.ipynb
├── doodle_classifier_colab.ipynb       # Notebook for running on Colab GPU's
├── LICENSE
├── Network.png              
├── saved_models                        # Folder with all saved models
│   ├── combined_v2_28                  # Model predicting 10 classes
│   └── improved_30_28_20_epochs        # Model predicting 30 classes   
└── README.md
```

## :smiley_cat: Author

- [@bryanlusse](https://github.com/bryanlusse)

Made with &nbsp;❤️&nbsp;