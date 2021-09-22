# ColabHeartFailureAnalysis
colab과 Python을 이용하여 심부전(Heart_Failure) 데이터 분석하기

<img width="464" alt="asfasfasfsvxcv" src="https://user-images.githubusercontent.com/81430564/134305914-0361cf08-d9f5-465b-a7e3-35f8386ea83f.PNG">


## 💻 기술 스택

- Jupyter Notebook
- python
- seaborn
- matplotlib
- pandas
- numpy
- StandardScaler
- XGBoost 

## ✨ 참고사항

출처 : https://www.kaggle.com/andrewmvd/heart-failure-clinical-data?select=heart_failure_clinical_records_dataset.csv

이 데이터세트에는 심부전으로 인한 사망률을 예측하는 데 사용할 수 있는 12가지 인자가 포함되어 있다.

- age : 나이
- anaemia : 빈혈 (0: 정상, 1: 빈혈)
- creatinine_phosphokinase : 크레아틴키나제(혈청cpk) 검사 수치
- diabetes : 당뇨 (0: 정상, 1: 당뇨)
- ejection_fraction : 심박출률 => 심장의 펌프기능을 나타내는 지표
- high_blood_pressure : 고혈압 (0: 정상, 1: 고혈압)
- platelets : 혈소판 수치
- serum_creatinine : 혈중 크레아틴 수치 (mg/dL)
- serum_sodium : 혈중 나트륨 수치 (mg/dL)
- sex : 성별 (0: 여성, 1: 남성)
- smoking : 흡연 여부 (0: 비흡연, 1: 흡연)
- time : 관찰 기간 (일)
- DEATH_EVENT : 사망 여부 (0: 생존, 1: 사망)

## 📄 예시

<img width="237" alt="asdasdadavxv" src="https://user-images.githubusercontent.com/81430564/134305768-0e8cafe7-1705-4084-942f-4f4962c26960.PNG">
<img width="210" alt="asdadsdsfxc" src="https://user-images.githubusercontent.com/81430564/134305708-db935c91-32ca-4716-aab2-a4b78352c015.PNG">


## 🌲 디렉토리 구조

```
├── heart_failure_clinical_records.csv
└── HeartFailureAnalysis.ipynb
``` 

## ⚙️ 주요 기능

- 그래프와 표를 활용해 데이터를 쉽게 확인할 수 있도록 구현
