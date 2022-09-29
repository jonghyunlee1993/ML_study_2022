# ML study 2022

- 2022년도 9월 29일 ~ 
- 교재: 파이썬 머신러닝 완벽 가이드 (1판), 권철민 저
- [스터디 개요](https://geode-stage-e25.notion.site/ML-study-ddc4e57ce1324c47bace4c10f0e78cb2)



## 1주차

- 따릉이 데이터를 이용한 결측값 처리 및 간단한 regression 문제 풀이

    - Source: (데이콘)[https://dacon.io/competitions/open/235576/overview/description]

    - Data description

        - X: 시간, 온도, 강수량, 풍속, 습도, 시계거리, 오존, pm10, pm2.5
        - y: 따릉이 대여 횟수

    - Model

        - Random forest (untuned)

    - Metrics

        - RMSE

    - Approaches

        - Mean filling: 45.63263

        - Median filling: 44.8944

        - KNN imputation: 45.16413

        - Linear interpolation: 46.2823

- 특별히 튜닝을 진행하지 않아 성능은 전체 대회 성적 중 32% 정도. 그럼에도 불구하고 imputation만 해줘도 성능 개선되는 것을 확인하였음. GAN 등을 이용한 imputation을 추후 적용해볼 생각.