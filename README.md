# 대신 장봐주는 남자


## 1. 공모전 소개

### 2016 SW 동아리 재능기부 챌린지
```
1) 소속 : 계명대학교 경영정보학과 소프트웨어 개발 동아리 '수은불망' 내의 팀 '마에스트로'
2) 목표 : 지역의 소상공인과 협력하여 SW 개발 동아리의 재능기부 실천 및 실력 향상, 동시에 소상공인에게 도움이 되는 SW를 개발
3) 기간 : 2016.04 ~ 2016.11
4) 구성원 : 5명
5) 참여도 : 100%
6) 담당업무 : 기획, 분석 및 설계, 개발
7) 주요실적 : 기획, 분석 및 설계, 웹 상품관리의 진열관리, 푸시알림 관리 및 애플리케이션 메인 개발 담당
```

## 2. 개발환경

```
언어: Java
IDE: Eclipse
WAS: Apache Tomcat 7.0.73
DBMS: MySQL
버전관리: SVN
기타: HTML5, CSS3, Bootstrap, JSP, MyBatis, JavaScript, JQuery, Ajax, Android, Cordova
```
### Spring Framework 3.2.4
```
<dependencies>
	<!-- gcm-server -->
	<dependency>
		<groupId>com.google.gcm</groupId>
		<artifactId>gcm-server</artifactId>
		<version>1.0.0</version>
	</dependency>
	<!-- json-simple -->
	<dependency>
		<groupId>com.googlecode.json-simple</groupId>
		<artifactId>json-simple</artifactId>
		<version>1.1.1</version>
	</dependency>
	<!--  엑셀 업로드 -->
	<dependency>
		<groupId>org.apache.poi</groupId>
		<artifactId>poi</artifactId>
		<version>3.9</version>
	</dependency> 
	<dependency>
		<groupId>org.apache.poi</groupId>
		<artifactId>poi-ooxml</artifactId>
		<version>3.9</version>
	</dependency>
	<!-- JSON 관련  -->
	<dependency>
		<groupId>net.sf.json-lib</groupId>
		<artifactId>json-lib</artifactId>
		<version>2.4</version>
		<classifier>jdk15</classifier>    
	</dependency>
	<dependency>
		<groupId>org.codehaus.jackson</groupId>
		<artifactId>jackson-mapper-asl</artifactId>
		<version>1.9.13</version>
	</dependency>
	<!--보기편한로그 -->
	<dependency>
		<groupId>org.lazyluke</groupId>
		<artifactId>log4jdbc-remix</artifactId>
		<version>0.2.7</version>
	</dependency>      
	<!-- Mysql -->
	<dependency>
		<groupId>org.springframework</groupId>
		<artifactId>spring-jdbc</artifactId>
		<version>3.2.4.RELEASE</version>
	</dependency>
	<dependency>
		<groupId>mysql</groupId>
		<artifactId>mysql-connector-java</artifactId>
		<version>5.1.26</version>
	</dependency>    
	<dependency>
		<groupId>org.mybatis</groupId>
		<artifactId>mybatis</artifactId>
		<version>3.2.2</version>
	</dependency>
	<dependency>
		<groupId>org.mybatis</groupId>
		<artifactId>mybatis-spring</artifactId>
		<version>1.1.1</version>
	</dependency>
	<!-- MultipartHttpServletRequset -->
	<!-- 파일 업로드 -->
	<dependency>
		<groupId>commons-io</groupId>
		<artifactId>commons-io</artifactId>
		<version>2.0.1</version>
	</dependency>
	<dependency>
		<groupId>commons-fileupload</groupId>
		<artifactId>commons-fileupload</artifactId>
		<version>1.2.2</version>
	</dependency>
	<!-- JSON -->
	<dependency> 
		<groupId>com.fasterxml.jackson.core</groupId> 
		<artifactId>jackson-core</artifactId> 
		<version>2.4.1</version>
	</dependency> 
	<dependency> 
		<groupId>com.fasterxml.jackson.core</groupId> 
		<artifactId>jackson-databind</artifactId> 
		<version>2.4.1.1</version>
	</dependency>
	<!-- 끝부분 -->
	<!-- Spring -->
	<dependency>
		<groupId>org.springframework</groupId>
		<artifactId>spring-context</artifactId>
		<version>${org.springframework-version}</version>
		<exclusions>
			<!-- Exclude Commons Logging in favor of SLF4j -->
			<exclusion>
				<groupId>commons-logging</groupId>
				<artifactId>commons-logging</artifactId>
			</exclusion>
		</exclusions>
	</dependency>
	<dependency>
		<groupId>org.springframework</groupId>
		<artifactId>spring-webmvc</artifactId>
		<version>${org.springframework-version}</version>
	</dependency>
	<!-- AspectJ -->
	<dependency>
		<groupId>org.aspectj</groupId>
		<artifactId>aspectjrt</artifactId>
		<version>${org.aspectj-version}</version>
	</dependency>	
	<!-- Logging -->
	<dependency>
		<groupId>org.slf4j</groupId>
		<artifactId>slf4j-api</artifactId>
		<version>${org.slf4j-version}</version>
	</dependency>
	<dependency>
		<groupId>org.slf4j</groupId>
		<artifactId>jcl-over-slf4j</artifactId>
		<version>${org.slf4j-version}</version>
		<scope>runtime</scope>
	</dependency>
	<dependency>
		<groupId>org.slf4j</groupId>
		<artifactId>slf4j-log4j12</artifactId>
		<version>${org.slf4j-version}</version>
		<scope>runtime</scope>
	</dependency>
	<dependency>
		<groupId>log4j</groupId>
		<artifactId>log4j</artifactId>
		<version>1.2.15</version>
		<exclusions>
			<exclusion>
				<groupId>javax.mail</groupId>
				<artifactId>mail</artifactId>
			</exclusion>
			<exclusion>
				<groupId>javax.jms</groupId>
				<artifactId>jms</artifactId>
			</exclusion>
			<exclusion>
				<groupId>com.sun.jdmk</groupId>
				<artifactId>jmxtools</artifactId>
			</exclusion>
			<exclusion>
				<groupId>com.sun.jmx</groupId>
				<artifactId>jmxri</artifactId>
			</exclusion>
		</exclusions>
		<scope>runtime</scope>
	</dependency>

	<!-- @Inject -->
	<dependency>
		<groupId>javax.inject</groupId>
		<artifactId>javax.inject</artifactId>
		<version>1</version>
	</dependency>
	<!-- Servlet -->
	<dependency>
		<groupId>javax.servlet</groupId>
		<artifactId>servlet-api</artifactId>
		<version>2.5</version>
		<scope>provided</scope>
	</dependency>
	<dependency>
		<groupId>javax.servlet.jsp</groupId>
		<artifactId>jsp-api</artifactId>
		<version>2.1</version>
		<scope>provided</scope>
	</dependency>
	<dependency>
		<groupId>javax.servlet</groupId>
		<artifactId>jstl</artifactId>
		<version>1.2</version>
	</dependency>

	<!-- Test -->
	<dependency>
		<groupId>junit</groupId>
		<artifactId>junit</artifactId>
		<version>4.7</version>
		<scope>test</scope>
	</dependency>        
</dependencies>
```
## 3. 주요기능

### 관리자 웹
* [매장 관리](/debec/src/main/webapp/WEB-INF/views/market)
* [상품 관리](/debec/src/main/webapp/WEB-INF/views/prodct)
* [거래 관리](/debec/src/main/webapp/WEB-INF/views/deal)
* [고객 관리](/debec/src/main/webapp/WEB-INF/views/custmr)
* [마감 관리](/debec/src/main/webapp/WEB-INF/views/end)
* [개인 정보 관리](/debec/src/main/webapp/WEB-INF/views/login)

### 관리자 & 고객 애플리케이션
* [로그인 및 회원가입](/debecApp/assets/www/view/LoginFrame.html)
* [메인](/debecApp/assets/www/view/Main.html)
* [마켓](/debecApp/assets/www/view/MarketCusDebecChoiceMain.html)
* [레시피](/debecApp/assets/www/view/RecpList.html)
* [담소방](/debecApp/assets/www/view/CommunityList.html)
* [마이페이지](/debecApp/assets/www/view/MyPageEmpMain.html)
