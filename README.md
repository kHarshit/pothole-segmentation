# pothole-segmentation

Real-time Pothole Detection and Segmentation using Deep Learning

[Paper link]()

> The potholes found on the Indian roads prove to be conundrum to avoid while driving. This
work deals with the automatic detection and segmentation of potholes on the roads using
deep learning. This task is solved using instance segmentation, one of the remarkable
applications of Computer Vision. We test the instance segmentation models viz. Mask R-CNN
and YOLACT, pretrained on MS COCO and fine tune it on our custom pothole dataset. Our
trained YOLACT model is able to identify potholes with 0.81 accuracy on the test dataset and
can achieve near real-time speed, while Mask R-CNN achieves 0.86 accuracy but with lower
inference speed.

## Experiments

![hyperparam_tuning](https://user-images.githubusercontent.com/20869671/144581821-d27e8f82-c5fe-41ed-b826-8c779ea76335.png)
![quantitative_comparison](https://user-images.githubusercontent.com/20869671/144581200-e3b561be-871d-440a-a529-8d4344cd5872.png)

## Results

![potholeimg1](https://user-images.githubusercontent.com/20869671/144580955-53b01356-46dc-4378-8f84-710a5034bb57.png)
![potholeimg2](https://user-images.githubusercontent.com/20869671/144580971-f4c494eb-0944-4a27-9001-b88790fed72a.png)
