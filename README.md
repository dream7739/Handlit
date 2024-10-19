# Handlit
수습 운전자를 위한 운전 시뮬레이션 앱

|지도|운전 경로|경로 추천|비디오|
|--------|-----|------------|------------|
|<img width = "200" src = "https://github.com/user-attachments/assets/d766d7a2-5709-486e-8522-f23c5738ffcb">|<img width = "200" src = "https://github.com/user-attachments/assets/f40388ff-40a9-45e0-9bba-3141b2e29e86">|<img width = "200" src = "https://github.com/user-attachments/assets/27a63a70-aecb-4c4e-8e09-0c02a043f853">|<img width = "200" src = "https://github.com/user-attachments/assets/d34a418f-71e0-4de2-b513-286d9149f1a6">|

## 프로젝트 환경
- 인원: iOS 2인, 서버 1인, 디자인 1인, 기획 1인
- 기간: 2021.05.21 - 2021.05.23
- 최소버전: iOS 14+ 

## 기술 스택
- UI: UIKit, Storyboard 
- Location: MapKit, CLLocation
- Video: AVFoundation
  
## 핵심 기능
- 지도: 현위치 표시 및 출발지, 도착지 검색
- 운전 경로: 추천 경로, 최단 경로, 최장 경로 제공
- 비디오: 경로 안내 비디오 재생
  
## 주요 기술 및 담당 업무
- AVFoundation을 사용한 비디오 출력
- MapKit을 통한 경로 표시 및 커스텀 MKAnnotationView 사용
- CoreLocation을 통한 사용자 권한 처리 및 현재 위치 출력