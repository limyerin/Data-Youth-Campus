# Data-Youth-Campus
2023 데이터청년캠퍼스


# 사용방법
> 9팀_식중독_시계열(기온, 약물포함).ipynb는 google colab을 이용<br>
> 코랩에서 ctrl + F9 를 눌러 모두실행 하시면 됩니다.<br>
> Jupyter Notebook으로 진행함<br>
  -	가격데이터 + ARIMA.ipynb<br>
  - 다변량 변수 예측.ipynb<br>
  - 상관분석.ipynb<br>
  - 습도데이터 + ARIMA.ipynb<br>
  - 온도데이터 + ARIMA.ipynb


# 데이터 소개
> 사용한 데이터들
- 2010-2022년 월별 기온(최저, 최고, 평균)
  - 2002_2022_month(edit).csv <br><br>
- 2010-2022 월별 습도(상대, 최저)
  - 위와 동일한 파일 <br><br>
- 2010-2022 월별 식중독 환자수
- 월별_연도별_식중독_통계(edit).csv <br><br>
- 월별_연도별_식중독_통계_(1).xls <br><br>
- 2010-2022 월별 약물금액
  - A05 2010-2022(edit).csv <br><br>
  - T61 2010-2022(edit).csv <br><br>
  - T78 2010-2022(edit).csv <br><br>


## 목차
1. 데이터로드 및 전처리(식중독 환자수, 기온, 약물가격 데이터)
   - 데이터 열 이름 재지정 및 타입 확인
3. 간단한 시각화(이상치, 추세그래프)
4. 상관분석
5. 식중독 환자수 ARIMA 모델 적용, 미래예측
6. 기온 ARIMA모델 적용
7. 약물가격 ARIMA모델 적용, 미래예측
8. 다변량분석(환자수, 기온, 약물가격) VAR모델 적용


## 결과
1. 상관분석
   1-1. 온도-습도 상관분석
   ![온도습도상관분석](https://github.com/limyerin/Data-Youth-Campus/assets/91580889/f133866d-d4fd-4ed6-824d-b558b0aedd33)
   
   1-2. 온도-습도-약물금액 상관분석
   ![온도습도약물금액상관분석](https://github.com/limyerin/Data-Youth-Campus/assets/91580889/767fee6a-2b2f-48a7-a2a2-771ec871e63b)
   
   1-3. 온도-습도-환자수 상관분석
   ![온도습도환자수상관분석](https://github.com/limyerin/Data-Youth-Campus/assets/91580889/78c5fe9e-102d-4e3d-9e71-fb704ef7cb3e)

3. 날씨 ARIMA 모델 적용
   ![날씨최저최고기온_아리마_결과](https://github.com/DanteKim07/Data_Youth_Camp/assets/101346639/1e7b455f-b52c-45ef-bf54-b359d8157cf9)

4. 식중독 ARIMA 모델 적용 및 예측
   3-1. 모델 적용 결과
   ![20_22식중독아리마](https://github.com/DanteKim07/Data_Youth_Camp/assets/101346639/02ff40e7-a7aa-49da-9d87-fd1694a80d6c)

   3-2. 미래 예측
   ![식중독_아리마_예측결과](https://github.com/DanteKim07/Data_Youth_Camp/assets/101346639/1b2439e5-b575-4b1a-87ee-23a5cfae22d0)

5. 약물금액 ARIMA 모델 적용 및 예측
   4-1. 모델 적용 결과
   ![약물금액_예측_그래프(A05, T78)](https://github.com/DanteKim07/Data_Youth_Camp/assets/101346639/4c126792-c71b-4cc7-a200-19de417b59d0)

   4-2. 미래 예측
   ![약물금액_미래_예측그래프](https://github.com/DanteKim07/Data_Youth_Camp/assets/101346639/0e9f924d-1174-4c03-941f-02c9f0eb50c9)

6. 다변량 변수 예측
   5.1 약물금액 다변량 변수 예측
![약물다변량변수예측](https://github.com/limyerin/Data-Youth-Campus/assets/91580889/77ad7cdf-d104-4fa0-b3aa-e2ab45a3404b)


#### 개발 환경 설정

python

jypyter notebook

google colab
![image](https://github.com/limyerin/Data-Youth-Campus/assets/91580889/7487a060-9dac-4cab-a068-b94cae32caa5)
