# Concurrent Geospatial Data for Supervising Invasive Species in Small and Dispersed Areas 

## ONE LINER OF WHAT IT DOES

Intro paragraph use keywords here.

## Visual Helper: diagram video
![Workflow of our proposed model](Workflow.png)

## Datasets
- Locations: [USGS Inhabit database](https://gis.usgs.gov/inhabit/)

- Training Dataset: [Kudzu Alive vs Dead](https://gis.usgs.gov/inhabit/) FIX LINK

## Requirements

For GPU:
- Tensorflow version older than 2.11: `!pip install "tensorflow<2.11"` This is important if wanted to use GPU. I believe higher versions work with the cpu.
- Cuda and Cudnn: `conda install -c conda-forge cudatoolkit=11.2 cudnn=8.1.0 -y`
- 

GPU set-Up for Windows 11 ([tutorial](https://www.xda-developers.com/use-gpu-jupyter-notebook/)) 
pip list

## How to use this workflow
User Instructions for general users no need to be coders
1. Clone this repository
2. Obtain a Google Maps API key
3. Run 2.StreetView.ipynb, make sure to edit the variable `api_key = <YOUR_API_KEY_GOES_HERE>`
4. Run 3.DeepCNNImageClassifier.ipynb, make sure to edit the path variables `your_directory = <YOUR_FOLDER_GOES_HERE>`
5. Run 4.Image Confirmation.ipynb, 
   

6. qwert




## How to tweak this project for your own purposes
Use other plants

Requirements:
step 1: Image retriveation
`python -m pip install requests`




### Known Issues



### Contact
Email: aclosatarres@wvstateu.edu




**Keywords:** geographic information systems, google street view, ecology, kudzu, workflow,
image classification, object detection, convolutional neural networks
