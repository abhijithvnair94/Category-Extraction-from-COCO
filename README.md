# Class-Extraction-from-COCO

  COCO dataset 2014 is a collection of 123k image of 91 categories. The code I provided can be used for the extraction of a specific class from the whole dataset. The dataset provides its annotations in a **.json file**. The json file format structure can be understand from [here](https://github.com/alwynmathew/COCO-annotation-structure).

  The code provided in this repo help you to extract the images of specific category from the whole dataset. This one is for car category.You can change the ID inside the code as:

```
id = 3   # change to each category ID                  
```
Also change the path file to save the image seperately.

Categories included in COCO 2014 are :- 

'person', 'bicycle', 'car', 'motorcycle', 'airplane', 'bus', 'train', 'truck', 'boat', 'traffic light', 'fire hydrant', 'stop sign', 'parking meter', 'bench', 'bird', 'cat', 'dog', 'horse', 'sheep', 'cow', 'elephant', 'bear', 'zebra', 'giraffe', 'backpack', 'umbrella', 'handbag', 'tie', 'suitcase', 'frisbee', 'skis', 'snowboard', 'sports ball', 'kite', 'baseball bat', 'baseball glove', 'skateboard', 'surfboard', 'tennis racket', 'bottle', 'wine glass', 'cup', 'fork', 'knife', 'spoon', 'bowl', 'banana', 'apple', 'sandwich', 'orange', 'broccoli', 'carrot', 'hot dog', 'pizza', 'donut', 'cake', 'chair', 'couch', 'potted plant', 'bed', 'dining table', 'toilet', 'tv', 'laptop', 'mouse', 'remote', 'keyboard', 'cell phone', 'microwave', 'oven', 'toaster', 'sink', 'refrigerator', 'book', 'clock', 'vase', 'scissors', 'teddy bear', 'hair drier', 'toothbrush'
