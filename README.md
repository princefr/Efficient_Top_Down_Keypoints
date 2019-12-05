# Efficient_Top_Down_Keypoints
Efficient Top down keypoints running at 20 FPS (+ 20 Peoples)


We have been told that Top down keypoints detection is slow to process compared to bottom up keypoints detection but its not always true. using small feature model and thin output feature size, one can speed up Top down model to match the speed of the bottom up model.

 
 [![Video](https://img.youtube.com/vi/VID/0.jpg)](https://www.youtube.com/watch?v=2728C0bnmLo&feature=youtu.be)


# Result on coco Dataset.
```
IoU metric: bbox
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.494
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets=100 ] = 0.769
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets=100 ] = 0.547
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = -1.000
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.411
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.544
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=  1 ] = 0.251
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 10 ] = 0.583
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets=100 ] = 0.598
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= small | maxDets=100 ] = -1.000
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets=100 ] = 0.546
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets=100 ] = 0.634
IoU metric: keypoints
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=   all | maxDets= 20 ] = 0.545
 Average Precision  (AP) @[ IoU=0.50      | area=   all | maxDets= 20 ] = 0.741
 Average Precision  (AP) @[ IoU=0.75      | area=   all | maxDets= 20 ] = 0.583
 Average Precision  (AP) @[ IoU=0.50:0.95 | area=medium | maxDets= 20 ] = 0.458
 Average Precision  (AP) @[ IoU=0.50:0.95 | area= large | maxDets= 20 ] = 0.606
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=   all | maxDets= 20 ] = 0.666
 Average Recall     (AR) @[ IoU=0.50      | area=   all | maxDets= 20 ] = 0.824
 Average Recall     (AR) @[ IoU=0.75      | area=   all | maxDets= 20 ] = 0.707
 Average Recall     (AR) @[ IoU=0.50:0.95 | area=medium | maxDets= 20 ] = 0.621
 Average Recall     (AR) @[ IoU=0.50:0.95 | area= large | maxDets= 20 ] = 0.698
```
