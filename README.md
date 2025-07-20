# CropStats-v2
# SICKLE – Remote‑Sensing Crop Analytics

This repo contains **CS_SICKLE.ipynb**, a self‑contained Jupyter notebook that:

* loads the **SICKLE** dataset (Sentinel‑1 image time‑series + tabular features)  
* provides utility functions for preprocessing, augmentation & dataloading  
* implements two deep‑learning models – **UTAE** and **ConvLSTM** – for  
  * crop‑type classification  
  * crop‑yield regression  
* logs training metrics and saves checkpoints.

