
## Object-detection-using-Mask-RCNN

### Problem statement

The COCO dataset is large image dataset designed for
Object Detection, Segmentation, person key points
detection, and Caption Generation. The objective is to
use Mask RCNN technique for instance segmentation
on the COCO dataset

COCO is a large-scale object detection, segmentation, and captioning dataset. COCO has
several features:
- Object segmentation
- Recognition in context
- Superpixel stuff segmentation
- 330K images (>200K labeled)
- 1.5 million object instances
- 80 object categories
- 91 stuff categories
- 5 captions per image
- 250,000 people with keypoints

In this project
- First cloned the Facebook Detectron Model using this link: https://github.com/facebookresearch/Detectron
- Loaded the pretrained weights from : 
https://dl.fbaipublicfiles.com/detectron/36494496/12_2017_baselines/e2e_mask
_rcnn_X-101-64x4dFPN_1x.yaml.07_50_11.fkwVtEvg/output/train/coco_2014_train%3Acoco_2014_v
alminusminival/generalized_rcnn/model_final.pkl
- Used the Mask RCNN Architecture and the pre-trained weights to generate predictions for
your own images or images from the COCO dataset
- Visualized the Results


