# 2020년 7월 27(월) 오프라인

## MariaDB
mySQL 삭제 후 mariaDB 설치 완료
설치 과정에서 encoding-utf8로 설정해야 했으나 못해서 my.ini 파일에서 수정
DB와 연동하여 GUI편집기인 workbrench 설치후 schema에 들어가서 테이블 속성 수정

***
톰캣 설치 --> JVM 위에 톰캣으로 웹 상에 앱을 실행 시켜준다.  
url : http:// 127.0.0.1:8080/프로젝트이름/webcontent 하위 .jsp파일  
***

**_DB자격증 : OCP, DA, SQL_** -- DB모델링, join 등...
***

## io
**_Stream_** : 데이터에 빨대를 꼽고 빨음 , byte -- char ''' 기반 스트림과 보조 스트림으로 나눠짐  

보조 스트림( 보조 스트림( 주 스트림))) 요런 느낌  

***
exception처리는 가독성도 떨어지고 비효율적. 가능하다면 if문으로 할 것.  
***
Scanner 클래스는 자동으로 stringToknizer 기능이됨 , next();

## Decorator Pattern
객체의 결합을 통해 기능을 동적으로 유연하게 확장 할 수 있게 해주는 패턴  
기본 기능에 추가할 수 있는 기능의 종류가 많은 경우에 각 추가 기능을  
Decorator 클래스로 정의한 후 Decorator 객체를 조합함으로써 추가 기능의 조합을 설계 하는 방식이다.

```java
	BufferedReader br = new BufferedReader(new InputStreamReader(new FileInputStream(file)));
```
```java
	BufferedReader br = new BufferedReader(new InputStreamReader(System.in, "utf-8"));
```

***
_채팅방 만들어보기_  
C:\gachon2020\강의\02.강의\01.Java Advanced Programming\03.Java 네트워크 프로그래밍



 
