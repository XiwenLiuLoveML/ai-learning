
# Aircraft Damage Classification and Multimodal Captioning with Cross-Attention

## Project Overview

This project develops an automated system capable of:
- **Classifying aircraft and detecting damage** from images using VGG16 feature extraction.
- **Generating descriptive captions and summaries** for the images using a pretrained BLIP model.
- **Integrating a custom Cross-Attention layer** to enhance multimodal learning.

The project demonstrates practical applications in the aviation industry for damage detection and reporting.

## Key Steps

1. Load and preprocess the dataset.
2. Extract features using VGG16.
3. Build and compile a classification model in Keras.
4. Implement and use a custom Cross-Attention layer.
5. Train the classification model.
6. Plot training and validation accuracy curves.
7. Predict and visualize model results.
8. Generate captions using the BLIP pretrained model.
9. Summarize image content and visualize BLIP model architecture.

## Installation

```bash
pip install torch torchvision tensorflow transformers matplotlib scikit-learn
