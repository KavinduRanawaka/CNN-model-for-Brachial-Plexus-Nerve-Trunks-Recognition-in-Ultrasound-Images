# CNN-model-for-Brachial-Plexus-Nerve-Trunks-Recognition-in-Ultrasound-Images
## Prerequisites
- Download Dataset: Download the dataset from the provided link (https://drive.google.com/file/d/1xMdKyX9k-Fi_vI5Tz-8qDDjFVn6iZGv4/view?usp=drive_link).
- Do not unzip. Locate Dataset in your Google Drive.
## Usage
- Open this repo (https://github.com/NHMSudara/CNN-model-for-Brachial-Plexus-Nerve-Trunks-Recognition-in-Ultrasound-Images.git) from Goolgle colab.
- Change the path of Dataset
```markdown
!unzip /path/to/new_data_nr.zip
```
- Run each and every block in notebook one by one. (make sure use GPU in Google Colab)
## Model
### U-Net Architecture
The U-Net architecture is a convolutional neural network (CNN) designed for semantic segmentation tasks, especially in medical imaging. Introduced in 2015, it consists of an encoder, a decoder, skip connections, and a final layer. Key features include efficient use of training data, precise object localization, and adaptability to various imaging modalities. It's widely used for segmenting organs, tumors, and anatomical structures in medical images.
### Inc+ResU-Net Architecture
ResU-Net and Inception+U-Net are advanced adaptations of the U-Net architecture for medical image segmentation. ResU-Net utilizes residual blocks to mitigate vanishing gradients and enhance fine detail capture, while Inception+U-Net combines U-Net with Inception modules for improved multi-scale feature extraction and segmentation accuracy. The Inc+ResU-Net model, created by combining residual and Inception blocks, effectively addresses issues like vanishing gradients and enhances feature extraction.

