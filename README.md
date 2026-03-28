# Applied Computer Vision: Advanced GANs

Author: Keese Phillips

---

## Overview

This project explores advanced Generative Adversarial Network (GAN) architectures as part of an applied computer vision course. The implementation builds on foundational GAN concepts to investigate more sophisticated generative modeling techniques using PyTorch and supporting deep learning frameworks.

For a detailed discussion of the project methodology, experimental design, results, and evaluation, refer to the [Project Report (PDF)](./project_3.pdf).

## Repository Structure

```
.
├── README.md              # This file
├── requirements.txt       # Python dependencies (Colab environment snapshot)
├── project_3.pdf          # Full project report with methodology and evaluation
└── ...                    # Source notebooks and supporting files
```

## Environment

This project was developed and executed in Google Colab with GPU acceleration. The runtime environment uses Python 3.10 with CUDA 12.1 and the following core libraries:

- **PyTorch 2.5.1** (CUDA 12.1) with TorchVision 0.20.1 and TorchAudio 2.5.1
- **TensorFlow 2.17.1** with Keras 3.5.0
- **OpenCV 4.10.0** (opencv-contrib-python)
- **NumPy 1.26.4**, **SciPy 1.13.1**, **Matplotlib 3.8.0**
- **Hugging Face Diffusers 0.31.0** and Transformers 4.46.2
- **torchvision**, **timm 1.0.11**, **albumentations 1.4.20** for data augmentation and model architectures

The full dependency list is captured in `requirements.txt`, which reflects the complete Colab environment at the time of execution.

## Setup

### Running in Google Colab (recommended)

Open the project notebook directly in Google Colab and ensure a GPU runtime is selected under **Runtime > Change runtime type > T4 GPU** (or higher). The Colab environment includes most required packages by default.

### Running Locally

To replicate the environment locally, a CUDA-capable GPU with CUDA 12.1+ drivers is required.

```bash
# Clone the repository
git clone https://github.com/<your-username>/applied-cv-project-3.git
cd applied-cv-project-3

# Create and activate a virtual environment
python3.10 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

Note that `requirements.txt` contains the full Colab environment snapshot, which includes many packages beyond what this project strictly requires. A minimal installation covering PyTorch, TorchVision, OpenCV, NumPy, Matplotlib, and the Hugging Face libraries should be sufficient for most use cases.

## Attribution

This project references and builds upon material from [Modern Computer Vision with PyTorch](https://github.com/PacktPublishing/Modern-Computer-Vision-with-PyTorch) by Packt Publishing.

## License

This repository is submitted as coursework. Please refer to any applicable course policies regarding redistribution and reuse.
