# TIL

Today I Learned

📎 **프로토타입 체인**

- 자바스크립트는 특정 객체의 프로퍼티나 메소드에 접근시 객체 자신의 것뿐 아니라 `__proto__` 가 가리키는 링크를 따라서 자신의 부모 역할을 하는 프로토타입 객체의 프로퍼티나 메소드를 접근할 수 있다.
- 특정 객체의 프로퍼티나 메소드 접근시 만약 현재 객체의 해당 프로퍼티가 존재하지 않는다면 `__proto__` 가 가리키는 링크를 따라 부모 역할을 하는 프로토타입 객체의 프로퍼티나 메소드를 차례로 검색하는 것이 바로 프로토타입 체인이다.
