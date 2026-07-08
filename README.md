# Anomaly Image Detection Project
### 딥러닝 기반 이상치 탐지 및 MES 연동 시스템

## 프로젝트 목적

## 아키텍쳐

## 기술 스텍
- C# WPF / OpenCvSharp
- Java Spring Boot
- Vue.js
- SQLite
- Docker Compose

## 주요 기능
- 딥러닝 기반 이미지 이상치 탐지
- MES 대시 보드

## 실행 방법
docker-compose up

## 스크린샷
- Auto Mode: RS232 신호를 받아 촬영 후 추론을 시작한 후 결과를 DB에 저장
- Model Creation: 검사 방식, Network, 훈련 데이터, 테스트 데이터, 훈련 파라미터 선택 후 Weight를 생성 후 각종 데이터를 json 형태로 저장
- Model Management: 모델 리스트 출력 후 수정 및 삭제
- Model Selection: 모델에 대한 json 파일 리스트를 출력 후 선택
- Inspection
- Settings: 밝기 감도 GPU 설정
- Calibration: Calibration Board를 이용한 이미지 수정
