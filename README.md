# Project README

This README summarizes your project structure and instructions so far. You can edit or expand it anytime.

## Overview

This project involves:

* Working with image datasets (training and testing sets)
* Preparing data for TensorFlow image classification
* Handling missing labels in a Kaggle dataset

## Current Status

* Training dataset: **Labeled and usable**.
* Testing dataset: **Unlabeled** — labels are not provided in the Kaggle competition.
* Because of this, binary sorting into `benign/` and `malignant/` is **not possible** without a mapping file.

## Next Steps (Recommended)

1. Proceed with model training using your labeled training set.
2. Use the test set only for predictions (not for accuracy testing).
3. Optionally switch to a fully labeled public dataset if evaluation is required.

## Notes

* TensorFlow `image_dataset_from_directory` requires subfolders for label inference.
* Unlabeled datasets must be loaded using `labels=None`.

## Folder Structure Example

```
complete_set/
    training_set/
        benign/
        malignant/
    testing_set/
        (unlabeled images here)
```
