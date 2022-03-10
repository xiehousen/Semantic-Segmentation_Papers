# semantic segmentation paper list

A paper list of  semantic segmentation.

*Last updated: 2022/02/15

#### Update log

*2022/January* - update some recent papers (TITS, PR, IEEE SPL, arXiv) of  semantic segmentation.  

##

## Table of Contents

- [Datasets](https://github.com/xiehousen/semantic-segmentation_papers/edit/main/README.md#Datasets)
- Metrics
- Performance tables
- Paper list

##

## Datasets

The papers related to datasets used mainly in natural/color image segmentation are as follows.

- [[Cityscapes]](https://paperswithcode.com/dataset/cityscapes)  **Cityscapes** is a large-scale database which focuses on semantic understanding of urban street scenes. It provides semantic, instance-wise, and dense pixel annotations for 30 classes grouped into 8 categories (flat surfaces, humans, vehicles, constructions, objects, nature, sky, and void). 
- [[Pascal VOC](http://host.robots.ox.ac.uk/pascal/VOC/)] **PASCAL VOC 2007** is a dataset for image recognition and image semantic segmentation.
- [[ADE20K](https://groups.csail.mit.edu/vision/datasets/ADE20K/)] The **ADE20K** semantic segmentation dataset contains more than 20K scene-centric images exhaustively annotated with pixel-level objects and object parts labels. There are totally 150 semantic categories, which include stuffs like sky, road, grass, and discrete objects like person, car, bed.

##

## Metrics
The papers related to metrics used mainly in RGBD semantic segmentation are as follows.

- **[PixAcc]**  Pixel  accuracy
- **[mAcc]**  Mean accuracy
- **[mIoU]** Mean intersection over union
- **[f.w.IOU]** Frequency weighted IOU
##

## Performance tables

We show several evaluation indicators and **backbones** used in the performance table, and indicate the year and source of the article.


## Performance tables

We show several evaluation indicators and **backbones** used in the performance table, and indicate the year and source of the article.

### Cityscapes

|    Method    | Backbone  | PixAcc | mAcc | mIoU(*val*) | mIoU(*test*) | f.w.IOU | Published | Year |
| :----------: | :-------: | :----: | :--: | :---------: | :----------: | :-----: | :-------: | :--: |
|    PSPNet    | ResNet101 |   -    |  -   |      -      |     78.4     |    -    |   CVPR    | 2017 |
|  BiseNet.V1  | ResNet101 |        |      |    80.3     |     78.9     |         |   ECCV    | 2018 |
| BiseNet.V2-L |           |   -    |  -   |    75.8     |     75.3     |    -    |           | 2020 |
|     STDC     |   STDC2   |        |      |    77.0     |     76.8     |         |   CVPR    | 2021 |



### CamVid

|    Method    | Backbone | PixAcc | mAcc | mIoU | f.w.IOU | Published | Year |
| :----------: | :------: | :----: | :--: | :--: | :-----: | :-------: | :--: |
|    PSPNet    | ResNet50 |   -    |  -   | 69.1 |    -    |   CVPR    | 2017 |
|  BiseNet.V1  | ResNet18 |        |      | 68.7 |    -    |   ECCV    | 2018 |
| BiseNet.V2-L |    -     |        |      | 73.2 |         |           | 2020 |



### ADE20K

|      Method      | Backbone  | PixAcc | mAcc | mIoU | f.w.IOU | Published | Year |
| :--------------: | :-------: | :----: | :--: | :--: | :-----: | :-------: | :--: |
|      PSPNet      | ResNet101 |   -    |  -   |  -   |    -    |   CVPR    | 2017 |
|    BiseNet.V1    |           |        |      |      |         |           |      |
|   BiseNet.V2-L   |           |   -    |  -   |      |    -    |           | 2020 |
|       STDC       |   STDC2   |        |      | 73.9 |         |   CVPR    | 2021 |
|     PFD(CNN)     | ResNet101 |        |      | 47.9 |         |   arXiv   | 2022 |
| PFD(Transformer) |  Swin-L   |        |      | 56.0 |         |   arXiv   | 2022 |



### PASCAL VOC 2012

|    Method    | PixAcc | mAcc | mIoU(*val*) | mIoU(*test*) | f.w.IOU | backbone  | Published | Year |
| :----------: | :----: | :--: | :---------: | :----------: | :-----: | :-------: | :-------: | ---- |
|    PSPNet    |   -    |  -   |      -      |     82.6     |    -    | ResNet101 |   CVPR    | 2017 |
| BiseNet.V2-L |   -    |  -   |    75.8     |     75.3     |    -    |           |           | 2020 |
|              |        |      |             |              |         |           |           |      |
|              |        |      |             |              |         |           |           |      |



##

## Paper list

- **[PSPNet]** Zhao H, Shi J, Qi X, et al. Pyramid scene parsing network[C]//Proceedings of the IEEE conference on computer vision and pattern recognition. 2017: 2881-2890. [[Paper](https://openaccess.thecvf.com/content_cvpr_2017/html/Zhao_Pyramid_Scene_Parsing_CVPR_2017_paper.html)] [Code]
- **[BiSeNet]** Yu C, Wang J, Peng C, et al. Bisenet: Bilateral segmentation network for real-time semantic segmentation[C]//Proceedings of the European conference on computer vision (ECCV). 2018: 325-341. [[Paper](https://arxiv.org/pdf/1808.00897.pdf)] [Code]
- **[STDC]** Fan M, Lai S, Huang J, et al. Rethinking bisenet for real-time semantic segmentation[C]//Proceedings of the IEEE/CVF conference on computer vision and pattern recognition. 2021: 9716-9725. [[Paper](https://arxiv.org/pdf/2104.13188.pdf)] [[Code](https://github.com/
  MichaelFan01/STDC-Seg)]
- **[PFD]** Qin Z, Liu J, Zhang X, et al. Pyramid Fusion Transformer for Semantic Segmentation[J]. arXiv preprint arXiv:2201.04019, 2022. [[Paper](https://arxiv.org/abs/2201.04019)] [Code]
- 

## Contact & Feedback

If you have any suggestions about this project, feel free to contact me.

- [e-mail: xiehousen[at]gmail.com]
