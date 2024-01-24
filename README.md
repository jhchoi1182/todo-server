## 🗺프로젝트 아키텍처

![image](https://github.com/jhchoi1182/next-todo/assets/116577489/c959ef3f-656d-4d22-b713-34fcf3006a44)

## 🎉소개

스프링 부트를 이용해 개발한 게시판 API
<br>
<br>
프론트엔드 코드 : https://github.com/jhchoi1182/next-todo

<br>

## ✨특징
* User, Todo, Comment 모델의 데이터 테이블 생성
* 불필요한 쿼리 요청 최적화
  * Todo 삭제 시 @Modifying 및 @Query 어노테이션을 활용하여 Comment 삭제에 대한 **쿼리 요청을 단일화하여 데이터 처리 효율성 증대와 서버 부하 감소**
  * API 요청 처리 시, Spring Securiy의 인증 절차 외 추가적인 사용자 인증 절차를 제거하여 **API 응답 시간 단축 및 쿼리 최적화**
* **AWS EC2, Docker Compose를 이용해 배포**하여 배포 과정의 일관성 및 재현성 보장
* **Github Actions를 통한 CI/CD 프로세스 구축**으로 개발 편의성 개선 및 배포 속도 향상
* **Nginx를 활용하여 외부 서버에서 HTTPS 프로토콜을 구성**하고 구현, 사용자 데이터 보호 및 통신 보안 강화
* Jwt 토큰을 사용해 사용자 인증 정보의 보안성 및 접근 제어 메커니즘 강화

<br>
