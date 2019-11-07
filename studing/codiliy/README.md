다음을 참조해서 작성한다.
- https://github.com/dudmy/study
> 레슨12까지만 있네?

목표는 공간 퍼포먼스, 시간 퍼포먼스를 N(O)로 맞추는 것이다.

* CPU점유율은 어떻게 하지?
* 개인적으로 체크하는 시스템을 갖추어야할것 같은데?
* 누군가에게 조언을 얻을수 있으면 좋겠다.

---

나의 가장 큰 단점은 해석이다. 잘못 해석하면 잘못 코딩이 된다. 

## 
4. FrogJmp
- 반복문으로 해야할것 같은데 다시 생각해보면 그렇지 않다.
> 거리가 같을때 +1을 해야하는줄 알고 뛰는줄 알았는데 잘못해석했다.

5. 
- min과 max를 구해야할것 같
- 변환을 해야할것 같다.https://code-examples.net/ko/q/1062ff
- min, max를 구하는 여러가지 방법
    - https://www.daleseo.com/java-min-max/

> int[]와 Integer[]의 다른점을 알수 있다.

아니다... 이곳은 for문은 유도하지 않는다. 다르게 생각해보자. 의외로 쉽다.

그래도 min과 max를 구하는것을 알아두는 것은 좋은것 같다. 
> 알고르즘 문제에서는 null과 빈값같은 오류체크는 신경쓰지 않는다는것이 증명되었다.


---

array는 값을 구하기위해서는 반복문을 쓸수 밖에 없다.
알고리즘에서 array가 나오면 반복문을 안쓰는 방법을 확인해보는 방법과 반복문을 최소화하는 방법을 생각하도록 유도한다.
    - 자바로 배열과 List의 차이를 생각해보아야한다.
    - 주어지는 것은 배열이게 되므로...

int[] A = {A,B,C}//가 되는데.. 
System.out.println(A);
// 프린트로 A,B,C가 찍히게 하는 방법이 모가 있을까?

---

알고리즘과 현실의 다른점은... 알고리짐은 경계값이 분명하거나 무시하지만 현실은 경계값이 변경될수 있거나 무시할수 없다는 것아닐까?
    - 그 차이를 줄이는 것이 실전이아닐까?

---
시간은 아래와 같이 체크하는데... 공간은 어떻게 체크하지?
(시간복잡성과 공간복잡성)
O(N) = for문이 하나일때
Nlog(N) = for문이 2개일때? 그이상일때도?
O2(N) = for문안에 하나의 for문이 있을때를 말한다.

* 복잡성과 크기와는 같은것일까?
* 공간복잡성은 변수선언일까?    

---

코드에 대한 코딜리티와 같은 시스템은 어떻게 만들까?

시간, 공간, 점유율 체크
> 현실에서 제약사항은 어떻게 체크할것인가?

단어에 대한 체크도 하였으면 좋겠다.
> 점차... 완성되어가는 시스템

---

순열... 이라는것도 나오는구나..

알고리즘의 또다른 능력은 해석능력을 키우는 것이다.

그리고. 몬가 알것같기도 한데... 실제 몬가를 닥쳤을때의 일종의 패턴을 알게 할수도 있을것 같다.

1. 우리에게는 없는 문장 분석력
    - 알게모르게 자신이 알고 있는 범위에서만 해석하려고 한다. 그걸 벗어날수 있는 제일 쉬운 방법중에 하나가 알고리즘
2. 쓸데없이 저장해야할것을 버리게 해주는 습관을 준다.
3. 몬가... 패턴을 깨닫게 해준다.


알고리즘도 패턴과 비슷하구나.. 알고리즘의 기본이 되는것이 있고, 서로 연계한다. ㅋ

기본 자료구조를 알아야 알고리즘이 더 쉬워진다.
실제는 별로 쓸일이 없었던것으로 알고 있는데...
이것도 파다보면 몬가 나오겠지? 하루아침에 안나오겠네? ㅋ


하나를 파는게 아니라.. 전체를 훌터본다음에 계속 계속 반복해야하는 것이었어. 
- 프로그램 고유 특성인가? 모 이러냐.