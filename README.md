# SCT_ML_03
Image classification is a foundational task in computer vision. The most common beginner project is classifying images of cats and dogs. This notebook focuses on the **setup and extraction** phase: unzipping and organizing a large dataset of cat and dog images, which is the prerequisite for training any image classification model.

## Dataset

- **Source:** The dataset used is a ZIP file named `PetImages.zip`, which contains two subfolders: `Cat` and `Dog`, each with thousands of `.jpg` images.
- **Structure after extraction:**
  ```
  extracted_images/
      PetImages/
          Cat/
              0.jpg
              1.jpg
              ...
          Dog/
              0.jpg
              1.jpg
              ...
  ```

## Project Workflow

1. **Setup and Extraction**
    - Import necessary libraries (`os`, `zipfile`)
    - Define the ZIP file path and extraction directory
    - Extract all images to a specified folder
    - Print and verify the resulting directory structure and file count

2. **Directory Inspection**
    - Recursively print the contents of the extracted folders to verify the presence of cat and dog images
    - Ensure the dataset is prepared for the next steps (preprocessing, training, etc.)
## Requirements

- Python 3.x
- Jupyter Notebook
