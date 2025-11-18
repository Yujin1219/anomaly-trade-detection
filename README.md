# 📈 이상 거래 탐지 (EDA) 프로젝트
## 💹 연구 배경
암호화폐 무기한 선물 거래소에서는 **보너스 지급, 펀딩피 제도 등 인센티브를 악용하는 사례가 증가**하며 시장 건전성을 위협하고 있다. 자동화 스크립트, 다중 계정을 통한 이상 거래는 일반 투자자에게 불공정한 환경을 조성하고 거래소 비용을 증가시킨다. 
본 연구는 **실제 거래 데이터를 기반으로 세 가지 주요 이상 거래 패턴을 탐지하고, 그 행동 특성과 경제적 동기를 분석**한다.
## 🌟 이상 거래 패턴 정의
### 패턴 1: 보너스 악용형 패턴
보너스를 짧은 시간 안에 반복적으로 수령하고, 해당 보너스를 활용하여 즉시 거래를 수행함으로써 보너스를 사실상 현금(증거금)처럼 사용하는 행위

<img width="844" height="476" alt="image" src="https://github.com/user-attachments/assets/5591de16-a93e-49f1-9348-8c29360e7da1" />
<img width="844" height="476" alt="image" src="https://github.com/user-attachments/assets/271dc5a3-560b-45af-81eb-aa88843fd644" />
<img width="844" height="476" alt="image" src="https://github.com/user-attachments/assets/0c434a47-a00a-4771-a57b-5071dc2230a9" />


### 패턴 2: Funding fee 차익거래형
펀딩피 발생 시점을 노려 포지션을 조작하여 펀딩피 수익을 극대화하는 행위

<img width="844" height="476" alt="image" src="https://github.com/user-attachments/assets/0e49b33d-8c7d-4ce3-b37a-c9aacbc5db5f" />
<img width="844" height="476" alt="image" src="https://github.com/user-attachments/assets/3d21260d-9d17-4d78-b052-bdf779794acd" />


### 패턴 3: 다중 계정 조작형
연관된 다수 계정이 협력하여 인위적으로 거래량을 늘리거나 가격을 조작하는 행위

<img width="844" height="476" alt="image" src="https://github.com/user-attachments/assets/3694b4d9-a3c1-4829-b972-6e0e02598cb5" />
<img width="844" height="476" alt="image" src="https://github.com/user-attachments/assets/3bfb42e2-205f-4af1-8c2c-70b7c6edc33a" />

## 📊 분석 결과
### 패턴 1: 보너스 악용형 패턴
<img width="844" height="476" alt="image" src="https://github.com/user-attachments/assets/0c71888d-5be8-4791-ab1a-19f2238a79ba" />

### 패턴 2: Funding fee 차익거래형
<img width="844" height="476" alt="image" src="https://github.com/user-attachments/assets/5c745c71-d138-467b-900c-1330e25ef687" />

### 패턴 3: 다중 계정 조작형
<img width="844" height="476" alt="image" src="https://github.com/user-attachments/assets/09c9dd4a-bd3d-4c09-834a-1994b67ea243" />

