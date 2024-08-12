# 🚙 Parkro
부족한 백화점 내 주차장을 빙빙 돌면서 자리를 찾지 말고 밖, 외부 주차장으로 나가서 찾아보자는 의미

<br>

## 👋 프로젝트 소개
- 주제: 백화점 외부 주차장 위치를 안내하고, 주차 현황을 파악할 수 있는 안드로이드 앱 서비스
- 프로젝트 일정: 2024.07.30 ~ 2024.08.08

<br>

## 🚀 기획 배경
현대백화점은 고객들의 주요 불만인 협소한 주차 문제를 해결하기 위해 외부 주차장과 연계해 추가 주차공간을 마련했지만, 많은 고객이 이를 인지하지 못하고 있습니다.
외부 주차장 정보가 홈페이지에 기재되지 않고, 주차안내 판이나 안내 요원의 안내를 통해서만 확인 가능한 점을 개선하기 위해 연계 주차장 정보 제공과 사전 정산 기능을 갖춘 `🚙Parkro` 앱을 제작하게 되었습니다.

<br>

## 💡 기대 효과
&nbsp;1️⃣ 고객 방문율 증가

&emsp;: 고객들에게 편리한 주차 경험을 제공해 고객 방문율 증가
        
&nbsp;2️⃣ 주차장 관리 비용 절감

&emsp;: 주차장 안내를 위한 안내원을 따로 두는 것과 같은 관리 비용 절감
        
&nbsp;3️⃣ 간접적 매출 상승

&emsp;: 단축된 주차시간을 고객의 쇼핑 시간에 포함시킬 수 있으므로 간접적인 매출 상승 기대

<br>

## 👥 팀원 소개
|[김민정](https://github.com/serak0310)|[김지수](https://github.com/soojik)|[양재혁](https://github.com/yangjaehyuk)|
|:-------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------:|
| [<img src="https://github.com/serak0310.png" width="200">](https://github.com/serak0310) | [<img src="https://github.com/soojik.png" width="200">](https://github.com/soojik) | [<img src="https://github.com/yangjaehyuk.png" width="200">](https://github.com/yangjaehyuk) |
|주차|정산|회원|

<br>

## ⚙️ 시스템 구성도
<img src="https://github.com/user-attachments/assets/1de640d1-88c3-413c-8af9-7f4ca187875d" width = 900 />

- **Presentation Tier**: Kotlin, Android Studio
- **Application Tier**: Java 11, Springboot 2.7.17, Spring Security, lombok, MyBatis 2.3.2
- **Data Tier**: Oracle 19c

<br>

### 🤷‍♂️ 회원
> 스플래시
<img src="https://github.com/user-attachments/assets/9acf4839-cde4-41c0-8c2c-44b752fa34d5" width=320 />

> 자동로그인
<img src="https://github.com/user-attachments/assets/dcc5357b-cd9f-4a09-9bd6-1904ba9a5fa7" width=320 />

> 마이페이지 - 차량 프로필 변경
<img src="https://github.com/user-attachments/assets/338bd6de-ce54-4284-97ca-7c026627e794" width=320 />

> 로딩
<img src="https://github.com/user-attachments/assets/98637baa-8173-4f74-bd3d-faa59bfcfd90" width=320 />

<br>

### 🗺️ 지도
> 현재 유저 위치 추적
<img src="https://github.com/user-attachments/assets/4d58704e-de22-4d25-9728-2072b826b5bd" width=320 />

> 백화점 지점별 주차장 위치 표시
<img src="https://github.com/user-attachments/assets/06fd1905-d80c-472c-84a6-dd1edc13a07e" width=320 />

> 주차장 잔여 좌석 리스트
<img src="https://github.com/user-attachments/assets/e72dc164-2a7e-42cf-9db1-94d8baa85aa1" width=320 />

<br>

### 📜 주차 내역
> 나의 주차 내역
<img src="https://github.com/user-attachments/assets/00982929-7c69-41ca-9cb9-3d1bc5c23549" width=320 />

> 주차 내역 상세
<img src="https://github.com/user-attachments/assets/c0e6c1e6-78b1-47a4-ab01-7de398ec5b74" width=320 />

> 입차 알림
<img src="https://github.com/user-attachments/assets/ea8512ee-e88a-4dde-a230-df5b09cd433b" width=320 />

<br>

### 💵 정산
> 쿠폰 사용
<img src="https://github.com/user-attachments/assets/576da69d-7475-4e78-9f5d-18a71e00b5b1" width=320 />

> 영수증 등록
<img src="https://github.com/user-attachments/assets/5a1ff303-0be1-4203-a1f9-2d209ebdc843" width=320 />

> 토스페이먼츠 결제
<img src="https://github.com/user-attachments/assets/2b4d86e6-a506-40f8-9bda-7eaf760d35f5" width=320 />

> 정산 후 10분 경과 시 정산 취소 및 알림
<img src="https://github.com/user-attachments/assets/686f9bde-cef4-4509-9e59-c3e9e5010d34" width=320 />

<br>

### 🎫 쿠폰
> 쿠폰 발급
: 매월 1일 새벽 2시에 스케줄링을 통한 쿠폰 발급
<img src="" width=320 />

<br>

### 🛠️ 관리자
> 주차장별 주차 내역 - 차량 번호 및 주차장 검색
<img src="https://github.com/user-attachments/assets/e3d418d5-0b1d-4f26-ad5f-a51c16c69633" width=320 />

> 주차장별 주차 내역 - 데이트 피커
<img src="" width=320 />

> 임의 정산 처리
<img src="https://github.com/user-attachments/assets/ed174e1b-5170-4b19-b61e-05ce5fa1798d" width=320 />


