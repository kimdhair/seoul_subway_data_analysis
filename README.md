# seoul_subway_data_analysis

## 1. 프로젝트 개요
- 주제
  - 우리 생활에 밀접한 교통수단인 지하철의 이용량을 분석
 
- 목적
  - 매일 같이 이용하는 대중 교통을 분석하여 가장 여유롭게 지하철을 이용하기 위해 이용량을 확인

- 사용 데이터
  - 서울 열린 데이터 광장에서 서울시 지하철 이용량 데이터 다운받아 사용

## 2. 데이터 시각화 및 결과
- 데이터 전처리 / pandas
  - 이상 값 제거, 중복 제거, 타겟 데이터 선정 및 병합
 
- 결과 / matplotlib, seaborn
  - 2호선이 약 전체의 20%의 이용량을 보임
  - 출퇴근 시간대인 8-9, 18-19시에 가장 많은 이용량을 보임
  - 코로나 초기 이용량 급락 후 정상화 단계

<img src="https://github.com/kimdhair/seoul_subway_data_analysis/blob/main/img/%EB%85%B8%EC%84%A0%EB%B3%84%20%EC%9D%B4%EC%9A%A9%EB%9F%89.png?raw=true" width="30%"><img src="https://github.com/kimdhair/seoul_subway_data_analysis/blob/main/img/%EC%8B%9C%EA%B0%84%EB%8C%80%EB%B3%84%20%EC%9D%B4%EC%9A%A9%EB%9F%89.png?raw=true" width="30%"><img src="https://github.com/kimdhair/seoul_subway_data_analysis/blob/main/img/%EC%9B%94%EB%B3%84%20%EC%B4%9D%20%EC%9D%B4%EC%9A%A9%EB%9F%89.png?raw=true" width="30%"></img>
