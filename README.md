# Computer Vision Engineer

A collection of code and learning materials for studying and revising **Computer Vision**.  
Designed for those who want to practice the fundamentals and experiment with popular tools and frameworks.

#### Foundation

- [Basic Image Processing](./notebooks/image-processing.ipynb)
- [Linear Algebra / Matrix Ops](./notebooks/linear-algebra-matrix-ops.ipynb)

#### Core CV Models

- [Classic CV](./notebooks/classic-cv.ipynb)
- CNNs (Convolutional Neural Networks)
- - [Basic Deep Learning with 🔥Pytorch](./notebooks/basic-pytorch-dl.ipynb)
- - [LeNet-5](./notebooks/cnn-lenet-5.ipynb)
- - [AlexNet](./notebooks/cnn-alexnet.ipynb)
- - [VGG-16](./notebooks/cnn-vgg-16.ipynb)
- - [ResNet-18](./notebooks/cnn-resnet-18.ipynb)
- - [EfficientNet-B0](./notebooks/cnn-efficientnet-b0.ipynb)
- [Transfer Learning](./notebooks/transfer-learning.ipynb)

> PS. Each model was tested only on the CIFAR-100 dataset because it can be easily loaded from Torch, has a manageable data size, and includes a reasonable number of classes for experimentation.

#### Advanced CV Architectures

- Object Detection
- - Ultralytics YOLOv8
- - Detectron2 (Facebook AI Research)
- - MMDetection (OpenMMLab)
- - DETR (Facebook) / DINO / RT-DETR

- Image Segmentation
- - U-Net / U-Net++ (PyTorch / Segmentation Models PyTorch)
- - DeepLabV3 / DeepLabV3+ (TorchVision Model Zoo)
- - Mask R-CNN (Detectron2 / MMDetection)
- - Segment Anything Model (SAM by Meta AI)
- - Meta’s Segment Anything 2 (SAM2)

- Vision Transformers (ViT)
- - Vanilla ViT (Vision Transformer)
- - DeiT (Data-Efficient Image Transformer)
- - Swin Transformer (Shifted Window Transformer)
- - ConvNeXt (Hybrid CNN + Transformer)
- - DINOv2 / MAE (Self-Supervised ViT)

- CLIP (Contrastive Language–Image Pretraining)

---

## Getting Started

1. Clone the repository

```bash
git clone https://github.com/morsechimwai/computer-vision-engineer.git
cd computer-vision-engineer
```

2. Install dependencies

```
pip install -r requirements.txt
```