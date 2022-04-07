# project_stock

bootstrap 템플릿을 이용하여 주가정보를 다양하게 나타내고, 다음 장날의 주가 정보를 제공하는 웹페이지 생성

<img width="100%" src="https://user-images.githubusercontent.com/67838477/162278544-2a6e5979-e3ee-4d09-afff-ec17165b6201.PNG">

- 현재 주가와 함께 국내 지수, 미국 지수 표기, 설정 기간만큼의 주가 추이 차트로 구현
- ARIMA모델을 활용해 다음 장날 주가 예측. 예측에는 한달분량의 주가 데이터를 이용했고, 모델 update를 통한 예측 방식 사용

