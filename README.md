메이븐
빌드
	소스코드 파일 컴파일
	패키징 결과물
빌드도구
	생성
	테스트빌드
	배포
	라이브러리 추가
	프로젝트 진행 
	라이브러리 버전 동기화
	ANT
	Maven
	Gradle
	라이프사이클
	jar 추가 자동화
	POM.xml
	jar 작동한 필요한 다른 라이브러리를 
	네트워크 통해 자동으로 다운
	배포관리
	Build tool
	Project Management
	Life Cycle
	미리정해진 빌드 순서
	메이븐 프레임워크 
	동작방식 정해짐
	빌드순서
Life Cycle
	Default(build)
	Clean
	Validate
	Compile
	Test
	Package
	Verify
	Install
	Site
	Deploy
	
	compile
		src/main/java
	test
		src/test/java
		src/test/resources
	packaging
		jar war 로 압축
	Phase
		Build Lifecycle 각각의 단계
	
	중앙저장소
	/.m2/repository
		groupId 마다 폴더
		
		C:\Users\spman\.m2
mvn install:install-file
-Dfile= -DgroupId -DartifactId -Dpackage -Dversion=
<dependency> 추가
pom.xml
src/main/java 디렉토리 아래의 모든소스코드가 컴파일된다.
test
	src/test/java
	src/test/resources
	packaging
	의존관계
Goal
	task 최소실행단위
	-mvn plugin:goal
settings.xml
MAVEN_HOME/conf
.m2/repository/
POM
	Project Object Model
프로젝트 root의 존재
인텔리J는 자바 어디 설치
settings.xml
MAVEN_HOME/conf

C:\Users\spman\.m2\wrapper\dists\apache-maven-3.8.1-bin\2l5mhf2pq2clrde7f7qp1rdt5m\apache-maven-3.8.1