# Melanoma Skin Cancer Detection
> This project uses a custom CNN to detect melanoma in images of skin lesions among 9 classes. The model predicts with an 87% accuracy.


## Table of Contents
* [General Info](#general-information)
* [How to Run](#how-to-run)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
### Algorithms Used
Convolutional Neural Network

### Dataset Information

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed by the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

## Steps Involved

- Data Loading
- Baseline Model Building
- Training the Model and testing the model
- Building an augmented model
- Training the augmented model and testing the model
- Countering Class Imbalance with augmentor
- Building the final model
- Training the final model and testing the model
- Verifying the model
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- As the accuracy of the model increases, the loss decreases. The final model has an accuracy of 87% and a loss of 0.3. The model is able to predict the class of the lesion with a high accuracy.
- Augmenting the data and countering class imbalance helped in improving the accuracy of the model.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## How to run
1. Install the libraries:
   ```bash
   pip install tensorflow Augmentor numpy pandas matplotlib pillow
   ```
2. Get the data: the ISIC skin cancer images (`Train/` and `Test/` folders, one sub-folder per class). The notebook was run on Google Colab with the images on Google Drive; change `data_dir_train` / `data_dir_test` to your own folders when running elsewhere.
3. Open and run the notebook:
   ```bash
   jupyter notebook "Ankur_A_Gupta_nn.ipynb"
   ```

## Technologies Used
- Python
- Tensorflow
- Keras
- Augmentor
- Matplotlib
- NumPy


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
