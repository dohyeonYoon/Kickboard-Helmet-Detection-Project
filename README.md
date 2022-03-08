# 교내 전동킥보드 헬맷 단속모델 개발 프로젝트

전북대학교 교내에서 촬영한 데이터셋을 이용해 YOLOv4 model 학습(using google colab)

# 시연영상
![test11](https://user-images.githubusercontent.com/66056440/127437775-50315941-2408-4023-8cf1-4acb22a522a8.png)
![ìƒˆë¡œìš´ í”„ë¡œì íŠ¸](https://user-images.githubusercontent.com/66056440/127440655-4095ffbf-a665-4328-8a59-02dd98a2303f.gif)

# 간단 사용법
레포지토리 내 **yolov4** 폴더는 4개의 custom file이 들어있습니다.
(i.e. **yolov4-custom.cfg**, **obj.data**, **obj.names** and **process.py**) except **obj.zip**(labeled images). 

**obj.zip** 파일은 yolo format으로 레이블링된 텍스트 파일을 포함합니다. 
 
**<ins>NOTE</ins>**
**yolov4-custom.cfg**, **obj.data**, **obj.names** 3개의 파일을 본인이 찾고자 하는 class에 맞게 수정하여 사용하시면 됩니다.
(제 경우 helmet, no_helmet 2가지 class 사용)



## YOLOv4 model training을 위한 코랩노트북

https://colab.research.google.com/drive/16biTYL3mgmbJghKDcjzKArI81vnGuYZr#scrollTo=Py0DQRy4HHDH

## 사용법 설명 블로그

https://dohyeon.tistory.com/9?category=1006878

## 참조

[AlexeyAB GitHub](https://github.com/AlexeyAB/darknet/)
