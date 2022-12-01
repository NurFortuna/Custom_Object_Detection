# **TensorFlow 2  Custom Object Detection** :candy:

###  617  images are divided that 466 images were included in the training data set and 151 images were included in the test data set. In  data set, the traffic light (go, wait,stop)  are marked on the images and the coordinates have been converted to XML format for training. These clusters in the form of XML files have been converted into TFRecord files for training of the Tensorflow library, and important parameter changes have been made for training. ###
![image](https://github.com/NurFortuna/Custom_Object_Detection/blob/main/model4/test/test_images/test7.jpg)

##  Label Map ##
 
```
item {
    name: "stoplight",
    id: 1,
    display_name: "stoplight"
}
item {
    name: "stop",
    id: 2,
    display_name: "stop"
}
item {
    name: "wait",
    id: 3,
    display_name: "wait"
}
item {
    name: "go",
    id: 4,
    display_name: "go"
}


```

## Model-Master 2 ##
In this model I used **efficientnet _d1_coco 17 tpu-32** for object detection. 

### TensorBoard ###
![image](https://github.com/NurFortuna/Custom_Object_Detection/blob/main/model2/test/result_images/graphs.JPG)

![image](https://github.com/NurFortuna/Custom_Object_Detection/blob/main/model2/test/result_images/result2.png)
![image](https://github.com/NurFortuna/Custom_Object_Detection/blob/main/model2/test/result_images/result4.png)
![image](https://github.com/NurFortuna/Custom_Object_Detection/blob/main/model2/test/result_images/result5.png)
![image](https://github.com/NurFortuna/Custom_Object_Detection/blob/main/model2/test/result_images/result3.png)

## Model-Master 3 ##
In this model I used **ssd_mobilenet_v1_fpn_640x640_coco17_tpu-8** for object detection. 
### TensorBoard ###
![image](https://github.com/NurFortuna/Custom_Object_Detection/blob/main/model3/test/result_images/result1.JPG)

![image](https://github.com/NurFortuna/Custom_Object_Detection/blob/main/model3/test/result_images/result2.png)
![image](https://github.com/NurFortuna/Custom_Object_Detection/blob/main/model3/test/result_images/result1.png)

![image](https://github.com/NurFortuna/Custom_Object_Detection/blob/main/model3/test/result_images/result7.png)
![image](https://github.com/NurFortuna/Custom_Object_Detection/blob/main/model3/test/result_images/result5.png)


## Model-Master 4 ##
In this model I used **ssd_mobilenet_v1_fpn_640x640_coco17_tpu-8** for object detection. 
### TensorBoard ###
![image](https://github.com/NurFortuna/Custom_Object_Detection/blob/main/model4/test/result_images/tensorboard.JPG)

![image](https://github.com/NurFortuna/Custom_Object_Detection/blob/main/model4/test/result_images/2.png)
![image](https://github.com/NurFortuna/Custom_Object_Detection/blob/main/model4/test/result_images/1.png)

![image](https://github.com/NurFortuna/Custom_Object_Detection/blob/main/model4/test/result_images/4.png)
![image](https://github.com/NurFortuna/Custom_Object_Detection/blob/main/model4/test/result_images/5.png)



