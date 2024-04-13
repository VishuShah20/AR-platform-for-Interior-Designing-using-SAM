# AR-platform-for-Interior-Designing-using-SAM

## Overview

This repository is home to the Visionary AR platform, an innovative tool that revolutionizes interior design through augmented reality, deep learnming and SAM (Segment Anything by Meta). The platform allows users to upload images of their spaces and dynamically alter textures and furnishings using advanced semantic segmentation and texture overlay technologies. Developed with a CNN model trained on proprietary and ADE20K datasets, this tool is designed to significantly enhance realism and user engagement in interior design.

## Use Case

The Visionary AR platform is tailored for interior designers, real estate agents, furniture retailers, and homeowners. It enables them to visualize and modify room interiors virtually, which helps in making informed decisions about design changes without physical or financial commitments. This immersive experience is not only a tool for visualization but also a means to increase customer satisfaction and sales through interactive design proposals.

## Features

- **Photo Upload Capability**: Users can upload photos of their rooms directly into the platform.
- **Real-Time Texture and Interior Swapping**: Change the textures and interior elements within the uploaded photos to visualize different design outcomes.
- **Semantic Segmentation for Detailed Customization**: Utilizes cutting-edge CNN models to accurately segment different areas of a room, allowing precise modifications.
- **Enhanced User Interaction**: Designed to boost user engagement with an intuitive interface that offers immediate visual feedback.

## Getting Started

### Prerequisites

- Python 3.8 or newer
- TensorFlow 2.x
- OpenCV for image processing
- PixelLib for handling semantic segmentation

## How it works

1. Upload an Image: Start by uploading a high-resolution image of the interior space you wish to redesign.
2. Apply Semantic Segmentation: The platform automatically processes the image to detect and segment different elements like walls, floors, furniture, etc.
3. Customize Textures and Interiors: Choose from a wide range of textures and design elements to apply to different segments of your image.
4. Visualize Changes: Review the changes in real-time, make adjustments as needed, and finalize the design.

### Installation

Clone this repository to your local machine using the following command:
```bash
git clone https://github.com/your-username/visionary-ar-design-platform.git
