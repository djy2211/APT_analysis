# APT_analysis

#1
국토교통부 아파트 실거래가 11월 기준

서울시 아파트 값 분석 /
전체 평균과 각 구별 평균 가격을 구하여 평균보다 높은 구와 낮은 구를 비교


***

***

#2

국토부에서 제공하고 있는 실거래가 자료는 2006년부터임

2006년부터 2023년까지 서울시 아파트 가격의 평균값을 구한 후, 추후 가격을 Prophet으로 예상

2028년 까지 급격하게 우상향 하는 그래프가 그려졌으나, Prophet은 주기와 패턴에 따라 값을 예상함으로 적절하지 않은 예측결과가 나옴

추후 시간이 있다면, 아파트 가격 예측에 대한 다른 접근 방향을 고민해야 할 것으로 보임.

***

ex. 국민 소득 데이터, 미국 금리, 주기에 따른 아파트 공급량 등 정형데이터셋을 만든 후에 

그 값에 따라 2006~2018년 데이터를 기반으로 2023년까지 예측을 시켜보고, 그 중에서 결과가 유사한 방법을 찾은 후 미래 값에 대입해보는 방식을 진행하는 것도 좋아 보임.

추 후 시간이 나면 시도할 예정
