# Flight_Delay_Project
**✨ SW전문인재양성 4기 보람삼조 ✨**   

---

## ✈️ Prediction Flight Delay         
![화면 캡처 2024-06-24 180051](https://github.com/seonseono/Flight_Delay_Project/assets/115915544/e8fd9252-5933-49c2-9e85-8c13ad8c9e7a)    

Dacon 경진대회 : **월간 데이콘 항공편 지연 예측 AI 경진대회**                    
주소 : [https://dacon.io/competitions/official/236094/overview/description](https://dacon.io/competitions/official/236094/overview/description)    

### 🙌 Team Info
|이름|work|                    
|:---:|:---:|                                   
|<span style="color:blue">이선오|데이터 전처리, 데이터 EDA/시각화, 머신러닝 모델 개발/튜닝, PPT 제작|   
|<span style="color:blue">이영빈|데이터 전처리, 텍스트분석 모델 개발, PPT 기획, PPT 제작|   
|<span style="color:blue">이위성|블로그/뉴스 기사 크롤링, 데이터 전처리, 워드클라우드 제작, 딥러닝 모델|       

<br/><br/>
## 📑 Summary          

코로나19로 주춤했던 **국제 여객 수송량**은 2022년부터 빠른 회복세를 보이고 있습니다.    
국제공항협의회의 발표에 따르면 2023년 10월 총 승객 교통량은 **전년 대비 22% 증가**하여 2019년의 95%에 도달했습니다.   
코로나 이전의 기대치까지 회복하기엔 시간이 필요할 것으로 예측했으나, 많은 공항이 승객 교통 기록을 달성하고 있습니다.       

![표지-003](https://github.com/seonseono/Flight_Delay_Project/assets/115915544/3a94b9c4-0d15-48d3-9f63-22716a0c6ffe)
항공을 키워드로 네이버블로그 및 뉴스 2,000건을 크롤링하고 워드클라우드로 나타낸 결과   
여행, 예약과 더불어 **지연**이 중요한 키워드로 나타났습니다.   
관련 연구에 따르면 항공사 운송서비스 만족도는 고객 충성도에 긍정적인 영향을 미치고,   
서비스 실패에 대한 소비자의 부정적 감정 반응이 높을 수록 이용 항공사 전환 의지가 강해집니다.    

이렇듯 **항공기 지연**은 **고객 경험에 큰 영향**을 미치는 요소로, 항공기 지연은 소비자 불만뿐 아니라 항공사에도 많은 비용을 발생시킵니다.     
코로나 이전인 2019년 미국의 약 20%의 항공편이 지연을 겪었고, 이로 인해 약 **329억$의 지연 비용**이 발생했습니다.     

항공기 지연은 항공 산업을 넘어 더 넓은 범위까지 영향을 미칠 수 있고    
소비자, 항공사 양측 모두 고려했을 때 항공기 지연 예측이 필요하다고 판단해 프로젝트를 진행했습니다. 
<br/><br/>
## 🗃 Data Info                                            
**Dacon 항공기 지연 데이터** : [https://dacon.io/competitions/official/236094/data](https://dacon.io/competitions/official/236094/data)     
**Data Shape**           
train (1,000,000, 19)             
test (1,000,000, 18)               
<br/><br/>
## 📊 Visualization   
### 1️⃣ 미국 주별 지연율   
![화면 캡처 2024-06-24 182428](https://github.com/seonseono/Flight_Delay_Project/assets/115915544/b7d88f19-131a-4a17-9c8f-04f17d16a7c3) 
<br/>
데이터 EDA를 통해 미국 주별 지연 정도를 파악했고, 워싱턴, 뉴욕, 캘리포니아, 플로리다 네 곳이 특히 지연율이 높음을 확인했습니다.    
그 중 플로리다는 미국 내 인구수 3위, 미국 내에서 허리케인이 가장 자주 발생하는 지역으로   
연결 항공기의 지연 도착과 더불어 날씨는 미국 항공기 지연에 큰 영향을 미치는 요소입니다.
<br/>
2022년 미국 항공편 결항의 절반 이상이 기상이변으로 인해 발생했고,       
지연 예측을 통해 시기별 비즈니스 모델 개발까지 기대 가능합니다.    
<br/>
### 2️⃣ 계절 별 항공기 이용 / 지연 횟수  
![season](https://github.com/seonseono/Flight_Delay_Project/assets/115915544/9008ea64-5ccc-42d8-b057-678f83b4d873)
<br/>
