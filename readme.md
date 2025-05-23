# CanvasSAM -- Image Editing with Segment Anything Model

## Overview

This project uses Meta AI's Segment Anything Model (SAM) for advanced image segmentation and editing. SAM is an AI model designed to identify and segment objects in images with minimal human input, enabling powerful image manipulation capabilities.

## Setup

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/image_edit.git
   cd image_edit
   ```

2. Install the required packages:
   ```
   pip install torch torchvision opencv-python matplotlib
   pip install segment-anything
   ```

3. Download the SAM checkpoint (if needed):
   ```
   wget https://dl.fbaipublicfiles.com/segment_anything/sam_vit_h_4b8939.pth
   ```

## Usage

### Google Colab (Recommended)

For the best performance, we recommend using Google Colab with A100 GPU:

1. Open the notebook in Google Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]

2. Select Runtime > Change runtime type > Hardware accelerator > GPU > Select A100 GPU (if available)

3. Follow the instructions in the notebook


## Examples

Below are some examples of what you can achieve with CanvasSAM:

### Original Image
This is the original test image before any processing:

![Original Test Image](content/test2.jpg)

### Image Segmentation and Editing
After processing with CanvasSAM, objects can be precisely identified and manipulated:

![Plant Transformation](demo_image/final_output_gdino_sam.png)


![Lion to Elephant](demo_image/final_output_gdino_sam_lion.png)


![Fancier Umbrella](demo_image/final_output_gdino_sam_umbrella.png)

## References

- [Segment Anything Model (SAM)](https://segment-anything.com/)
- [SAM GitHub Repository](https://github.com/facebookresearch/segment-anything)

## Contributing

Contributions to improve the project are welcome. Please feel free to submit a pull request.
