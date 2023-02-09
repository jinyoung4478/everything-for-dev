# Design Patterns

## Design Patterns

소프트웨어 설계에서 반복적으로 나타나는 문제를 해결하기위한 설계 기법

-  목적
   -  공통적인 상황을 만나는 개발자들이 경험과 지식을 공유하여 개선된 솔루션을 제안하기 위함
   -  SW 재사용성, 호환성, 유지 보수성을 보장
-  GoF Design Patterns
   -  [Design Patterns: Elements of Reusable Object-Oriented Software] 책에 의해 유행한 특정 디자인 패턴의 집합
   -  GoF(Gang of Four): 해당 책을 쓴 4명의 저자
-  분류
   -  목적에 따른 분류
      -  생성(Creational)
      -  구조(Structural)
      -  행동(Behavioral)
   -  범위에 따른 분류: 클래스 패턴, 객체 패턴

---

## Creational Patterns

객체의 생성 방식 결정

-  Class Pattern: 객체를 생성 일부를 서브클래스에게 위임
   -  [Factory Method](https://github.com/jinyoung4478/everything-for-dev/blob/main/Design%20Patterns/Factory%20Method.md)
-  Object Pattern: 객체 생성을 다른 객체에게 위임
   -  Abstract Factory
   -  Builder
   -  Prototype
   -  Singleton

---

## Structural Patterns

객체간의 관계를 조직

클래스나 객체들을 조합하여 더 큰 구조로 만듦

-  Class Pattern: 상속을 통해 클래스나 인터페이스를 합성
   -  Adaptor(Class)
-  Object Pattern: 객체를 합성하는 방법을 정의
   -  Adaptor(Object)
   -  Composite
   -  Bridge
   -  Proxy
   -  Flyweight
   -  Facade
   -  Decorator

---

## Behavioral Patterns

객체나 클래스의 교류 방법(조직, 관리, 연합)에 대해 정의

하나의 객체로 수행할 수 없는 작업을 여러 객체로 분배하면서 그들 간의 결합도를 최소화

-  Class Pattern: 상속을 통해 알고리즘과 제어 흐름을 기술
   -  Interpreter
   -  Template Method
-  Object Pattern: 하나의 작업을 수행하기 위해 객체 집합이 어떻게 협력하는지를 기술
   -  Mediator
   -  Chain of Responsibility
   -  Observer
   -  Command
   -  State
   -  Visitor
   -  Iterator
   -  Memento
   -  Strategy

---

## Reference Links

-  [신입 개발자 전공 지식 & 기술 면접 백과사전](https://github.com/gyoogle/tech-interview-for-developer)
-  [[Design Pattern] GoF(Gang of Four) 디자인 패턴](https://4z7l.github.io/2020/12/25/design_pattern_GoF.html)
