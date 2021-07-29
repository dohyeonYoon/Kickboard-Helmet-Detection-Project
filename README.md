# yolov4 kickboard-helmet detector
Training yolov4 custom dataset using google colab


![test11](https://user-images.githubusercontent.com/66056440/127437775-50315941-2408-4023-8cf1-4acb22a522a8.png)
![새로운 프로젝트](https://user-images.githubusercontent.com/66056440/127440655-4095ffbf-a665-4328-8a59-02dd98a2303f.gif)

## **kickboard helmet detection using YOLOv4**

The **yolov4** folder in this repository contains the 4 custom files needed. (i.e. **yolov4-custom.cfg**, **obj.data**, **obj.names** and **process.py**) except **obj.zip**(labeled images). 



The **obj.zip** file contains 908 images along with their YOLO labeled text files. I have labeled around 908 of these. 


**<ins>NOTE</ins>** : The **yolov4-custom.cfg**, **obj.data**, and **obj.names** files are customized for the 2 classes I am working with. (i.e. "helmet" & "no_helmet"). You can edit these files for your custom objects.


## My Colab notebook for training a custom Yolov4 detector

https://colab.research.google.com/drive/16biTYL3mgmbJghKDcjzKArI81vnGuYZr#scrollTo=Py0DQRy4HHDH

## My Medium article on this

https://dohyeon.tistory.com/9?category=1006878

## References

[AlexeyAB GitHub](https://github.com/AlexeyAB/darknet/)
