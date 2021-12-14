# Anime-face-detection-notebook
Using Faster RCNN to detect Anime face. hope it will help you. And the Code is based on pytorch.

### Result

![pred00006](https://image-2021-wu.oss-cn-beijing.aliyuncs.com/blogs/picturespred00006.jpg)

### dataset

I found the dataset from :point_right: https://github.com/qhgz2013/anime-face-detector. But I only used 2000 images for training. 

### Training

I trained 25 epochs on Tesla P4, which costed 76min. And using Resnet50 for backbone. It shows a good loss curve.

![resnet50](https://image-2021-wu.oss-cn-beijing.aliyuncs.com/blogs/picturesresnet50.png)

### File

`Anime_face_dection.ipynb`: All in One.
