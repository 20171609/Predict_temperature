## project
- 기상 데이터를 이용하여 다음날의 한파와 폭염을 예측하기
- 폭염 
    1. 일 **최고 체감온도가 33℃ 이상**인 경우
       
- 한파 
    1. 아침 최저기온이 **전날보다 15℃ 이상 하강하여 3℃ 이하이고 평년값보다 3℃가 낮을 것으로 예상**될 때
    2. 아침 최저기온이 **-15℃ 이하가 2일 이상 지속될 것이 예상**될 때


## Model Architecture
### Summer Model
![image](https://github.com/20171609/Predict_temperature/assets/28584277/1544cdee-0d4e-44ad-a640-80a540a5e860)

### Winter Model
![image](https://github.com/20171609/Predict_temperature/assets/28584277/3506f3af-c594-401b-a87b-19c424e74866)

## 성능
### Summer (폭염)

![image](https://github.com/20171609/Predict_temperature/assets/28584277/156faebe-ffb3-4e52-b084-4043ac44fab6)
Precision : 0.73
Recall : 0.74
F1-Score : 0.72

### Winter (한파)

![image](https://github.com/20171609/Predict_temperature/assets/28584277/b022008c-0b53-4a64-821b-78a9ce35a7b9)
Precision : 0.03125
Recall : 0.03333
F1-Score : 0.03225

## 원인 분석
![image](https://github.com/20171609/Predict_temperature/assets/28584277/1aae32e2-78fe-4361-83a7-1e587e74a90d)


![image](https://github.com/20171609/Predict_temperature/assets/28584277/8e6b01c4-6d2a-472a-9d5c-92e305630557)

