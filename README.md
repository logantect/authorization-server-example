# Building an Authorization Server with Spring Security OAuth2 Boot

Spring Security OAuth 프로젝트는 Spring Boot 1.x 버전에서 함께 제공 되었으나,
Spring Security 5의 일급 OAuth 지원을 위해 Spring Boot 2.x에서 제거되었습니다.
그래서 해당 프로젝트를 직접 의존성 주입을 해줘야 사용가능합니다.

사실 기존에 Spring Boot 1.x 버전을 활용하여 OAuth2.0 인증서버를 구현했었는데, 그때는 개념을 이해하고 사용했다기보다 ~~(다들 아시겠지만 일정이 급하다보니)~~ 구글링을 통해서 어떻게든 구현을 했었는데요, OAuth2.0 이해와 실제 동작 메커니즘을 완벽히 숙지 하지 못한 상황에서 운영 중 이슈가 발생했을 때 정말 힘들더라구요...

그래서! 이번 기회에 다시 한번 구축해 보면서 Auth2.0을 이해해보려고 합니다.  
그럼 한번 시작해보도록 하겠습니다. 
  




### Gradle Dependencies
```groovy
implementation 'org.springframework.security.oauth.boot:spring-security-oauth2-autoconfigure:2.6.3'
```

Reference
---
---
- https://docs.spring.io/spring-security-oauth2-boot/docs/2.6.3/reference/html5/