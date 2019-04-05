# [프로젝트 만들기](./pratice_coding)
# 개발을 위한 로드맵
개발을 하기 위해서 알아야할게 왜 이렇게 많아 졌는가? 좀더 단순하게 정의할수는 없는가? 
개발을 하여야 하고 그걸 배포하기 위해서 알게 참 많다.
현재의 최적화를 한번 알아보자.
일단 작업들을 프로젝트로 묶자. 프로젝트 아래에 마일스톤으로 묶는다. 마일스톤은 또 스프린트로 나뉜다. 스프린트에서 실제 작업할것이라는 것을 이슈라고 정의하자. 스프린트는 작업자가 집중할수 있는 단위라고 생각하면 될것 같다. 마일스톤은 사용자에게 보여줄만하다는 단위라고 생각하면 될것 같다. 
이슈가 생겼으면 이제 일을 해야한다. 일을 하려면 프로젝트라는 코드의 구조가 나와야한다. 그 구조를 maven이나 gradle로 잡는다. 작업을 완료하면 작업한 코드를 저장해야하는 곳이 생긴다. 이것을 다른말로  형상관리라고 하고 그 도구로는 git, svn을 주로 쓴다. 

그런데 형상관리도구를 쓰면서 문제 점이 생긴다. 서로 같은 소스를 건드릴때 발견하는 충돌이다. git은 이것을 방지하기 위해서 branch단위로 작업을 하게 한다(git flow). branch단위로 작업하고 서버에 작업한것을 보내고, 서로 통합해줄것을 중앙관리자에게 요청한다(full request). 

full request가 통과된 소스는(remote merge) 개발서버에 적용되고(CI : 젠킨스로 진행, 젠킨스에서 docker로 만든다), 기획자나 설계자가 본뒤에 통과되면 작업이 완료된다.

그뒤로 실행하면서 오류가 나는것을 모니터링 도구로 살펴보거나 현업이 알려준다. 

마일스톤이 끝나면 개발이 되었다는 보고서나 개발에 대한 문서를 만들게 된다.
그건 프로젝트가 끝날때도 마찬가지이다.

결과물은 프로젝트에서 요구하는이 모두 다르다. 

* 이론은 작업을 설명들을때 어떤것을 적용하겠다는 실 코드까지의 상황을 바로 알게 해주는 단위라고 할수도 있다.
* 또는 프로젝트의 개요쯤을 기본 베이스를 설계할수도 있다. 그래서 그것의 제약사항 될수도 있다.


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

---

* [깃허브 페이지 만들기](makeMyGitHubPage.md)
