## 6-4-4. Casting

구현 객체가 인터페이스 타입으로 promotion하면 인터페이스에 선언된 메소드만 사용 가능함. 하지만 경우에 따라서 구현 클래스에 선언된 필드와 메소드를 사용해야 하는 경우도 발생함. 이때  casting을 통해 다시 구현 클래스 타입으로 변환하고 구현 클래스의 필드와 메소드를 사용할 수 있음.

하지만, casting을 하기 전 [instanceof() 연산자](https://www.notion.so/Java-e6e3d6ff76cf4fc48268123416eda79a)를 통해 객체 타입을 확인하고 안전하게 casting을 해야 함.

👉🏻 [예제](https://github.com/gimhanul/Java/tree/master/src/interfacee/polymorphism/casting)