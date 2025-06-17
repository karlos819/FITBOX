# FITBOX 2021145124 김문성
**FITBOX**는 심박수를 기반으로 운동 중에 음악을 추천해주는 IOS앱 입니다.
운동 중 몰입도와 재미를 높이기 위한 피트니스 도우미 앱으로 설계 되었습니다

---
## 주요 기능
-심박수 실시간 측정(HealthKit 연동)
-유튜브 음악 자동 추천(심박수 기반 BPM검색)
-운동 타이머, 기록 확인
-캘린더를 통한 운동 이력 조회

---
## 개발 환경
-Xcode (StoryBoard 기반)
-Swift 5
-UIKIT/ MAPKIT/ HealthKit
-Firebase API(로그인, 회원가입 구현)
-Youtube API(음악 재생)
-GitHub를 이용한 버전 관리
---
## 실행 방법
1. 프로젝트 압축을 해제한 후 'FITBOX.xcodeproj'파일을 xcode로 열어주세요
2. 'Simulator'또는 실기기로 실행가능 합니다.
3. HealthKit은 실제 기기에서만 작동합니다.

---
## 제출자 
- 이름: **김문성**
- 학번: 2021145124

---
## 실행화면
![1](https://github.com/user-attachments/assets/6398ad21-ccd6-4956-a577-2c66e426eccb)
![2](https://github.com/user-attachments/assets/6be04771-ea58-4c03-87aa-ef0937a1537a)
![3](https://github.com/user-attachments/assets/12c1674a-6736-4855-9cd0-981ae726dc7d)

-로그인 화면입니다 
3가지의 화면이 5초 간격으로 변화하게 만들었습니다.
----
![13](https://github.com/user-attachments/assets/4ef91ccf-f788-4e40-8008-ee9f41098c8b)

-파이어 베이스 서버에 등록되지 않은 계정으로
로그인을 하려하면 이렇게 로그인이 불가능합니다

----
![4](https://github.com/user-attachments/assets/3789be2d-76bc-4656-b7bd-f4b48c2f7449)
![5](https://github.com/user-attachments/assets/897db1a9-37ef-4572-8e21-2018f38f1d82)

-회원가입 화면입니다
모든 정보를 입력하디 않으면 회원가입이 되지않고
정보를 다 입력하고 기존 회원과 중복이 
되지 않으면 가입이 완료 됩니다
----

![6](https://github.com/user-attachments/assets/01f9a64e-f02b-4b50-92ad-79b5398b3589)

-메인 홈 화면입니다
운동 어플이기때문에 메인화면에 지도를 넣어 두었고
메뉴 버튼을 누르면  
운동에 도움이 되는 기능들을 이용할수 있습니다.
----
![7](https://github.com/user-attachments/assets/8b4b4d17-a0ba-4c86-a3fe-00d1b721f8d2)
![8](https://github.com/user-attachments/assets/985d0ac2-cbe4-435c-b4b0-b3b55a712b4c)
![9](https://github.com/user-attachments/assets/ad077354-1c9d-431b-bf97-6da0cd738972)
![10](https://github.com/user-attachments/assets/759e3834-0114-49f5-9f28-8a759d245baf)
![11](https://github.com/user-attachments/assets/a875d86f-a51b-49c8-9101-482a65ac75a4)

- 사이드 패널 화면입니다
- 사용자의 추가적인 생체정보를 작성하는 페이지
- 운동한 날짜를 달력에 기록 가능한 페이지
- 운동에 도움이 되는 조언을 주는 페이지
- 앱의 정보가 나오는 페이지로 구성 되어 있습니다.
----

![12](https://github.com/user-attachments/assets/b565ab29-8207-4015-9c40-2dc198fcb314)
![14](https://github.com/user-attachments/assets/54dc21c1-f265-45c2-beb9-ad1bb314de9c)

- 운동 화면입니다
홈화면에서 운동 시작 버튼을 누르면
이 화면으로 전환되고
심박수를 기반으로 음악이 나오며
다른 노래로 전환하거나, 노래를 멈출수 있고
중지 버튼으로 홈 화면으로 돌아갈수 있습니다.



