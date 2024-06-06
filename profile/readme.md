# ✈️ ChatToTrip

**LLM 기반 대화 콘텐츠 분석을 통한 여행 경로 작성 웹 서비스**

![image](https://github.com/TripWiz/.github/assets/83939775/25043408-c1af-478a-9c4b-91085eb97abb)

---

## 발표 자료

[![image](https://github.com/TripWiz/.github/assets/83939775/59683547-0610-413a-94ca-f6e644bd2f1d)](https://drive.google.com/file/d/1mwpWdNZHK5Jb3BdeEI__0fQfiqtpg7_H/view?usp=drive_link)

---

## 시연 영상

[![Video Label](https://img.youtube.com/vi/eUXKL51i9hw/0.jpg)](https://youtu.be/eUXKL51i9hw)

---

# :computer: 담당한 역할

- Stateless
  - SpringBoot 초기 세팅, Controller, Service, Mapper, DTO 클래스 설계
  - 컨트롤러에 대한 **API 및 MyBatis 쿼리 작성**
  - **JWT Token** Service 작성
  - **Filter**를 사용한 일부 Request Wrapping 처리
  - **Interceptor**를 통한 API 별 인가 처리
- Stateful
  - Stomp 기반 **연결 관리를 위한 NetworkService** 작성
    - 플랜 별 Room 개념 도입
    - Room 별 대화 내용을 접속 유저와 공유하여 동기화

---

# :seedling: 기술 스택

- SpringBoot + Maven
- MyBatis
- MySQL
- Swagger
- WebSocket(Stomp)
- Git

---

# :chart_with_upwards_trend: ERD

![image](https://github.com/TripWiz/.github/assets/83939775/bfb2b672-8fc8-4893-adb7-bf31b65d0cef)

---

# :chart_with_upwards_trend: 클래스 다이어그램

![image](https://github.com/TripWiz/.github/assets/83939775/7d2cbe8d-6f2d-4533-a571-b15486df594d)
