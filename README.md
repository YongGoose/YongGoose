## Somewhere between AI and the JVM

I'm Yongjun Hong, a committer for Apache Seata and a backend engineer at NAVER WEBTOON.

In JUnit I added parallel execution to the Vintage engine, and I've made a few changes to Spring Boot and Spring Framework. I was also a GSoC '25 contributor for the Kotlin & Gradle project, and I maintain the Batch Control plugin for Jenkins.

I write about some of these on my blog. Lately I've been building AI tools for developers.

## Open Source Contributions
- **Apache Seata**: committer, [23 merged PRs](https://github.com/apache/incubator-seata/pulls?q=is%3Apr+is%3Amerged+author%3AYongGoose)
  - Use a shared `EventLoop` for TM and RM clients to reduce thread overhead [#7179](https://github.com/apache/incubator-seata/pull/7179)
  - Enforce account initialization and disable default credentials [#7261](https://github.com/apache/incubator-seata/pull/7261)
- **JUnit**: [7 merged PRs](https://github.com/junit-team/junit-framework/pulls?q=is%3Apr+is%3Amerged+author%3AYongGoose)
  - Parallel class and method execution in the JUnit Vintage engine [#4135](https://github.com/junit-team/junit-framework/pull/4135), [#4242](https://github.com/junit-team/junit-framework/pull/4242)
  - Provide a mechanism for managing resources across engines and executions [#4281](https://github.com/junit-team/junit-framework/pull/4281)
- **Spring Boot**: [2 merged PRs](https://github.com/spring-projects/spring-boot/commits?author=YongGoose)
  - Fail fast when both the management base path and an endpoint mapping are set to `/` [#45251](https://github.com/spring-projects/spring-boot/pull/45251)
- **Spring Framework**
  - Reject effectively private handler methods on CGLIB-proxied controllers [#35352](https://github.com/spring-projects/spring-framework/pull/35352)
- **LangChain4j**: [3 merged PRs](https://github.com/langchain4j/langchain4j/pulls?q=is%3Apr+is%3Amerged+author%3AYongGoose)
  - `PgVectorEmbeddingStore` supports full-text and hybrid search [#4288](https://github.com/langchain4j/langchain4j/pull/4288)
- **Fixture Monkey**: [4 merged PRs](https://github.com/naver/fixture-monkey/pulls?q=is%3Apr+is%3Amerged+author%3AYongGoose)
  - Register and select an `ArbitraryBuilder` by name [#1036](https://github.com/naver/fixture-monkey/pull/1036)

## Projects
- [Batch Control](https://plugins.jenkins.io/batch-control/) ([source](https://github.com/jenkinsci/batch-control-plugin)): a Jenkins plugin that requires approval for every run and keeps an audit trail of every change.
- [kotlin-pom-gradle](https://github.com/YongGoose/Maven-Central-utility-plugins-for-Gradle): a Gradle plugin for error-free publishing to Maven Central (GSoC '25).

## Writing
- [Centralized POM Configuration Management with kotlin-pom-gradle](https://dev.to/gradle-community/centralized-pom-configuration-management-with-kotlin-pom-gradle-1kap)
- [Spring 관점에서 보는 Seata의 내부 통신](https://solution-is-here.tistory.com/236)
- [Apache Seata란?](https://solution-is-here.tistory.com/235)
- [내가 JUnit5에 글로벌 Extension 필터링 기능을 추가한 이야기](https://solution-is-here.tistory.com/233)
- [내가 JUnit5에 병렬화를 도입한 이야기 - 메서드 단위](https://solution-is-here.tistory.com/231)
- [내가 JUnit5에 병렬화를 도입한 이야기 - 클래스 단위](https://solution-is-here.tistory.com/230)

## Get in touch
If you've got something fun to talk about in AI, email me at [yongjunh@apache.org](mailto:yongjunh@apache.org).
