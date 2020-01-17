# 제 1회 비즈니스애널리틱스 빅데이터 경진대회 (우수상)

<br>

# 1. 대회 설명
## (1) 대회 내용
 - 2010년 부터 2019년 11월 19일까지 삼성전자의 주식 가격 데이터를 바탕으로 2020년 1월 10일의 주식 가격을 예측한다.
 - 머신러닝, 딥러닝 등 어떠한 예측 방법도 허용된다.
 - 결과물은 예측 모델과 모델을 추정하는 방법에 대해서 간결히 설명해야 한다.

<br>

## (2) 평가 방법
 - 2020년 1월 10일의 삼성전자 주식 가격을 가장 정확하게 예측하는 팀이 우승한다.
 - RMSE
 - 예측 모델의 창의성과 정확성

<br>

## (3) 데이터
 - 2010년 부터 2019년 11월 19일까지의 주식 가격
 - 동기간 일별 코스피 지수
 - 삼성전자 일별 수익률 자료
 - 하이닉스 일별 수익률 자료
 
<br>
<hr>
<br>

# 2. 결과물
## (1) 모델 구성
 - 모델 : LSTM
 - Loss : Mean Squared Error
 - Optimizer : rmsprop
 - Batch size : 10
 - Epochs : 15

<br>

## (2) 결과물
 - Loss : 0.0053
 - Val Loss : 0.0055
 - 예측 값 : 56405.17

<br>
<hr>
<br>

# 3. 수상 내역
 - 수상 일 : 2020년 1월 15일
 - 수상 내용 : 우수상
 - 수상자 : 서기원(컴퓨터공학과), 이한들(디지털콘텐츠학과)
