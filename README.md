# Time-Series-Analysis-of-Domestic-Airline-Fare-CPI
시계열 자료분석 소논문, 국내 항공료의 소비자물가지수에 대한 시계열 분석


본 연구에서는 2008년 1월부터 2023년 5월까지의 국내 항공료 소비자물가지수 데이터를 이용하여 시계열 분석을 실시하였다. 먼저 국내 항공료 소비자물가지수 데이터의 산포도를 통해 전체적인 추세를 확인하였고, 분산은 일정하나 평균은 일정하지 않은 비정상 시계열인 것을 확인하였다. 또한 데이터의 산포도와 ACF, PACF를 통해 계절성이 존재한다고 판단하였다. 이를 정상 시계열로 만들기 위해 차분의 필요성을 느껴 일차 차분과 계절 차분을 진행하였다. 일차 차분과 계절 차분만 각각 진행한 경우와 일차 차분과 계절 차분을 같이 진행한 경우에서 총 7개의 잠정모형을 예측하였다. 이후 적합한 각 모형들 중 가장 적합한 모형을 채택하기 위해 7개의 모형들에 대한 모수 유의성 검정과 잔차에 대한 퍼트맨토우 검정을 진행하였다. 하지만 해당 과정을 통해 7개 모형들의 잔차가 모두 백색잡음이 아니라는 결론을 얻어 부적절한 모형이라 판단하였고, 추가로 ACF와 PACF를 덜 고려하여 모형을 적합해보았다. 그 결과 모수가 모두 유의하고 잔차가 백색잡음인 를 제외한 ARIMA(0,1,2)(2,1,1모형을 채택하였다. 해당 모형의 AIC와 SBC의 값이 예측한 모형들 중 가장 작은 값을 가지고, 추가로 잔차가 정규성을 만족하는지에 대하여 잔차의 분포 그래프와 QQ-Plot을 이용해 살펴본 결과 정규성을 만족한다고 판단하여 본 모형이 데이터를 설명하기에 가장 적합한 모형이라고 판단하였다. 최종모형을 통해 20 시점 미래, 즉 2023년 6월부터 2025년 1월까지의 20개의 국내 항공료 소비자물가지수를 예측했다. 예측해 본 결과, 국내 항공료 소비자물가지수는 꾸준히 주기성을 보이는 것을 볼 수 있으며, 증가와 감소의 형태를 보이지만 과거 대비 값이 소폭 증가했음을 볼 수 있다. 더욱 정확한 예측을 위해서는 경제적, 사회적인 여러 가지 요인들을 함께 고려하는 것이 좋을 것이다.
