## 2024 영주시 공모전 Project_Fkiler

![fruit-3860991_1280](https://github.com/minkyunglee1012/Project_Fkiller/assets/156975194/43b786ef-ab7f-4535-9dec-38f90bfe12d9)



[Chapter 01. 영주시 관련 뉴스 크롤링](https://github.com/minkyunglee1012/Project_Fkiller/tree/master/01.01%20%EC%98%81%EC%A3%BC%EC%8B%9C%20%EA%B4%80%EB%A0%A8%20%EB%89%B4%EC%8A%A4%20%ED%81%AC%EB%A1%A4%EB%A7%81)

<p>$\small{\rm{\color{#DD6565}네이버 및 다음에서 키워드(영주시 관련) 뉴스 기사를 크롤링 해오는 코드를 만든 후, }}$</p>
<p>$\small{\rm{\color{#DD6565}네이버 크롤링을 통해 우리의 주제인 사과 모양으로 워드 클라우드를 작성하였다.}}$</p>


---

[Chapter 02.데이터 전처리](https://github.com/minkyunglee1012/Project_Fkiller/tree/master/01.02%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%A0%84%EC%B2%98%EB%A6%AC)

<p>$\small{\rm{\color{#DD6565}사전에 강수량 결측치는 전날 강수량, 주변 지역 강수량 등을 참고하여 수정하였고 Pandas를 통해 나머지 컬럼들 결측치를 평균값으로 대체하였다.}}$</p>
<p>$\small{\rm{\color{#DD6565}그 후 히트맵을 그려 속성들 간의 상관관계를 분석하였고, 다중공선성을 고려하여 속성들끼리 관계가 높은 것은 제거하였다.}}$</p>
<p>$\small{\rm{\color{#DD6565}타겟을 평균가격, 총거래물량, 총거래금액 3가지로 각각 모델링하여 가장 예측 결과가 좋게 나온 타겟을 우리의 최종 모델링에 사용 하기로 하였다.}}$</p>

---

[Chapter 03. 영주시 날씨에 따른 사과 가격/양 예측](https://github.com/minkyunglee1012/Project_Fkiller/tree/master/01.03%20%EC%98%81%EC%A3%BC%EC%8B%9C%20%EB%82%A0%EC%94%A8%EC%97%90%20%EB%94%B0%EB%A5%B8%20%EC%82%AC%EA%B3%BC%20%EA%B0%80%EA%B2%A9%20%EC%98%88%EC%B8%A1)

---

[Chapter 04. 영주시 사과 가격에 따른 등급 예측](https://github.com/minkyunglee1012/Project_Fkiller/tree/master/01.04%20%EC%98%81%EC%A3%BC%EC%8B%9C%20%EC%82%AC%EA%B3%BC%20%EA%B0%80%EA%B2%A9%EC%97%90%20%EB%94%B0%EB%A5%B8%20%EB%93%B1%EA%B8%89%20%EC%98%88%EC%B8%A1)
