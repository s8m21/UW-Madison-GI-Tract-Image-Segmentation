# OncoScan AI: Image-Segmentation-for-Gastrointestinal-Tract-Cancer
This repository contains codebase for the image segmentation task as part of our project titled <b>OncoScan AI</b>.

Following is the description of the individual pages of the interface - 

# GUI Description

## 1. HomePage

<img width="1277" alt="image3" src="https://github.com/s8m21/UW-Madison-GI-Tract-Image-Segmentation/assets/127258950/6ad444d4-d9c9-4be4-b33c-1f6953291a7d">

The landing page of OncoScan AI which is used also describes about different windows in the Interface.

## 2. Animation Window

<img width="1276" alt="image4" src="https://github.com/s8m21/UW-Madison-GI-Tract-Image-Segmentation/assets/127258950/c82c8061-e408-401c-83a0-8b6c5281afd3">

This page demonstrates the MRI scans of a chosen case using the dropdown button provided in the form of Animation using an adjustable slider.

## 3. Prediction Window

<img width="1277" alt="image5" src="https://github.com/s8m21/UW-Madison-GI-Tract-Image-Segmentation/assets/127258950/a43de887-1148-459d-9218-11983c47f481">

This page demonstrates the prediction window where a user can upload any MRI scan and get a predicted mask as an output figure on the interface itself. The above image demonstrates the predicted mask from an input `case 108`, `Day 13` and `slice 74`. 

## 4. Visualization Window

<img width="1280" alt="image6" src="https://github.com/s8m21/UW-Madison-GI-Tract-Image-Segmentation/assets/127258950/faa65536-3854-48b4-9da0-0b13d9ac9621">

This page is used to visualize individual MRI scans by choosing specific combination of `case`, `day` and `slice`.

# Installation

```{python}
pip install -r requirements.txt
```

The above command would installed all of the dependencies for the project. Next run the following command to start the interface.

# Run

```{python}
python app.py
```
