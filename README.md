# IMEN321 데이터마이닝
고려대학교 IMEN321 데이터마이닝을 수강하면서 진행한 프로젝트입니다.
주제는 'E-commerce 시장에서의 상품명을 통한 카테고리 분류'입니다.

과정은 다음과 같습니다.

1) 대상 데이터 크롤링 (G-market, Robots.txt = True 확인)
2) 상품명을 정규화(Stemming) 및 명사만 분류 (상품명은 명사가 주로 의미가 있다고 판단)
3) Train_data, Test_data로 나눈 후, TF / TF-IDF 값 계산
4) TF만 모델에 넣어보고, TF-IDF 또한 모델에 넣어봄 (다양한 모델)
5) LDA(Latent Dirich Alloaction) 진행
6) L-LDA (Labeled - LDA) 진행
