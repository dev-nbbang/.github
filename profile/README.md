## 🚀 엔빵! 1/N로 나눠보자!
<p align="center">
  <img width="200" alt="nbbang-logo" src="https://user-images.githubusercontent.com/52314663/181794851-8ce364da-07eb-4ba2-bdc5-4d450d24642b.png">
</p>

## 🐾 프로젝트 개요

나날이 갈수록 OTT 플랫폼 서비스는 가격이 증가하고 있습니다. 

일반적으로 OTT 서비스는 하나의 계정으로 여러명이 함께 사용할 수 있는 패밀리 서비스를 함께 제공합니다.

사용자들은 패밀리 서비스를 이용해 이용자를 구하고 가격을 나눠내면서 사용하지만 OTT 플랫폼 서비스가 출시된 지 오래된 현재에는 OTT 서비스에 가입 안된 사용자를 구하는 것이 어렵습니다. 

**“엔빵**"은 **“OTT 서비스의 계정을 함께 공유할 이용자들을 편리하게 모집하고 안전하게 함께 이용하면 좋겠다"라는 관점에서 진행하게 된  프로젝트** 입니다.

## 👥 팀원

|            [맹준영](https://github.com/jymaeng95)             |            [김현홍](https://github.com/kimho1995)             |             [최지환](https://github.com/gingaminga)             |  
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: 
| <img src="https://avatars.githubusercontent.com/u/52314663?v=4" width=200px alt="_"/> | <img src="https://avatars.githubusercontent.com/u/53163565?v=4" width=200px alt="_"/> | <img src="https://avatars.githubusercontent.com/u/60294629?v=4" width=200px alt="_"/> | 
|                         🫥 백엔드                         |                         💻 백엔드                         |                           🌈 프론트엔드                           |

## 📅 프로젝트 기간
Back-End : 2022-04 ~ 2022-07(3개월)
<br>
Front-End : 2022-04 ~ -ing


## 🏗 시스템 아키텍처
<p align="center">
  <img width="70%" alt="system-architecture" src="https://user-images.githubusercontent.com/52314663/181794798-d9279c66-9211-4128-aee3-431428d58017.png">
</p>

## 🏢 ERD
<p align="center">
  <img width="70%" alt="erd" src="https://user-images.githubusercontent.com/52314663/182320220-0b3b2eca-dbb0-4556-80ac-9ffe779f2891.png">
</p>

## ✨ 핵심 기술

- **Micro Service Architecture (MSA)** 를 이용한 각 서비스간 의존성 감소
- **Spring Cloud Gateway를 이용한 각 마이크로 서비스 라우팅 및 JWT 토큰 검증**
- **RabbitMQ**를 이용한 **Event-Driven-Architecture (EDA) 구축**
- **Spring Cloud Config Server와 RabbitMQ를 이용한 각 마이크로 서비스 별 구성정보 중앙 집중화**

## 🔥 Skills
### Back-End
<p>
  <img src="https://user-images.githubusercontent.com/52314663/181797789-400fe7fa-ab82-4049-949d-275c32b64588.png" alt="spring_boot" width=13.3%>
  <img src="https://user-images.githubusercontent.com/52314663/181797125-18396b1f-bcdf-4b8d-9a74-b2f56407eeb3.png" alt="mysql" width=13.3%>
  <img src="https://user-images.githubusercontent.com/52314663/181797147-b857bf1a-2d3f-4a3e-9760-204d80fe81fb.png" alt="redis" width=13.3%>
  <img src="https://user-images.githubusercontent.com/52314663/181797166-94a02034-913a-48d5-88fa-84b3c942fdce.png" alt="hibernate" width=13.3%>
  <img src="https://user-images.githubusercontent.com/52314663/181797807-21928a4d-a83e-429c-8730-19891128cdde.png" alt="spring_cloud" width=13.3%>
  <img src="https://user-images.githubusercontent.com/52314663/181797216-cd90d9f0-5154-41a7-bcad-e80881a869de.png" alt="Github" width=13.3%>
  <img src="https://user-images.githubusercontent.com/52314663/181797242-1e299f4f-3254-43fb-ab96-c6aac4888ce6.png" alt="rabbitMQ" width=13.2%>
</p>

- **Spring Boot**를 이용하여 **각 마이크로 서비스의 웹 서버 애플리케이션을 구현**했습니다.
- **MySQL**을 이용하고 **DB 내 데이터를 Spring Data JPA, Hibernate를 이용해 객체 지향적인 데이터 로직을 작성**했습니다.
- **Redis**를 이용해 **JWT의 토큰을 관리**했습니다.
- **Spring Cloud Gateway와 Spring Cloud Eureka** 이용해 **각 마이크로 서비스의 라우팅을 구현**했습니다.
- **GitHub의 원격 레포지토리에 각 마이크로 서비스의 환경 설정 정보를 격리**하고, **Spring Cloud Config Server와 RabbitMQ를 이용해 변경사항에 대해서 중앙 집중식 환경 설정 관리를 구현**했습니다.
- **RabbitMQ**를 이용해 **마이크로 서비스 내 EDD(Evend Driven Develop)를 구현**했습니다.

---

### Infrastructure
<p>
  <img src="https://user-images.githubusercontent.com/52314663/181800139-ba8ef08a-9ac6-4d26-93de-bf057d1b48fb.png" alt="OCI" width=24%>
  <img src="https://user-images.githubusercontent.com/52314663/181800102-5e84d48b-ec9f-42e1-9a3d-eb5475ae729c.png" alt="docker" width=24%>
  <img src="https://user-images.githubusercontent.com/52314663/181797216-cd90d9f0-5154-41a7-bcad-e80881a869de.png" alt="Github" width=24%>
  <img src="https://user-images.githubusercontent.com/52314663/181800167-72a02cf4-8f54-4a5d-9fcd-fdeaac4aeb82.png" alt="jenkins" width=24%>
</p>

- **Oracle Cloud Infrastructure**와 **Docker**를 이용해 **서버를 구축**했습니다.
- **Github 레포지토리**의 특정 조건에 **WebHook을 발생**시켜 **Jenkins를 이용해 배포 자동화를 구축**했습니다.


## 📋 기능 요약

- **인증 :** RestAPI를 이용한 구글 및 카카오 소셜 로그인 및 JWT를 이용한 인증 구현

- **회원** : 사용자 정보 조회, 포인트 적립/사용 및 쿠폰 서비스 구현

- **파티** :  OTT 서비스 파티 자동 매칭 및 일반 매칭, 아임포트 API를 이용한 결제 시스템 구축, 구성된 파티 정보 내 QNA 관리 구현

- **알림** : 회원, 파티 서비스로부터 발생하는 이벤트 처리 구현, 공지사항 및 이벤트 등록 시 사용자 전체 알림 저장 구현
