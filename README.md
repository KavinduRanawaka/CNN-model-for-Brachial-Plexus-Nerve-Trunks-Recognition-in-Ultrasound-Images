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

#### Overview

The U-Net architecture is a convolutional neural network (CNN) designed for semantic segmentation tasks, particularly in medical imaging applications. Introduced by Ronneberger et al. in 2015, U-Net has become a fundamental model in the field of medical image analysis.

#### Key Components

##### Encoder

The encoder portion of the U-Net comprises convolutional and pooling layers that progressively downsample the input image to capture high-level features.

##### Decoder

The decoder part of the network consists of upsampling layers that recover spatial information lost during encoding, allowing for precise object localization.

##### Skip Connections

U-Net utilizes skip connections between corresponding layers in the encoder and decoder, enabling the decoder to access features at multiple scales for accurate segmentation.

##### Final Layer

The final layer typically consists of a 1x1 convolutional layer followed by a softmax or sigmoid activation function, generating pixel-wise predictions for the segmentation mask.

#### Advantages

- Efficient use of training data
- Precise object localization
- Flexibility and adaptability to various imaging modalities

#### Applications

U-Net is widely used for segmenting organs, tumors, and anatomical structures in medical images, including MRI, CT, and ultrasound.



