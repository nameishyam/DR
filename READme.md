# Image Processing and GAN-Based Classification Project

## Project Structure

The project is organized into four main folders:

1. **Image Preprocessing**

   - Converts all images from their original rectangle shape to their respective average resolution.
   - Creates separate directories for low-resolution and actual-resolution images.

2. **GAN Training**

   - Contains the code for training the GAN model on the preprocessed images.

3. **Low-Resolution Image Classification**

   - Includes the code for classifying images that are of low resolution.

4. **High-Resolution Image Classification**
   - Contains the code for classifying images that are of high resolution.

---

## Workflow

### Step 1: Image Preprocessing

- Run the script in the `Image Preprocessing` folder to:
  - Convert images to their average resolutions.
  - Create separate directories for low-resolution and actual-resolution images.

### Step 2: Train the GAN Model

- Ensure that all file and folder paths are correctly set.
- Execute the GAN training script in the `GAN Training` folder to generate high-resolution images.

### Step 3: Image Classification

- Run the classification code in the `Low-Resolution Image Classification` folder.
- Execute the classification code in the `High-Resolution Image Classification` folder.
- Compare results for analysis.

---

## Directory Structure

```
/project_root
│── Image_Preprocessing/
│   ├── preprocess_images.py
│   ├── low_resolution_images/
│   ├── actual_resolution_images/
│
│── GAN_Training/
│   ├── train_gan.py
│   ├── model/
│
│── Low_Resolution_Classification/
│   ├── classify_low_res.py
│   ├── results/
│
│── High_Resolution_Classification/
│   ├── classify_high_res.py
│   ├── results/
```

This structure ensures a clear and systematic approach to processing, enhancing, and analyzing images using GANs.
