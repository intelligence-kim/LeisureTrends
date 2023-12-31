# 포스트 코로나 전/후 여가시간 동향 조사 및 심리 분석

## 프로젝트 소개
포스트 코로나라 불리우는 현시대에서 여가시간의 변화와 그에따른 사람들의 주요 심리를 시각화하여 파악해본다.
<br>

## 프로젝트 기술 소개
 - 시각화 라이브러리 : matplotlib / wordcloud /networkX 를 활용하여 다양한 시각화 진행 및 분석을 통한 유의미한 결론 도출
 - 크롤링 라이브러리 : BeautifulSoup4 / Selenium
 - 토픽 모델링 : LDA

## 개발 기간
 * 23.03.10 - 23.03.15 (5일)

## 구성원
 - 김지성(팀장) : 여가시간 동향 분석 및 소비 심리 파악
 - 박기영 : 영화 시장 동향 분석
 - 배선화 : 여가시간 동향 분석
 - 윤영주 : 공연 시장 동향 분석

## 사용 언어
 - python

## 프로젝트 분석 결과
## 데이터 수집
 - [문화 빅데이터 플랫폼(여가/문화 유형별 관심도)](https://www.bigdata-culture.kr/bigdata/user/data_market/detail.do?id=6a5451f0-eb98-11ec-a6e8-cdf27550dc0d)
 - [문화 빅데이터 플랫폼(여가시간 활용 목적)](https://www.bigdata-culture.kr/bigdata/user/data_market/detail.do?id=62b70280-eb98-11ec-a6e8-cdf27550dc0d)
 - [문화 빅데이터 플랫폼(하루 평균 여가문화 시간 및 사용 비중)](https://www.bigdata-culture.kr/bigdata/user/data_market/detail.do?id=e057a550-f06b-11ec-a6e8-cdf27550dc0d)
## 여가시간 변화와 동향 분석
### 1. 여가시간의 변화
![leisure_time_1](https://github.com/intelligence-kim/LeisureTrends/assets/128572870/ad574970-2a84-4076-b105-f5eb4aa4fa99)
  - 회색 수직 점선을 기준으로 코로나 발생 이후 사람들의 평균 여가시간은 급격히 증가한 것을 알 수 있다.
  - 이는 코로나로 인한 재택근무의 활성화, 공공시설 이용 제한에 따른 사람들의 실내 취미 생활이 증가한 것으로 추측된다.
### 2. 여가시간 동향
![leisure_category_1](https://github.com/intelligence-kim/LeisureTrends/assets/128572870/9d4423ff-be6f-4598-94e7-47ec54b1acae)
 - 코로나가 한창인 시기에는 주로 휴식/오락 위주로 여가시간을 보냈으나 코로나가 어느정도 완화되는 시기에 대인관계 형성과 취미사용이 높아진 것을 볼 수 있다.
 - 결과적으로 급격히 늘어난 여가시간이 초창기에는 주로 잉여시간으로 보내졌지만 추후 이 시간을 자기개발과 코로나 반동으로 인한 대인관계 비중이 높아졌다고 추측된다.
### 3. 여가시간 만족도
![leisure_satisfaction](https://github.com/intelligence-kim/LeisureTrends/assets/128572870/874e8d78-cc73-4a37-a875-ccec49aad423)
 - 여가시간 만족도는 시간이 지남에 따라 '만족'으로 맞춰지는 것으로 보임
 - 대체적으로 코로나 이전 여가시간 만족도는 소극적인 편이었으나 코로나로 인해서 여가시간이 증가하고, 여가시간에 따른 사용방식의 변화는 사람들에게 대체적으로 '만족'을 주었으며 이는 긍정적으로 보여진다.

## 소비자 심리 분석
### 1. 주요 키워드 분석
#### 2030/4050의 소비 키워드 비교
![2030](https://github.com/intelligence-kim/LeisureTrends/assets/128572870/4922ef50-573e-4dd2-b54c-d7ef1e165710)
![4050](https://github.com/intelligence-kim/LeisureTrends/assets/128572870/813bd2f2-a8d5-442e-86fe-74a43ee5901c)
 - 2030은 주로 스트레스 해소/자기만족이 가장 큰 키워드였지만 4050은 상대적으로 높은 가치를 두지는 않았다.
#### 4050의 가장 높은 키워드
![4050_2](https://github.com/intelligence-kim/LeisureTrends/assets/128572870/f715fd2f-90af-4c0d-9e83-d14451aaecaa)
 - 오히려 4050은 사회적 교류를 가장 높은 가치로 두었다.
### 2030 키워드의 다양한 분석적 접근
#### 네트워크 시각화
![net](https://github.com/intelligence-kim/LeisureTrends/assets/128572870/5e0d0c3c-4530-40d9-b167-e8f97bb1de5e)
#### 토픽 모델링
![net](https://github.com/intelligence-kim/LeisureTrends/assets/128572870/de9582c4-e88d-47ee-8a36-9958c9ccc1e4)
 - 2030의 스트레스 해소/자기만족의 키워드는 코로나로인한 다양한 온라인 플랫폼의 등장으로 새로운 소비자로 급부상한 것으로 보임
 - 이러한 결과는 2030세대는 코로나를 겪으면서 전적으로 자신에게 집중한 결과를 초래한 것으로 보임

## 2030은 '나'에게로 4050+은 '너'에게로
 - 코로나 이후 사람들의 평균 여가시간은 증가했으며 그에따라 취미/여가에 투자하는 시간이 많아졌다.
 - 2030은 주로 남는 여가시간을 자신을 위주로 보냈으며 4050+은 코로나로인한 관계의 단절을 회복하려는 모습을 보였다.
 - 최종적으로 2030은 떠오르는 소비자로 나타났으며 이는 실제로 기업들에게 큰 변화가 생길 것을 알 수 있다.





