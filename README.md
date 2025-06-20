# ece228_RiNN

This repository contains the code, dependencies, and trained models developed for the ECE 228 Spring 2025 course project.

---

## Setup Instructions

1. **Install dependencies**  
   Use the provided `requirements.txt` file:
   ```bash
   pip install -r requirements.txt
   ```

2. **Open the Jupyter notebook**  
   Open `ECE228Project-Group47-RiNN.ipynb` and update the base directory path to your local setup.

3. **Please use the Google Drive provided below to obtain the datasets and pre-trained models.**

4. **Select the dataset**  
   - To run on the SISO dataset, rename `dataset_siso.json` accordingly.
   - The default is `dataset_1RIS.json`.

5. **Update voxel path in training loop**  
   Modify the `voxels_path` parameter in the training cell:
   ```
   path_to_your_repo/channel_scatter_room/scene_voxels_1RIS.npy
   ```
   or
   ```
     path_to_your_repo/channel_scatter_room/ scene_voxels_SISO.npy
   ```

6. **Run all notebook cells to train or evaluate the model**
7. **Pre-trained models**
      The trained on respective datasets are available under
   ```
   channel_scatter_room/trained_models
   ```

---

## Pretrained Models and Datasets

Due to their size, pretrained model weights and datasets are not stored in the repository.  
You can download them from the following Google Drive link:

👉 [Click here to download](https://drive.google.com/drive/folders/1-EopV4C6ENwCd2_6oGYzGgxJmDoi3uAP?usp=sharing)

---

Let us know if you encounter any issues or would like to contribute! PLease contact: nbhat@ucsd.edu or fasalehi@ucsd.edu
