# Flight_Delay_Project
**✈️ SW전문인재양성 4기 보람삼조**   

#### 👨‍👩‍👧‍👦 Team Info
|이름|work|                    
|:---:|:---:|                                     
|<span style="color:blue">[이선오]|데이터 전처리, 데이터 EDA/시각화, 머신러닝 모델 개발/튜닝, PPT 제작|   
|<span style="color:blue">[이영빈]|데이터 전처리, 텍스트분석 모델 개발, PPT 기획, PPT 제작|   
|<span style="color:blue">[이위성]|블로그/뉴스 기사 크롤링, 데이터 전처리, 워드클라우드 제작, 딥러닝 모델|   

---

## 1. 🛫 Prediction Flight Delay 🛫         
<img src="">        

Dacon 경진대회 : **월간 데이콘 항공편 지연 예측 AI 경진대회**                    
주소 : [https://dacon.io/competitions/official/236094/overview/description](https://dacon.io/competitions/official/236094/overview/description)         

### 📜 Summary    
<img src="">      

코로나19로 주춤했던 **국제 여객 수송량**은 2022년부터 빠른 회복세를 보이고 있습니다.    
ACI(국제공항협의회)의 발표 자료에 따르면 2023년 10월 총 승객 교통량은 **전년 대비 22% 증가**하여 2019년의 95%에 도달했습니다.   
코로나 이전의 수요 증가 기대치까지 회복하기엔 시간이 필요할 것으로 예측되었으나,    
많은 공항이 승객 교통 기록을 달성하고 있습니다.       

항공을 키워드로 네이버블로그 및 뉴스 크롤링을 진행하고 워드클라우드로 나타낸 결과   
여행, 예약과 더불어 **지연**이 중요한 키워드로 나타났습니다.   

또한 관련 연구에 따르면 항공사 운송서비스 만족도가 고객 충성도에 긍정적인 영향을 미치며,   
서비스 실패에 대한 소비자의 부정적 감정반응이 높을 수록 다른 항공사로 전환하려는 의지가 강해짐을 알 수 있었습니다.    
이렇듯 **항공기 지연**은 **고객 경험에 큰 영향**을 미치는 요소입니다.      

항공기 지연은 소비자 불만뿐 아니라 항공사에도 큰 비용을 발생시킵니다.
코로나 전 2019년 미국 약 20%의 항공편이 지연을 겪었고, 이로 인해 약 **329억$의 지연 비용**이 발생했습니다.

항공 산업을 넘어 더 넓은 범위까지 영향을 미칠 수 있음

소비자, 항공사 양측 모두 고려했을 때 항공기 지연 예측이 필요하다고 판단

### 🗃 Data Info.                                            
**Dacon 항공기 지연 데이터** : [https://dacon.io/competitions/official/236094/data](https://dacon.io/competitions/official/236094/data)     
 
<img src="">            

**Data Shape**           
train (1,000,000, 19)             
test (1,000,000, 18)               

### 📊 Visualization   
**1️⃣ 주별 지연율**
