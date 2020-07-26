# 2020년 7월 21일    

## Maven    
**Maven** : build tool의 하나로 이클립스 뿐만 아니라 다른 IDE에서도 돌아갈 수 있게 함(호환성이 좋다.)

## TDD
**_TDD(테스트 주도 개발)_** : 테스트를 먼저 만들고 통과를하기 위한 것을 짜는 것. 메인 메소드를 만들어 넣고 그뒤에 로직 짜는 느낌
    
## 접근자   

1. 무조건 접근자를 붙이는게 좋다    
2. 같은 패키지 접근 권한(default)은 굳이 따지지 않는다.    
3. private - 캡슐화, 데이터 접근을 막음    

## .gitignore
/target/
/.classpath
/.project
/.settings

## 멀티 프로젝트 (Maven Project)
부모 프로젝트를 Maven Project로 설정하고 자식 프로젝트는 Maven Module로 설정하면됨
module추가시 pom.xml 에 모듈추가됨 

_오류시_
***
간단한 해결방법   
1.Maven-> project update 
2. 해당 프로젝트 이름변경 -> 새로 프로젝트 생성