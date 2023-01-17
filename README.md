# OSSP_2023
2023년도 동계 계절학기 [44740] 오픈소스SW프로젝트 과목 
## 제목
Car_Damage_Area_Segmentation
## 주제 
Unet을 기반으로 한 차량의 손상 이미지를 보고 파손 영역 크기를 계산해주는 인공지능
## 목표
차량 손상을 4가지 
- Scratch : 스크래치
- Seperated : 이격
- Crushed : 찌그러짐
- Breakage : 파손
로 분류해 각 파손 종류별 영역 크기를 계산한다.
### 사용한 사전 학습 모델 및 데이터
- 쏘카제공 사전 학습 모델 : https://drive.google.com/drive/folders/1q0l5vT14Kka_iu0WZgn1EFJLUbWD8EtY?usp=sharing
- 데이터셋 : 차량 파손 이미지 - AI허브 https://www.aihub.or.kr/aihubdata/data/view.do?dataSetSn=581
## 소스코드 출처
- https://github.com/kairess/car-damage-segmentation
- 유튜브 차량 수리비 산출을 위한 차량파손 이미지 데이터-한국전기차리빌딩협회-인공지능 학습용 데이터 교육 영상(2021 2차) https://youtu.be/vkKeu3kRr2U
- 유튜브 [AI-Hub X 빵형의 개발도상국] 차량 파손 수리 견적 뽑아주는 AI https://youtu.be/2TmjBz7teUs
- 도움 : 한국지능정보사회진흥원 , 쏘카