# 동뮤다 프로젝트
### DONGMUDA - Spring Boot with React

## 🖇️ 프로젝트 환경설정

### 프로젝트 경로
- C:\acnh\workspace

### 지원 Java 버전
- Java 18 사용
  - OpenJDK 18.0.2
    - C:\acnh\worktools\jdk\jdk-18.0.2
  - IntelliJ 설정 방법
    - File → Project Structure (Ctrl + Alt + Shift + S)를 들어가서 Project 탭에서 SDK를 원하는 버전 선택
    - File → Project Structure (Ctrl + Alt + Shift + S)를 들어가서 Modules탭에서 Sources 탭을 누른 뒤 Language level을 버전에 맞게 바꾸어 준다.
      - (Default 는 Project 설정의 SDK와 동일함)
- Spring Boot 버전별 필요 Java 사양
  - Spring Boot 3.x: Java 17 이상

### 패키지 명세
- 빌드 시 어플리케이션에 사용된 패키지를 설치하기 위해서는 `build.gradle` 혹은 `pom.xml` 파일에 올바르게 내용이 작성되어 있어야 합니다.
 
### 외부 라이브러리
- lombok : IntelliJ는 Lombok 라이브러리를 플러그인 형태로 제공하므로 플러그인 설치를 통해 적용
- 수동 설치 시 경로
  - C:\acnh\worktools\jar
  
## 🏷️ 프로젝트 구성

### 프로젝트 전체 구조
```
project-acnh-2024
  ├─ src
  │   ├─ main
  │   │   ├─ java(kr.kro.dongmuda)
  │   │   │   ├─ config
  │   │   │   ├─ exception  : exception 핸들러
  │   │   │   ├─ v1.0
  │   │   │   │   ├─ controller : api 컨트롤러
  │   │   │   │   ├─ vo : Request, Response ...
  │   │   │   │   └─ service
  │   │   │   └─ v1.1
  │   │   │      └─ ...
  │   │   └─ resoures
  │   └─ test
  ├─ build.gradle     : gradle 설정 및 build 파일
  ├─ settings.gradle  : 프로젝트 세팅 파일
  └─ logs             : 프로젝트 로그 폴더

```

### 환경변수

- `SPRING_PROFILES_ACTIVE`: 배포 프로필 설정
- `TZ`: 타임존 설정

## 💬 문제해결

- [클라우드타입 Docs](https://docs.cloudtype.io/)

- [클라우드타입 FAQ](https://help.cloudtype.io/guide/faq)

- [Discord](https://discord.gg/U7HX4BA6hu)


## 📄 License

[Apache-2.0](https://github.com/spring-projects/spring-boot/blob/main/LICENSE.txt)

