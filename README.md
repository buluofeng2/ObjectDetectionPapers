# ObjectDetectionPapers
Some papers about SOD and some github-program about the papers

### 数据集
- COCO : https://paperswithcode.com/dataset/coco
  - cocoapi https://github.com/cocodataset/cocoapi
  - pip install numpy
  - conda install cpython
- LVIS : https://paperswithcode.com/dataset/lvis
- CIFAR10 : https://paperswithcode.com/dataset/cifar-10
## 代码
### Augmentation for small object detection
  - 跑不了，都只是工具项目，只是实现了小图片的复制黏贴罢了

    - https://github.com/zzl-pointcloud/Data_Augmentation_Zoo_for_Object_Detection

    - https://github.com/finepix/small_object_augmentation

    - https://github.com/gmayday1997/SmallObjectAugmentation

### YOLO V4
- 论文：https://arxiv.org/abs/2004.10934
- 源码：https://github.com/AlexeyAB/darknet
  - 上面的源码跑不通，换一个pytorch版本的
  - [yolov4-pytorch](https://github.com/Tianxiaomo/pytorch-YOLOv4)
- 使用教程 ： https://blog.csdn.net/Creama_/article/details/106209388
- yolo v4权重文件 ： https://drive.google.com/file/d/1cewMfusmPjYWbrnuJRuKhPMwRe_b9PaT/view
- issue:
  - mosaic=1: https://blog.csdn.net/yapifeitu/article/details/106001420
git
### Swin-Transformer
- 源码：https://github.com/SwinTransformer/Swin-Transformer-Object-Detection
  - https://link.zhihu.com/?target=https%3A//github.com/microsoft/Swin-Transformer
  - https://link.zhihu.com/?target=https%3A//github.com/SwinTransformer/Swin-Transformer-Semantic-Segmentation
### detectron2
- 源码 ： https://github.com/facebookresearch/detectron2
- intro: https://cloud.tencent.com/developer/article/1583634
- getting Started : https://detectron2.readthedocs.io/en/latest/tutorials/evaluation.html
- error : RuntimeError: DataLoader worker (pid 37593) is killed by signal: Bus error. It is possible that dataloader's workers are out of shared memory. Please try to raise your shared memory limit.
### faster-rcnn
- Code : https://github.com/ruotianluo/pytorch-faster-rcnn

### Swin-transformer
- Code : https://github.com/SwinTransformer/Swin-Transformer-Object-Detection
### pp yolo tiny
- Code : https://github.com/PaddlePaddle/PaddleDetection/blob/release/2.0/README_cn.md

### test
- 测试vscode中的git插件的使用效果
- 测试vscode中的服务器与本地代码同步的插件是否有效 -- 有效
