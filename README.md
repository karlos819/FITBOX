# 📱 FITBOX  
**2021145124 김문성**  

**FITBOX**는 심박수를 기반으로 운동 중 음악을 추천해주는 iOS 앱입니다.  
운동의 몰입도와 재미를 높이기 위한 스마트 피트니스 도우미로 설계되었습니다.

---

## 💡 주요 기능
- 실시간 심박수 측정 (HealthKit 연동)
- 유튜브 음악 자동 추천 (심박수 기반 BPM 검색)
- 운동 타이머 및 기록 확인
- 캘린더 기반 운동 이력 조회

---

## 🛠️ 개발 환경
- **Xcode** (StoryBoard 기반)
- **Swift 5**
- **Frameworks**: UIKit / MapKit / HealthKit
- **Firebase API**: 로그인, 회원가입 기능 구현
- **YouTube API**: 음악 재생 기능
- **GitHub**: 버전 관리

---

## ▶️ 실행 방법
1. 프로젝트 압축을 해제한 후 `FITBOX.xcodeproj` 파일을 Xcode로 엽니다.
2. 시뮬레이터 또는 실기기에서 실행 가능합니다.
3. **HealthKit 기능은 실기기에서만 작동**합니다.

---

## 👤 제출자
- 이름: **김문성**
- 학번: **2021145124**

---

## 📸 실행 화면

### 🔐 로그인 화면
<img src="https://github.com/user-attachments/assets/6398ad21-ccd6-4956-a577-2c66e426eccb" width="300" />
<img src="https://github.com/user-attachments/assets/6be04771-ea58-4c03-87aa-ef0937a1537a" width="300" />
<img src="https://github.com/user-attachments/assets/12c1674a-6736-4855-9cd0-981ae726dc7d" width="300" />

- 3가지 배경 이미지가 5초 간격으로 자동 전환됩니다.

### ❌ 로그인 실패 예시
<img src="https://github.com/user-attachments/assets/4ef91ccf-f788-4e40-8008-ee9f41098c8b" width="300" />

- Firebase 서버에 등록되지 않은 계정은 로그인할 수 없습니다.

---

### 📝 회원가입 화면
<img src="https://github.com/user-attachments/assets/3789be2d-76bc-4656-b7bd-f4b48c2f7449" width="300" />
<img src="https://github.com/user-attachments/assets/897db1a9-37ef-4572-8e21-2018f38f1d82" width="300" />

- 모든 필수 정보를 입력해야 회원가입이 가능하며, 기존 계정과 중복되지 않으면 가입이 완료됩니다.

---

### 🗺️ 메인 홈 화면
<img src="https://github.com/user-attachments/assets/01f9a64e-f02b-4b50-92ad-79b5398b3589" width="300" />

- 지도 기반 UI를 제공하며, 좌측 상단의 메뉴 버튼으로 다양한 운동 기능에 접근할 수 있습니다.

---

### 📂 사이드 패널 화면
<img src="https://github.com/user-attachments/assets/8b4b4d17-a0ba-4c86-a3fe-00d1b721f8d2" width="300" />
<img src="https://github.com/user-attachments/assets/985d0ac2-cbe4-435c-b4b0-b3b55a712b4c" width="300" />
<img src="https://github.com/user-attachments/assets/ad077354-1c9d-431b-bf97-6da0cd738972" width="300" />
<img src="https://github.com/user-attachments/assets/759e3834-0114-49f5-9f28-8a759d245baf" width="300" />
<img src="https://github.com/user-attachments/assets/a875d86f-a51b-49c8-9101-482a65ac75a4" width="300" />

- 사용자의 추가 생체 정보 입력
- 운동 이력 기록을 위한 달력
- 운동 팁 및 앱 정보 확인

---

### 🏃 운동 화면
<img src="https://github.com/user-attachments/assets/b565ab29-8207-4015-9c40-2dc198fcb314" width="300" />
<img src="https://github.com/user-attachments/assets/54dc21c1-f265-45c2-beb9-ad1bb314de9c" width="300" />

- 운동 시작 시 이 화면으로 전환되며,
  - 심박수에 따라 음악이 자동 재생됩니다.
  - 다음 곡, 정지 버튼으로 제어 가능
  - 운동 종료 시 홈 화면으로 복귀합니다.

---

📦 **감사합니다!**



