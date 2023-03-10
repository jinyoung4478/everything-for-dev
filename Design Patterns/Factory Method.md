# Factory Method Pattern

> 부모 클래스에서 객체들을 생성할 수 있는 인터페이스를 제공하지만, 자식 클래스들이 생성될 객체들의 유형을 변경할 수 있도록 하는 생성 패턴

## 특징

-  Creational Pattern, Class Pattern
-  가상 생성자라고도 불림
-  객체 생성 시 인스턴스 생성을 서브 클래스에게 위임
-  부모 추상 클래스는 인터페이스에만 의존
-  어떤 구현 클래스를 호출하는지는 서브 클래스에서 구현
-  새로운 구현 클래스가 추가되어도 기존 Factory 코드를 수정하지 않고 새로운 Factory를 추가하면 됨
-  객체 생성의 변화에 대비하는 데 유용

## 예시

-  물류 관리 앱

## 장단점

-  장점: Factory Method 패턴의 가장 큰 장점은 지금까지 본 것처럼 수정에 닫혀있고 확장에는 열려있는 OCP 원칙을 지킬 수 있다는 점입니다.

-  단점: 간단한 기능을 사용할 때보다 많은 클래스를 정의해야 하기 때문에 코드량이 증가합니다.

## Reference

-  https://refactoring.guru/ko/design-patterns/factory-method
