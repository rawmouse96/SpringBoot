
# SpringBoot

## Base
#### Server & Client
- Client : 서버로 요청하는 프로그램을 통칭
- Server : 클라이언트의 요청을 받아 처리하는 주체
- DB : 여러사람이 데이터를 한 군데에 모아놓고 사용할 목적으로 관리하는 데이터 저장소
  1. RDB (Relational DB) : 관계형 DB는 데이터를 행(row)과 열(column)으로 이루어진 테이블로 관리, 기본키(primary key)를 사용해 행을 식별하고 테이블 간의 관계 규정 가능.
  2. NoSQL : No SQL or Not Only SQL, 비관계형 데이터베이스 유형
 
#### IP & Port
- IP : 인터넷에서 컴퓨터 또는 기기들이 서로를 식별하고 통신하기 위한 주소
- Port : IP를 통해 기기(서버)를 찾은 후 서비스를 구분하기 위한 번호

#### Library & FrameWork
- Library : 애플리케이션 개발에 필요한 기능인 클래스, 함수 등을 모아놓은 코드의 모음
- FrameWork : 소프트웨어 개발을 수월하게 하기위한 소프트웨어 개발 환경

* java annotation : 자바로 작성한 코드에 추가하는 표식, @temp와 같이 작성하며 메타데이터로 사용하는 경우가 많음

#### Spring Concept
* Spring Container : 빈(Bean)을 생성하고 관리. 빈의 생성 ~ 소멸까지의 생명주기를 관리하고 애너테이션을 사용해 빈을 주입받을 수 있게 DI를 지원.
* 빈(Bean) : 스프링 컨테이너가 생성하고 관리하는 객체.
- IoC (Inversion of Control) : 제어의 역전, 객체 직접 생성 방식 -> 스프링 컨테이너에서 받아온 객체를 할당. 객체의 생성과 관리를 개발자가 하는 것이 아니라 프레임워크가 대신하는 것.
    - 객체 간 낮은 결합도, 유연한 코드 작성 가능, 가독성 증가, 코드 중복 방지, 유지 보수 용이
- DI(Dependency Injection) : 의존성 주입, 객체를 직접 생성하는 것이 아니라 외부에서 주입받아 사용하는 방식.
  - final로 선언 가능 (불변성),  재사용성이 높아진다, NullPointerException이 발생하지 않는다.
- AOP(Aspect Oriented Programming) : 관점지향 프로그래밍, 프로그래밍에 대한 관심을 핵심관점과 부가관점으로 나누어 개발, 모듈화.
- PSA(Portable Service Abstraction) : 이식 가능한 서비스 추상화, 스프링에서 제공하는 다양한 기술들을 추상화해 개발자가 쉽게 사용하는 인터페이스. 일관된 방식으로 개발.

