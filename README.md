# Polymer Membranes Fabrication Research Project

## Overview

This project focuses on the fabrication of polymer membranes, particularly exploring the factors that influence the creation of symmetrical bee-hive-like membranes and perfect-circle pore shapes. Additionally, the project investigates unintuitive causes that affect membrane fabrication results.

## Approach

### Pore Recognition Algorithm

1. **Gray-scaling and Noise Removal**
2. **Adaptive Threshold Segmentation**
3. **Finding Contours of the Pores**
4. **Creating "Hexagonal Tiling" and Measuring its Symmetry**

![illus](https://github.com/tomerfried/Polymer-Membranes-Fabrication-Data-Science-Project/assets/68680809/ae46151e-8787-4cd9-a43b-980f73c822a2)
Illustration of Pore Recognition Algorithm

### Dataset Creation and Pre-processing

1. **Metadata Records**: Collection of metadata for each image.
2. **Data Cleaning**: Filtering unnecessary data, removing special symbols, and fixing mistakes.
3. **Data Filling**: Filling empty entries and removing images with unfound data.

### Deep Learning Model

1. **Outlier Filtering**: Removing images that might be outliers.
2. **Normalization**: Normalizing variable values.
3. **Model Fitting**: Fitting a deep learning model on the dataset.
4. **Prediction Explanation**: Explaining the model's predictions.

![res](https://github.com/tomerfried/Polymer-Membranes-Fabrication-Data-Science-Project/assets/68680809/52ec17a3-86ee-4e77-9baa-1ff9471ef2e4)

Impact of different factors on the prediction. Factors are pixelated to avoid copyright infringement

## Conclusions From Model Prediction

1. No single dominant variable was identified; a combination of variables influences the outcomes.
2. The results allow to distinct between the most and the least Influential factors.

## Acknowledgments

Special thanks to:
- Dr. Martin Held
- Dr. Roland Aydin
- The associates of Helmholtz-Zentrum Hereon
