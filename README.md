# Ansible을 활용한 네트워크/보안장비 자동 백업시스템 구축
## 개요
네트워크/보안 장비 운영 중 장애 발생 시 백업 시스템을 활용하여 신속 복구

## 구성도
![ansible1](https://user-images.githubusercontent.com/61907361/147812095-53dd55f4-9d22-4953-9992-ae7572260cba.JPG)

## 기대효과
1. 방화벽/스위치 장애 발생시 백업 파일을 활용하여 신속 복구
2. 스위치설정 전사 변경시 일괄작업 가능하여 작업 소요시간 감소

## 결과
1. 매일 자정 스케줄 백업, 백업 데이터 1주일치 보관
1. 각시스템 날짜 및 호스트명별 폴더및 파일 생성  
![ansible_backup](https://user-images.githubusercontent.com/61907361/147813379-42dbc5e9-9f4b-43ae-aff3-8da500816e80.JPG)
![ansible_config](https://user-images.githubusercontent.com/61907361/147813388-e2524c49-2d32-40d5-9bbd-31fa6f9b7f84.JPG)
