# NeuralArt AI - Neural Style Transfer with AdaIN

Transform ordinary images into artistic masterpieces using Adaptive Instance Normalization (AdaIN) and Deep Learning.

## Overview

NeuralArt AI is a web-based application that performs neural style transfer by combining the content of one image with the artistic style of another. The project leverages the AdaIN architecture with a VGG19 encoder and a custom decoder network to generate stylized outputs efficiently.

## Features

- Neural Style Transfer using AdaIN
- Upload custom content and style images
- Adjustable style strength
- Real-time image generation
- Download generated artworks
- Responsive web interface
- Cloud deployment support with Render

## Tech Stack

### AI & Deep Learning
- Python
- PyTorch
- Torchvision
- AdaIN (Adaptive Instance Normalization)
- VGG19 Encoder
- Custom Decoder Network

### Backend
- Flask
- Gunicorn

### Frontend
- HTML5
- CSS3
- JavaScript
- Jinja2 Templates

### Deployment & Tools
- Render
- Git
- GitHub

## Model Architecture

```text
Content Image ──► VGG19 Encoder ──┐
                                  ├──► AdaIN ───► Decoder ───► Stylized Output
Style Image ─────► VGG19 Encoder ─┘
```

## Project Structure

```text
NeuralArt-AI/
│
├── NST_Code/
│   ├── app.py
│   ├── train.py
│   ├── vgg_normalised.pth
│   ├── experiment/
│   │   └── final_exp/
│   │       └── decoder_final.pth
│   ├── static/
│   ├── templates/
│   ├── utils/
│   ├── style_data/
│   └── content_data/
│
├── Procfile
├── requirements.txt
├── runtime.txt
├── README.md
└── .gitignore
```

## Deployment

The application is configured for deployment on Render using Gunicorn and a Procfile.

## Future Improvements

- Multiple artistic presets
- Higher-resolution inference with optimized memory usage
- User gallery and history
- Batch style transfer
- Mobile-friendly UI enhancements
- Hugging Face Spaces deployment

## Author

**Rohitha Panchamukhi M**

Computer Science Engineer (IoT, Cybersecurity & Blockchain Technology)  
AI & Machine Learning Enthusiast

## Tags

`Python` `PyTorch` `Flask` `AdaIN` `VGG19` `Neural Style Transfer` `Deep Learning` `Computer Vision` `Image Processing` `Torchvision` `HTML5` `CSS3` `JavaScript` `Jinja2` `Gunicorn` `Render` `Git` `GitHub` `AI` `Machine Learning`
