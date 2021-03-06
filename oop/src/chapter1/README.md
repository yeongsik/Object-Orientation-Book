## Chapter 1 협력하는 객체들의 공동체

### 협력 , 역할 , 책임

- 혼자서 하는 것보다 `협력`해서 공동체를 이루는 것이 더 큰 일을 할 수 있다.
- `협력`하는 데에 요청과 응답이 필요하다
- 각자 위치에서 `역할`과 `책임`을 갖고 요청에 응답한다.

### 역할과 책임

- 여러 객체가 `동일한` 역할을 수행할 수 있다.
- 역할은 `대체 가능성`을 의미
- 각 객체는 책임을 수행하는 `방법`을 `자율적`으로 선택 할 수 있다.
- 하나의 객체가 동시에 여러 `역할`을 수행할 수 있다.

### 협력

<aside>
💡 “어떤 객체도 섬이 아니다”  [Beck 1989]

</aside>

- 협력은 요청과 응답으로 구성된다.
- 협력적이면서 `자율적인 객체` 를 만들어야 한다.

### 자율적인 객체

- 객체는 `상태` 와 `행동` 으로 구성
- 객체의 상태는 사적인 부분 `private`  스스로 관리 ( 사생활 )
- 스스로 판단하고 행동 , 수행방법을 스스로 결정

### 메시지

- 객체지향 세계에서 한가지 `의사소통` 수단
- 송신자 - 수신자 객체

### 메서드

- 수신된 메세지를 처리하는 방법 ⇒ `method`
- 메시지와 메서드를 분리하는 것은 `객체의 자율성`을 높이는 핵심 메커니즘

## 객체지향의 본질

- 객체지향이란 시스템을 상호작용하는 `자율적인 객체들의 공동체` 로 객체를 이용해 시스템을 분할하는 방법
  

- 자율적인 객체란 `상태`와 `행위`를 함께 갖고 스스로를 책임지는 객체
  

- 객체는 시스템의 행위를 구현하기 위해 다른 객체와 `협력`한다. 각 객체는 협력 내에서 정해진 `역할` 을 수행하며 역할은 관련된 `책임`의 집합이다.
  

- 객체는 다른 객체와 협력하기 위해 메시지를 전송하고, `메시지`를 수신한 객체는 메시지를 처리하는 데 적합한 `메서드`를 자율적으로 선택

### 출근 길 아침 카페

* Customer , Casher , Barista , Coffee , Menu 
* Customer : 커피 주문하기 
* Casher : 주문 받기 
* Barista : 커피 만들기 


