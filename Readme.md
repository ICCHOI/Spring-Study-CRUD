Spring MVC - CRUD 예제
===

> 스프링 MVC를 사용한 CRUD 예제를 통해 HTTP의 작동방법을 이해하고, URL을 사용한 웹 프로그래밍에 대해 이해하는 것을 목표로 합니다.

Projcet 설계
---

* CRUD 학생명단 만들기
    * 학생 정보는 추가 가능 해야 합니다 (Create)
    * 등록된 모든 학생 정보는 출력 될 수 있어야 합니다.. (Read) ~~Remove~~
    * 개별 학생정보를 수정 할 수 있어야 합니다. (Update)
    * 개별 학생정보는 삭제 할 수 있어야 합니다. (Delete) 

개발환경
---
| Tool | Version |
| :---: | :---: |
| Build Tool | Gradle |
| Web Framework | Spring boot 2.2.6 |
| Database | H2 Database |
| IDE | IntelliJ IDEA |
| OS | Window 10 |
| Java version | JDK 8 >= |
| Template Engine | Thymeleaf | 
| Dependency | Spring Data JPA |

개발 순서
---
<details>

1. Spring Boot Application 생성

2. Project 구조 확인

3. Dependencies 확인 및 추가

4. Domain 레이어 작성

5. Repository 레이어 작성

6. Controller 레이어 작성

7. View 레이어 작성

8. Execute

9. Check

10. Done!
</details>

Reference
---

<details>


[HTTP 참고자료](https://developer.mozilla.org/ko/docs/Web/HTTP)
</details>

