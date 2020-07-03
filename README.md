# repo
ART SERVER 의 Maven repository 사용설명서

> **사용전 인증 작업이 필요합니다**\
> [깃허브 공식 문서](https://docs.github.com/en/packages/using-github-packages-with-your-projects-ecosystem/configuring-apache-maven-for-use-with-github-packages)를 참고해주세요.

## 리포지토리 추가
```
<repositories>
    <repository>
        <id>artserver</id>
        <url>https://maven.pkg.github.com/artserver/repo/</url>
    </repository>
</repositories>
```

## [ConfigManager](https://github.com/artserver/ConfigManager)
플러그인의 설정 파일을 쉽게 관리해줍니다.
```
<dependencies>
    <dependency>
        <groupId>aren227</groupId>
        <artifactId>configmanager</artifactId>
        <version>1.0-SNAPSHOT</version>
        <scope>provided</scope>
    </dependency>
</dependencies>
```

## [DataStorage](https://github.com/artserver/Datastorage)
플레이어 데이터와 플러그인 데이터를 빠르게 불러오고 저장할 수 있습니다.
```
<dependencies>
    <dependency>
        <groupId>kr.laeng</groupId>
        <artifactId>datastorage</artifactId>
        <version>1.0-SNAPSHOT</version>
        <scope>provided</scope>
</dependency>
</dependencies>
```   
