### 6-1-1. constant field

데이터를 저장할 수 있는 인스턴스또는 정적 필드를 선언할 수 없음. 하지만 고정된 값으로 데이터를 바꿀 수 없는 상수 필드(constant field)는 선언할 수 있음.

```java
[public static final] 타입 상수이름 = 값;
```

> 👉🏻 public static final을 생략해도 컴파일 과정에서 자동으로 붙음.


작성할 때 

- 대문자로 작성함.
- 서로 다른 단어로 구성되어 있을 경우에는 언더바(`_`)로 연결함.
- 초기값을 지정함.