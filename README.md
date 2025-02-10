## Overview
This repository contains an implmentaion of a method to generate captions for images. The main dataset is ([in this link](https://www.kaggle.com/datasets/malekzadeharman/persian-image-captioning-dataset/)).
Images first are passed through an encoder which is Resnet18 model, and then the extracted embeddings are concatenated with token embeddings and are passed through lstm network to generate captions in auto regressive maanner.

## How To Use
1. Download main dataset from ([here](https://www.kaggle.com/datasets/malekzadeharman/persian-image-captioning-dataset/))
2. Unzip required files to have this directory structure:
```
\persian_image_captioning
    \images
    \selected_images
    news.json
main.ipynb
```
3. Train img2seq model and use it to generate captions for selected images using final cell script

