# Faster R-CNN


## The project is mainly from the source code in the official pytorch torchvision module
* https://github.com/pytorch/vision/tree/master/torchvision/models/detection


## Environment Configuration：
* Python3.6/3.7/3.8
* Pytorch1.7.1(Note: must be 1.6.0 or above, as it is only supported after 1.6.0 using the officially provided hybrid precision training)
* pycocotools(Linux:`pip install pycocotools`; Windows:`pip install pycocotools-windows`)
* Ubuntu or Centos or Windows
* See `requirements.txt` for detailed environment configuration


## Pre-training weights can be downloaded at：
* ResNet50+FPN backbone: https://download.pytorch.org/models/fasterrcnn_resnet50_fpn_coco-258fb6c6.pth

 
## Training method
* Ensure that the dataset is prepared in advance
* Ensure that the corresponding pre-trained model weights are downloaded in advance
* Use the train_resnet50_fpn.py training script directly

## Testing method
* Use the predict.py test script directly
