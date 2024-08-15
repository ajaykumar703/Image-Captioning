# Image Caption Generator using CNN and LSTM (DL)

## Overview

This repository hosts an Image Caption Generator that combines Convolutional Neural Networks (CNN) for image analysis and Long Short-Term Memory (LSTM) units for sequence modeling. The primary goal is to generate descriptive captions for images in natural language, particularly English.

You can view website in this repo : [Website](https://github.com/ajaykumar703/Image-captioning-website)

## Methodology

The model architecture integrates state-of-the-art CNN and LSTM components. CNNs extract hierarchical features from images, enabling a comprehensive understanding of visual content. In parallel, LSTM units process sequential data, ensuring the generation of coherent and contextually relevant language.

## Dataset

We leverage the [Flickr8K dataset](https://www.kaggle.com/datasets/shadabhussain/flickr8k/) for model training and evaluation. This dataset comprises 8000 unique images, each associated with five distinct sentences that describe the image. The dataset's diversity facilitates effective generalization of our model.

### Dataset Structure:

- `Images/`: Directory containing the image files.
- `Descriptions.txt`: Text file with image filenames and their corresponding descriptions.
- `Flickr8k.token.txt`: Tokenized descriptions.
- `train.txt`, `val.txt`, `test.txt`: Split files for training, validation, and testing.

## GloVe Embeddings

We enhance the linguistic representation of words in our model using pre-trained GloVe word embeddings. Download the embeddings from the [GloVe Global Vectors for Word Representation dataset](https://www.kaggle.com/datasets/rtatman/glove-global-vectors-for-word-representation/).

### GloVe Files:

- `glove.6B.50d.txt`: GloVe embeddings file.

## Usage

1. **Download the datasets:**

   - Download the [Flickr8K dataset](https://www.kaggle.com/datasets/shadabhussain/flickr8k/) containing images and descriptions.
   - Obtain the pre-trained GloVe word embeddings from [GloVe Global Vectors for Word Representation](https://www.kaggle.com/datasets/rtatman/glove-global-vectors-for-word-representation/).

2. **Clone the repository:**

   ```bash
   git clone https://github.com/ajaykumar703/image-captioning.git
   cd image-captioning
   ```
   **or**
   - Download the ipynb file.
4. **Run Cells:**
   - change the path in code according to the name you have given to your downloaded data set and run.
  
     
## Feel Free to Contribute

We welcome contributions to enhance the capabilities and functionalities of this image caption generator.


