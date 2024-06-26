## 서문
+ 객체지향으로 향하는 첫 걸음은 클래스가 아니라 객체를 바라보는 것에서 시작
+ 두 번째는 객체를 독립적인 존재가 아니라 기능을 구현하기 위해 협력하는 공동체로 바라보기
+ 세 번째는 협력에 참여하는 객체들에게 얼마나 적절한 역할과 책임을 부여할 수 있는 지
+ 마지막으로 내가 사용하는 프로그래밍 언어라는 틀에 흐트러짐 없이 담아낼 수 있는 기술을 익히는 것

## 1장 - 협력하는 객체들의 공동체
+ "객체지향이란 실세계를 직접적이고 직관적으로 모델링할 수 있는 패러다임"
+ 하지만 이 설명에서 객체와 실세계 사물 사이에 존재하는 연관성은 희미
+ 즉 공부하기엔 좋지만 실용성은 떨어진다
+ 역할, 책임, 협력
    + 협력은 요청과 응답으로 구성
    + 역할은 책임을 내포
      + 여러 사람이 동일한 역할을 수행할 수 있다
      + 역할은 대체 가능
      + 책임을 수행하는 방법은 자율적으로 선택할 수 있다
        + 동일한 요청에 대해 서로 다른 방식으로 응답할 수 있는 것을 다형성이라고 한다
      + 한 사람이 동시에 여러 역할을 수행할 수 있다

### 객체는 협력적이어야 한다.
+ 전지전능한 객체는 내부적인 복잡도에 의해 자멸함
+ 명령에 따라 행동하는 것이 아닌 요청에 응답하는 것이다
+ 객체 스스로 판단한다
### 객체는 자율적이어야 한다.
+ 자기 스스로의 원칙에 따라 어떤 일을 하거나 자기 스스로를 통제하여 절제하는 것
### 상태와 행동을 지닌 실체인 객체
+ 객체는 다른 객체가 무엇을 수행하는지는 알 수 있지만 어떻게 수행하는지는 모른다
+ 메시지로 요청과 응답을 전달하고 sender와 receiver로 나뉜다
+ 수신된 메시지를 처리하는 방법을 메서드라고 한다
+ 메시지를 수신한 객체가 무슨 메서드를 쓸 지를 선택할 수 있다는 것은 다른 프로그래밍과의 차이점
+ 요청이 무엇인지를 표현하는 메시지와 그를 처리하는 방법을 구분하는 것이 캡슐화와도 관련있다
+ 객체지향하면 클래스를 떠올리는 것은 객체의 캡슐화를 저해하고 클래스를 서로 강하게 결합시킨다
+ ## 어떤 클래스가 필요한가가 아닌 어떤 객체들이 어떤 메시지를 주고받으며 협력하는가가 중요하다
+ 클래스는 객체들의 협력 관계를 코드로 옮기는 도구에 불과
+ 적절한 책임을 수행하는 역할 간의 유연하고 견고한 협력 관계
+ 클래스는 협력에 참여하는 객체를 만드는 데 필요한 구현 매커니즘
+ 클래스들의 정적인 관계가 중요한 것이 아닌 메시지를 주고 받는 객체들의 동적인 관계

### 느낀점
책임 역할 협력이 중요하다는 것은 알겠다
그런데 클래스가 객체를 담고 있으므로
클래스가 객체가 아닌가?
