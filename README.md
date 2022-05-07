# Make Yourself In Party (MYIP)
---
## 프로젝트 목표
* OpenCV를 이용한 이미지 처리 관련 프로그램 개발
 * Camera에서 캡처된 영상에서 얼굴을 인식하여 배경을 제거한 후 다른 영상으로 배경을 대체함
 * 해당 영상 위에 투명 이미지를 Overlay하여 꾸밀 수 있게 함 (투명 이미지는 Track Bar를 이용하여 선택)
 * 랜덤 주기로 랜덤 색상의 도형을 배경에 그림

## 사양
- Grab Cut 기술을 이용하여 배경을 잘라내고, 지정된 파일에 포함된 영상으로 변경한다.
- 배경에서 생성되는 도형(원)은 랜덤 색상 및 위치를 가지고 점점 커지며 반투명하다.
- Trackbar를 사용하여 선택한 투명 이미지는 클릭 후 드래그를 통해 크기 및 위치를 선택하여 영상에 직접 추가할 수 있다.

## 사용하는 OpenCV 기술
- Drawing
- Transparent Image Overlay
- Grab Cut
- Face Recognition
- Track Bar