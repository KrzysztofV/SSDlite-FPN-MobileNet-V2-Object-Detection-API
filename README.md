# SSDlite-FPN-MobileNet-V2-Object-Detection-API
Modified Object Detection API with custom SSDlite FPN MobileNet V2 model.

This repository contains only changed files from original Object Detection API:
https://github.com/tensorflow/models/tree/master/research/object_detection

The default SSDlite FPN MobileNet V2 model from Object Detection API is large and slow.
This modified model is much faster and has almost the same detection performance, especially for small objects.

Model in action:
https://www.youtube.com/watch?v=B2pxJw-a7mA                                                                                               
https://www.youtube.com/watch?v=oJNjzayapmY                                                                                               
https://www.youtube.com/watch?v=2smyLoS-MIA

Modified SSDlite FPN MobileNet V2:
![model diagram](https://raw.githubusercontent.com/KrzysztofV/SSDlite-FPN-MobileNet-V2-Object-Detection-API/master/fpn%20model.png)

Anchors scale and aspect ratios (23x40 feature map):
![Anchor scale and aspect ratios](https://raw.githubusercontent.com/KrzysztofV/SSDlite-FPN-MobileNet-V2-Object-Detection-API/master/anchors%20on%2023x40%20feature%20map.png)

Number of detections on individual feature maps:
![Number of detections](https://raw.githubusercontent.com/KrzysztofV/SSDlite-FPN-MobileNet-V2-Object-Detection-API/master/number%20of%20detections.png)

Performance comparison:
![Number of detections](https://raw.githubusercontent.com/KrzysztofV/SSDlite-FPN-MobileNet-V2-Object-Detection-API/master/comparison.png)
