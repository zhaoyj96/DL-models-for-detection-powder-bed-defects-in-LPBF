# SSD: Single Shot MultiBox Detector


## Environment configuration.
* Python 3.6/3.7/3.8
* Pytorch 1.7.1
* pycocotools (Linux: ``pip install pycocotools``; Windows: ``pip install pycocotools-windows``)
* Ubuntu or Centos or Windows
* Preferably using GPU training


## Pre-trained weights download at.
* ResNet50+SSD: https://ngc.nvidia.com/catalog/models  
 ` Search ssd -> find SSD for PyTorch(FP32) -> download FP32 -> unpack the file`


## Training method
* Make sure the dataset is prepared in advance
* Make sure to download the corresponding pre-trained model weights in advance
* Single GPU training or CPU, use train.py training script directly

## Testing method
* Use the predict.py test script directly
