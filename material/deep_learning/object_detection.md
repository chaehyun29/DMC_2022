# Object Detection

다음 2가지 작업을 실행

- 물체의 위치를 탐지(localization)
- 물체를 분류(classification)

물체 분류는 제시된 영상에 특정 대상의 유무를 판단하는 작업

![분류예](object_detection1.png)

물체 탐지는 특정 대상의 위치와 대상을 판단한는 작업
![믈체탐지예](object_detection2.png)

이외에 다른 작업들도 있다.
![이외 작업들](object_detection3.png)

<br>


# YOLO

- YOLO 설명 자료 : https://docs.google.com/presentation/d/1aeRvtKG21KHdD5lg6Hgyhx5rPq_ZOsGjG5rJ1HP7BbA/edit	

<br>

## DarkNet 사용

TensorFlow나 pythoh 기반이 아닌 c/c++로 구현된 Darknet을 기반으로 한다.

- DarkNet 홈 : https://pjreddie.com/darknet/
- YOLO 홈 : https://pjreddie.com/darknet/yolo/
- YOLO 프로젝트 : https://github.com/pjreddie/darknet

다만 미리 학습된 모델의 weight 파일을 제공한다.


- 실습 자료 : [object_detection_yolo_darknet.ipynb](object_detection_yolo_darknet.ipynb)  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/DMC_2022/blob/master/material/deep_learning/object_detection_yolo_darknet.ipynb)

- 적용 예 : https://drive.google.com/file/d/1ZGiJtRBG8wyI3nn8oI9iKqJC4zOitghT/view?usp=sharing

<br>


## Keras 사용

- 실습 자료 : [keras_yolov3.ipynb](keras_yolov3.ipynb)   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/DMC_2022/blob/master/material/deep_learning/keras_yolov3.ipynb)


<br>


## 커스텀 데이터 학습

- raccoon 데이터 학습 : [train_yolov3_raccoon_train.ipynb](train_yolov3_raccoon_train.ipynb)   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/DMC_2022/blob/master/material/deep_learning/train_yolov3_raccoon_train.ipynb)

- raccon 데이터 탐지 실행 : [keras_yolov3_custom_model.ipynb](keras_yolov3_custom_model.ipynb)   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/DMC_2022/blob/master/material/deep_learning/keras_yolov3_custom_model.ipynb)

<br>

## YOLO를 사용한 얼굴 인식

- face 데이터 탐지 실행 : [face_recognition_with_2_models.ipynb](face_recognition_with_2_models.ipynb)   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dhrim/DMC_2022/blob/master/material/deep_learning/face_recognition_with_2_models.ipynb)


<br>

## 레이블링 방법

- 레이블링 가이드 by labelImg : [yolo_labeling_guide.pdf](yolo_labeling_guide.pdf)
- 레이블링 가이드 by makesense : [yolo_labeling_guide_by_makesense.pdf](yolo_labeling_guide_by_makesense.pdf)

<br>

# 레이블링 툴

- https://www.makesense.ai
- https://github.com/tzutalin/labelImg

<br>
