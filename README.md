# MicrobeID

## Project Overview

MicrobeID is a bioinformatics project exploring whether combining bacterial colony images with agar growth-medium characteristics can improve machine learning classification of bacterial species.

The project uses image-based features and information about the growth medium to compare three classification approaches.

## Research Question

Can combining bacterial colony morphology with growth-medium characteristics improve machine learning classification of bacterial species compared with using colony images alone?

## Methods

Three models are being developed and compared:

1. **Image-only model:** Uses bacterial colony images to classify species.
2. **Medium-only model:** Uses agar growth-medium information to classify species.
3. **Combined model:** Uses both image features and growth-medium information.

MobileNetV2 is used for image feature extraction, followed by logistic regression for classification. Model performance is evaluated using accuracy, precision, recall, macro F1-score, and confusion matrices.

## Data Sources

The project uses publicly available bacterial colony image datasets from Mendeley Data:

- [2022 dataset](https://data.mendeley.com/datasets/kx6gz3wmcf)
- [2025 dataset](https://data.mendeley.com/datasets/v54x8jdx5x)

## Project Status

The dataset has been downloaded and organized, duplicate screening has been completed, and a plate-level training and testing split has been established. Model development and evaluation are ongoing.

## Reproducibility

The Google Colab notebook and supporting files will be provided in this repository. The goal is to make the analysis reproducible using the publicly available datasets without requiring access to personal Google Drive files.

## Acknowledgments

AI tools were used to assist with coding, troubleshooting, understanding machine learning concepts, and editing project documentation. Code and outputs were reviewed during development.
