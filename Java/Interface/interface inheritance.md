## 6-5. Interface Inheritance


인터페이스는 다중 상속을 허용함.

```java
public interface 하위인터페이스 extends 상위인터페이스1, 상위인터페이스2 { ··· } 
```

- 하위 인터페이스를 구현하는 클래스는 하위 인터페이스의 메소드뿐만 아니라 상위 인터페이스의 모든 추상 메소드에 대한 실체 메소드를 가지고 있어야 함.
- 구현 클래스로부터 객체를 생성한 후에 하위 및 상위 인터페이스 타입으로 변환이 가능함.
- 상위 인터페이스로 타입 변환되면 상위 인터페이스에 선언된 메소드만 사용 가능함.

👉🏻 [예제](https://github.com/gimhanul/Java/tree/master/src/interfacee/inheritance)