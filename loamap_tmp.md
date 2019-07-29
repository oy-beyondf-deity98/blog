개발을 하기 위해서 알아야하는 범위는 어디까지 일까?
제일 작은 범위로는 개발틀을 가지고 개발을 한다. 
여기에만 두가지가 있다. 개발툴, 개발 언어, 
이것만 있을까? 플러그인이라는 것도 있다. 플러그인은 보통 틀에 종속되어 있으며, 개발 언어를 쓰기 편하게  도와 준다.
개발을 하는데는 크게 두가지가 있을것 같다. 데이터, 데이터를 다루는 기술들
데이터도 또 두가지가 쪼개진다. DB데이터, 파일데이터 
파일을 다루는 기술도 쪼개진다. 여러가지 파일의 포맷에 따라서.. 대략적으로는
*  Txt, 엑셀, 워드, hwp, json, xml, ppt등으로 나눌수록 있겠다.
데이터를 다루는 기술도 참 많다.
* 데이터 구조
* 파일, DB 
* .... 참 끝도 없네... 여기서 멈추자.

개발만 하면 끝나냐? 그렇지 않다. 
배포라는 기술이 필요하다. 서버에 하던... 내가 쓰던 배포를 해약한다.
실행 파일을 만들어서 쓸것인가와 was와 같은 서버를 통해서 실행할것인가 다르다.
* 둘다 어차피 한해의 파일에서 시작하게 되어있다.
혼자 만들것이 아니면 프로젝트 관리라는것이 또 들어간다. 모든 개발은 프로젝트를 만들어서 진행하므로...

프로그램이 커지고, 점점 사용자의 요구사항이 증가함에 따라서 소스와 라이브러리를 관리해야하는 시대가 되었다.

위에 열거한것만해도 꽤나 많다. 정리를 해보면 다음과 같지 않을까?
1. [프로젝트 관리](./project_manager.md) : 개발 관리
2. 소스 관리
    1. 형상관리
    2. 소스툴
    3. 소스구조와 라이브러리 관리
3. 소스구현
    1. 데이터 : 파일(엑셀,txt), DB, JSON,xml 등등` 
    2. 데이터를 다루는 기술
- 데이터 : 파일입출력, DB, API, 소켓통신 등등 
4. 배포 관리
5. 유지보수 관리
- 예상 접속수, 장애대응 방식, 사용자 디바이스(OS), 서버(OS)

---

0. 이론
    - 패턴 : GOF 
    - 알고리즘
    - 객체지향과 DDD
    - DataBase

1. GIT
    - git hub
    - git flow
2. 개발을 위한 공유
    - JIRA, Conflence
    - UML, ERD, 테이블 명세서
3. 개발
    1. 프론트 
        - reactJS
        - 모바일 : 안드로이드, 아이폰, 데스크탑(윈도우,맥)
    2. 백엔드
        - 자바 : 스프링부트
        - nodeJS, 파이썬
4. 배포도구 
    1. CI 
        - 젠킨스
    2. 툴
        - 그래들            
        - maven
    3. 실행/통합 도구
        - docker
    4. 모니터링 
        - 자바 : 스프링부트 admin
5. 기타툴        
        
> 모니터링은 오류를 확인하고 속도를 체크, 오류를 처리했는지도 알고 있고 오류 처리에 대한 내역서(or 문서)를 만들어서 사람들이 같은 오류로 고생할때 알려주면 좋을것 같다.

> 개발을 위한 공유 : 형상관리, 이슈관리, 설계서(UML, ERD, UI/UX), 개발툴
- 이슈관리툴 : redmine, jira
- UML과 ERD
- UI/UX : 기능정의, 
- 형상관리, 이슈관리, 개발툴을 묶는 방법 : 개발툴로만 진행
- 개발툴 : 이크립스, 비주얼코드, 인텔리J

> 모니터링은 어디까지 되어야하는가?
- 속도
- 요청에 대한 실패 확인
- 스트레스 테스트 : 무엇을 해야하는가?