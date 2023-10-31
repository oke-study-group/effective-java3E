# Effective-java3/E
from Joshua Bloch

### 책에서 다루는 내용
- Java 7,8,9에서 자바 언어와 라이브러리에 추가된 특성들을 다룬다
- Java 7 -> try-with-resources
- Java 7 -> @SafeVarargs
- 함수형 인터페이스
- Java 8 -> 람다식의 등장 
- Java 8 -> 스트림
- Java 8 -> interface (default method / static method) 
- Java 8 -> Optional<T> interface
- Java 9 -> Module 시스템



## 2판에서의 내용
- Java 5가 도입한
    - Generics 제네릭
    - enum 열거 타입
    - autoboxing 오토박싱
    - for-each
    - 동시성 라이브러리 java.util.concurrent

## 자바 8용 언어 명세 (The Java Language Specification, Java SE 8 Edition)
자바가 지원하는 타입
- interface 인터페이스
- class 클래스
- array 배열 
- primitive 기본 타입

## 주의할 점 
- 책에서는 상속(inheritance)과 서브클래싱(subclassing)을 동의어로 쓴다.
- 인터페이스 상속 대신 
    - 클래스가 인터페이스를 구현한다. (implement)
    - 인터페이스가 다른 인터페이스를 확장한다. (extend)