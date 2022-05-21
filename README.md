# project-opencv - Caltech101 Object Recognition

### 1. DenseDetector 클래스
### 2. Quantizer 클래스 - 벡터 양자화를 계산하고 특징 벡터 생성
### 3. FeatureExtractor 클래스
### 4. SIFT 특정 탐지자 


## 🔨 개발환경
- opencv 3.4.0.16
- python 3.6
- pycharm 2021.3

## ✍🏻 방법
- 교재 9장 내용 기반 객체인식(즉, SIFT + Kmeans Clustering + BoW + SVM)
이 틀 안에서 팀별 파라미터 조정, 약간의 아이디어 추가, 삭제 가능
- 데이터셋: Caltech101(https://www.kaggle.com/datasets/athota1/caltech101) 
- 5개의 카테고리(클래스)에 대해, 학습데이터, 테스트데이터 구분
images_0001부터 images_0030까지 학습데이터, 나머지는 테스트데이터로 사용 - 경쟁을 위한 코드 작성

## 😅 경쟁 Competition
- 최종발표일 5개 카테고리 제시
- 각 카테고리 마다 첫 30개의 영상 데이터 학습
- 데이터 테스트 제시 > 분류 결과 제출 > 정확도 산출
- 팀간 정확도 1% 이하 차이는 평가자 재량으로 무시할 수 있음 - 정확도 외 방법론의 합리성, 독창성, 발표 등 평가


## ✅ 일정
- 22일 일요일 저녁 8시 줌으로 공부한 자료 공유
- 23일 월요일 오전까지 ppt 공유 및 수정
- 24일 화요일 4시전 제출
- 25일 수요일 중간발표!
- 6/8 (수) 팀별토론
- 6/15 (수) 팀별토론 - 대면수업
- 6/17 (금) 팀별 마무리 토론, 최종발표 - ppt준비, 경쟁, 채점, 동료평가


## 🌄 이미지 클래스 후보
- 데이터셋: Caltech101(https://www.kaggle.com/datasets/athota1/caltech101) 
1. cup
2. butterfly
3. stop_sign
