# Waste-Classification-Project

## 문제 정의
- 매년 전 세계적으로 약 20억톤의 쓰레기 발생, 이중 1/3 이상이 적절하게 처리되지 못하고 있음 (세계은행, 2018) <br>
![선정 배경](https://user-images.githubusercontent.com/44628138/216820186-089d11f0-a697-43a6-aeb5-01527a1a5e59.PNG)
- 생활수준 향상 등으로 전세계 쓰레기 배출양은 앞으로도 늘어날 것으로 예상<br>
- 기존 대표적인 쓰레기 처리 방식인 매립, 소각은 환경오염의 주범이자 다양한 기상이변과 발암물질의 발생 원인으로 손꼽힘<br>
- 산업 발전에 따라 늘어나는 종류별 쓰레기 배출량은 점점 감당하기 어려워지는 가운데, 자동화된 배출 쓰레기 분류 시스템 구축으로 보다 효율적이고 정확, 안전한 쓰레기 분류 및 관리 가능성에 주목<br>

## 프로젝트 목적 & 데이터 선정 이유
![프로젝트 소개](https://user-images.githubusercontent.com/44628138/216820619-03a582e3-975d-4b93-848e-4cbed5f2fa8b.PNG)

## 가설 설정
- 배출하려는 쓰레기가 음식물인지 재활용 쓰레기인지 파악할 수 있다.<br>
- 재활용 쓰레기를 플라스틱, 캔, 종이류 등 세분화하여 분류해낼 수 있다. (여건상 검증 불가)<br>

## 이미지 처리
- 데이터 처리 과정에서 ImageDataGenerator 기능을 통해 데이터셋 내의 기존 폴더 구분에 맞추어 데이터 가져온 후 전처리 및 검증 데이터 분리 진행<br>
- [Keras의 pre-trained model인 ResNet50 모델 선정](https://github.com/aurorave/Waste-Classification-Project/blob/main/2.%20AI_14_%EB%B0%95%EC%84%B1%ED%9D%AC(.ipynb).ipynb)<br>
- 이미지넷 훈련 모델(가중치) 활용<br>

## 모델 검정
![모델 검정](https://user-images.githubusercontent.com/44628138/216820696-b5249a62-f655-4b35-bdc5-a52f39b7a8ac.PNG)
