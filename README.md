# 교내 전동킥보드 헬맷 단속모델 개발 프로젝트

전북대학교 교내에서 촬영한 데이터셋을 이용해 YOLOv4 model 학습(using google colab)

# 시연영상
![test11](https://user-images.githubusercontent.com/66056440/127437775-50315941-2408-4023-8cf1-4acb22a522a8.png)
![ìƒˆë¡œìš´ í”„ë¡œì íŠ¸](https://user-images.githubusercontent.com/66056440/127440655-4095ffbf-a665-4328-8a59-02dd98a2303f.gif)

## **kickboard helmet detection using YOLOv4**

The **yolov4** folder in this repository contains the 4 custom files needed. (i.e. **yolov4-custom.cfg**, **obj.data**, **obj.names** and **process.py**) except **obj.zip**(labeled images). 



The **obj.zip** file contains 908 images along with their YOLO labeled text files. I have labeled around 908 of these. 


**<ins>NOTE</ins>** : The **yolov4-custom.cfg**, **obj.data**, and **obj.names** files are customized for the 2 classes I am working with. (i.e. "helmet" & "no_helmet"). You can edit these files for your custom objects.


## YOLOv4 model training을 위한 코랩노트북

https://colab.research.google.com/drive/16biTYL3mgmbJghKDcjzKArI81vnGuYZr#scrollTo=Py0DQRy4HHDH

## 사용법 설명 블로그

https://dohyeon.tistory.com/9?category=1006878

## 참조

[AlexeyAB GitHub](https://github.com/AlexeyAB/darknet/)
"»õ·Î¿î ±â´É Ãß°¡" 
