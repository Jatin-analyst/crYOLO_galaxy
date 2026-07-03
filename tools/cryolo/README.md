# crYOLO Galaxy Tool Suite

This repository contains Galaxy Tool wrappers for **crYOLO 1.9.9**, an automated particle picking tool based on the YOLO deep learning object detection framework.

## Included Tools

1. **crYOLO Config**: Generates the central configuration JSON file required for training and prediction.
2. **crYOLO Predict**: Runs particle picking on raw micrographs. Supports Single Particle Analysis (SPA), Filament Tracing, and 3D Tomography linking.
3. **crYOLO Train**: Trains or fine-tunes a crYOLO model using annotated micrograph datasets.

## Requirements

The tools depend on the `cryolo` conda package (installed via Bioconda).

## Citation

Wagner, T. et al. (2019). SPHIRE-crYOLO is a fast and accurate fully automated particle picker for cryo-EM. *Communications Biology*, 2, 218. https://doi.org/10.1038/s42003-019-0312-7
