# DeepFLaSH
A deep learning pipeline for segmentation of fluorescent labels in brain sections

## Jypter Notebooks on [Google Colab](http://colab.research.google.com)

* Select 'Runtime' -> 'Change runtime time' -> 'Python 3' (and 'GPU') before running the notebook.
* Ignore the warning: 'This notebook was not authored by Google.' Run anyway.
* Use Firefox or Google Chrome if you want to upload your images.

Train or fine-tune your own model and segment your images [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/matjesg/DeepFLaSH/blob/master/DeepFLaSH.ipynb)

Demo notebook [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/matjesg/DeepFLaSH/blob/master/demo.ipynb)

## Model Library

This list contains download links to the weights of the selected models as well as an example of their corresponding training images and masks.

You can select and apply these models within our Jupyter Notebook.
* [cFOS_Wue](https://drive.google.com/open?id=1u1jAqxRpQh2hjE0W2vdHNCyhQsM5uAis): 
Trained on 36 image-mask pairs of cFOS labels in the dorsal hippocampus (including 12 images of each sub-region: dentate gyrus, CA3 and CA1). Masks for training were prepared by five independent experts. Images were acquired using laser-scanning confocal microscopy with a resolution of 1.6 pixel per µm.
    
    <img src="https://raw.githubusercontent.com/matjesg/DeepFLaSH/master/assets/cFOS_Wue.png" width="250" height="250" alt="cFOS_Wue">
    <img src="https://raw.githubusercontent.com/matjesg/DeepFLaSH/master/assets/cFOS_Wue_mask.png" width="250" height="250" alt="cFOS_Wue_mask">

* [cFOS_Inns1](https://drive.google.com/open?id=1n6oGHaIvhbcBtzrkgWT6igg8ZXSOvE0D): Fine-tuned on [cFOS_Wue](https://drive.google.com/open?id=1u1jAqxRpQh2hjE0W2vdHNCyhQsM5uAis)
with five image-mask pairs of cFOS labels in the amygdala. Masks for fine-tuning were prepared by one expert. Images acquired using epifluorescence microscopy with a resolution of 1 pixel per µm.

    <img src="https://raw.githubusercontent.com/matjesg/DeepFLaSH/master/assets/cFOS_Inns1.png" width="250" height="250" alt="cFOS_Inns1">
    <img src="https://raw.githubusercontent.com/matjesg/DeepFLaSH/master/assets/cFOS_Inns1_mask.png" width="250" height="250" alt="cFOS_Inns1_mask">

* [cFOS_Inns2](https://drive.google.com/open?id=1TGxZC93YUP1kp1xmboxl6fJEqU4oDRzP):
Fine-tuned on [cFOS_Wue](https://drive.google.com/open?id=1u1jAqxRpQh2hjE0W2vdHNCyhQsM5uAis)
with five image-mask pairs of cFOS labels in the infralimbic cortex. Masks for fine-tuning were prepared by one expert. Images acquired using epifluorescence microscopy with a resolution of 2 pixel per µm.

    <img src="https://raw.githubusercontent.com/matjesg/DeepFLaSH/master/assets/cFOS_Inns2.png" width="250" height="250" alt="cFOS_Inns2">
    <img src="https://raw.githubusercontent.com/matjesg/DeepFLaSH/master/assets/cFOS_Inns2_mask.png" width="250" height="250" alt="cFOS_Inns2_mask">

* [cFOS_Mue](https://drive.google.com/open?id=1GFOsnLFY8nKDVcBTX7MvMTjoiYfhs91b):
Fine-tuned on [cFOS_Wue](https://drive.google.com/open?id=1u1jAqxRpQh2hjE0W2vdHNCyhQsM5uAis)
with five image-mask pairs of cFOS labels in the paraventricular nucleus of the thalamus. Masks for fine-tuning were prepared by one expert. Images acquired using laser-scanning confocal microscopy with a resolution of 0.8 pixel per µm.

    <img src="https://raw.githubusercontent.com/matjesg/DeepFLaSH/master/assets/cFOS_Mue.png" width="250" height="250" alt="cFOS_Mue">
    <img src="https://raw.githubusercontent.com/matjesg/DeepFLaSH/master/assets/cFOS_Mue_mask.png" width="250" height="250" alt="cFOS_Mue_mask">

* [Parv](https://drive.google.com/open?id=1VtxyOXhuYVDAC8pkzx3SG9sZfvXqHDZI):
Trained on 36 image-mask pairs of Parvalbumin-labels in the dorsal hippocampus (including 12 images of each sub-region: dentate gyrus, CA3 and CA1). Masks for training were prepared by five independent experts. Images were acquired using laser-scanning confocal microscopy with a resolution of 1.6 pixel per µm.
    
    <img src="https://raw.githubusercontent.com/matjesg/DeepFLaSH/master/assets/Parv.png" width="250" height="250" alt="Parv">
    <img src="https://raw.githubusercontent.com/matjesg/DeepFLaSH/master/assets/Parv_mask.png" width="250" height="250" alt="Parv">

## Acronym
A **Deep**-learning pipeline for **F**luorescent **La**bel **S**egmentation that learns from **H**uman experts
