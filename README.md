## A developer passionate about learning, sharing, and building impactful software.

Yongjun Hong is a backend engineer at `NAVER WEBTOON` and an open-source contributor to `JUnit5`, `spring-projects`, `naver/fixture-monkey`, and more. He is currently a committer for `apache/seata` and has been selected as a GSoC'25 contributor for a Kotlin & Gradle project. He enjoys collaborating on projects, sharing knowledge, and continuously learning new technologies to improve his skills.

Recently, he has been particularly interested in test code. To him, test code is not just for validation. It helps other developers understand how to use his code and serves as a foundation for efficient refactoring, making it essential for maintaining high-quality software.

He is also interested in distributed transactions, especially their implementation and challenges within microservices architectures. It's a complex but fascinating area, and he has been sharing his thoughts through recent blog posts.

## Open Source Contributions
- [JUnit Framework](https://github.com/junit-team/junit5/issues?q=is%3Apr+is%3Aopen+author%3AYongGoose)
  - Introduce feature flag for auto-closing `AutoCloseable` in Jupiter's `ExtensionContext.Store` [#4452](https://github.com/junit-team/junit5/pull/4452)
  - Provide `mechanism` for managing resources across engines and executions [#4281](https://github.com/junit-team/junit5/pull/4281)
  - Implement `Parallel Method Execution` in JUnit-Vintage engine [#4242](https://github.com/junit-team/junit5/pull/4242)
  - Support `parallelization` in Junit-Vintage-engine [#4135](https://github.com/junit-team/junit5/pull/4135)
  - Implement `include` and `exclude` filtering when calling registerAutoDetectedExtensions [#4120](https://github.com/junit-team/junit5/pull/4120)
  - Add `include matching` on ClassNamePatternFilterUtils [#4115](https://github.com/junit-team/junit5/pull/4115)
- [spring-boot](https://github.com/spring-projects/spring-boot/issues?q=is%3Apr+author%3AYongGoose)
  - Add Fail fast `mechanism` when both management `base path` and `endpoint mapping` are set to `/` [#45251](https://github.com/spring-projects/spring-boot/pull/45251)
  - Ensure `DefaultErrorAttributes` adds JSON serialization safe errors [#43330](https://github.com/spring-projects/spring-boot/pull/43330)
- [spring-framework](https://github.com/spring-projects/spring-framework/issues?q=is%3Apr+is%3Aopen+author%3AYongGoose)
  - Fall back to `JDK Dynamic proxy` if `CGLIB proxy` creation fails [#35344](https://github.com/spring-projects/spring-framework/pull/35344)
  - Reject effectively `private handler methods` on `CGLIB proxied controllers` [#35352](https://github.com/spring-projects/spring-framework/pull/35352) 
- [apache-seata](https://github.com/apache/incubator-seata/issues?q=is%3Apr+is%3Aopen+author%3AYongGoose)
  - Add `ChannelEventListener` support to prevent memory leaks [#7337](https://github.com/apache/incubator-seata/pull/7337)
  - Enforce account `initialization` and disable default credentials [#7261](https://github.com/apache/incubator-seata/pull/7261)
  - Use shared `EventLoop` for TM and RM clients to reduce thread overhead and improve performance [#7179](https://github.com/apache/incubator-seata/pull/7179)
  - Implement scheduled handling for `end status` transaction [#7133](https://github.com/apache/incubator-seata/pull/7133)
- [naver/fixture-monkey](https://github.com/naver/fixture-monkey/issues?q=is%3Apr+is%3Aopen+author%3AYongGoose)
  - Implement `Random Selection` of Register Operations When Not Using selectName [#1108](https://github.com/naver/fixture-monkey/pull/1108)
  - Implement a `Matcher interface` to manage ArbitraryBuilders with a single variable [#1062](https://github.com/naver/fixture-monkey/pull/1062)
  - Add `register` and `select` ArbitraryBuilder by name [#1036](https://github.com/naver/fixture-monkey/pull/1036)
- [LG/fosslight](https://github.com/fosslight/fosslight_dependency_scanner/issues?q=is%3Apr+author%3AYongGoose)
  - Refactor existing `tox test` to pytest [#225](https://github.com/fosslight/fosslight_dependency_scanner/pull/225)
  - Change `SCANOSS Invocation Method` from Command Line to Library Function [#178](https://github.com/fosslight/fosslight_source_scanner/pull/178)
 
## Recent blog posts
- [Centralized POM Configuration Management with kotlin-pom-gradle](https://dev.to/gradle-community/centralized-pom-configuration-management-with-kotlin-pom-gradle-1kap)
- [Spring 관점에서 보는 Seata의 내부 통신](https://solution-is-here.tistory.com/236)
- [Apache Seata란?](https://solution-is-here.tistory.com/235)
- [내가 JUnit5에 글로벌 Extension 필터링 기능을 추가한 이야기](https://solution-is-here.tistory.com/233)
- [내가 JUnit5에 병렬화를 도입한 이야기 - 메서드 단위](https://solution-is-here.tistory.com/231)
- [내가 JUnit5에 병렬화를 도입한 이야기 - 클래스 단위](https://solution-is-here.tistory.com/230)

## Recent Linkedin posts
- [내 블로그가 코틀린 공식 블로그에?](https://www.linkedin.com/posts/yongjunh_gsoc-googlesummerofcode-kotlin-activity-7396529892110188544-rt83?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEdFti4BPwqNFACvr6oVR_xL4IxZGLBhfNo)
- [Spring Framework에 기여한 이야기](https://www.linkedin.com/posts/yongjunh_reject-effectively-private-handler-methods-activity-7382958948506718208-Rbtn?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEdFti4BPwqNFACvr6oVR_xL4IxZGLBhfNo)

## Contact
- yongjunh@apache.org
- [Let's have a virtual coffee ☕](https://calendly.com/dev-yongjunh)
