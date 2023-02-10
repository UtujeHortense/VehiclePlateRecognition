# Vehicle Plate Recognition

This is a pipeline that extracts vehicle plate number from images. It is implemented in Matlab.

It is divided in 4 crucial parts:

## Plate Localisation

This entails the localisation of the plate in the image. We define what a plate is according to its rectangular shape and the height to width ratio.

## Plates Cleaning

Once the plate is separated from the vehicle in needs to be cleaned of any possible interference. For example extra logos.

## Plate Extraction

The next step is plate extraction (numbers and letters). It was done with the help of the OCR function available in Matlab.
More on OCR here: https://www.mathworks.com/help/vision/ref/ocr.html

## Validation

The final step is the validation of the pipeline. For this project the dataset includes only European Vehicles. Therefore the Training and Validation datasets are all of European vehicles.

# How to run the project

- Clone the repository
- Use Matlab to run the livecript at the root

# Project Report

For more detailed information on the implementation, refer to the project report in the repository by the name of ANPR - Project Report.
