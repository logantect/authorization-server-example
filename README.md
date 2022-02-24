# Building an Authorization Server with Spring Security OAuth2 Boot

Spring Security OAuth 프로젝트는 Spring Boot 1.x 버전에서 함께 제공 되었으나,  
Spring Security 5의 일급 OAuth 지원을 위해 Spring Boot 2.x에서 제거되었습니다.  
Spring Security OAuth 프로젝트를 이용하기 위해서는 직접 의존성 주입을 해줘야합니다.

사실 기존에 Spring Boot 1.x 버전을 활용하여 OAuth2.0 인증서버 구현 경험이 이미 있는데요,  
OAuth2.0 깊은 이해와 실제 동작 메커니즘을 완벽히 숙지 하지 못한 상황이다보니 운영 중 이슈가 발생했을 때 정말 힘들더라구요...

그래서! 이번 기회에 다시 한번 구축해 보면서 Auth2.0을 이해해보려고 합니다.  
그럼 한번 시작해보도록 하겠습니다! 
  




### Gradle Dependencies
```groovy
implementation 'org.springframework.security.oauth.boot:spring-security-oauth2-autoconfigure:2.6.3'
```

Reference
---
---
- https://docs.spring.io/spring-security-oauth2-boot/docs/2.6.3/reference/html5/