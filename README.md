#Spring_day

##자바 프로젝트에 MyBatis 설정
1. 자바 프로젝트 준비.
> mybatis_test01 생성
a
2. 라이브러리 준비.
> http://www.mybatis.org/mybatis-3/ko/getting-started.html
> 시작하기 메뉴 클릭
> 
> *다른 방법*
> 1. mvnrepository.com 접속
> 2. mybatis 라이브러리 검색
>> MyBatis Spring :: 스프링이랑 연동하고 싶을때
>> MyBatis :: 별도로 연동하고 싶을 때

<!-- https://mvnrepository.com/artifact/org.mybatis/mybatis -->
<dependency>
    <groupId>org.mybatis</groupId>
    <artifactId>mybatis</artifactId>
    <version>3.3.1</version>
</dependency>

> 3. mybatis-3.3.1.jar 다운로드

> 4. http://www.h2database.com/html/main.html 튜토리얼에서 DB연동 정보 검색
>> h2DB 사용
>> SARAM 테이블이 준비 되었다.
>> ID, NAME, AGE 필드

> 5. mybatis-config.xml 파일
>> 구글에서 "마이바티스"검색 -> 한글 문서 참조
>> 프로젝트 src에 mybatis-config.xml 생성하기
