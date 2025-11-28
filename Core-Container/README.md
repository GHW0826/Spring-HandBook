# IoC 컨테이너 / BeanFactory / ApplicationContext

# IOC/DI
- IOC
  - Inversion Of Control 제어의 역전을 의미.
  - 객체의 생성, 생명주기, 관리등 객체에 대한 주도권을 프레임워크가 가진것을 의미한다.
  - IoC를 통해 Application을 구성하는 객체 간의 낮은 결합도 유지 가능
  - IoC의 역할을 담당하는 것은 Spring Container (IoC Container)

- DI
  - Dependency Injection (의존성 주입)
  - new로 객체를 생성하는 것이 아닌, 외부에서 생성된 객체를 주입받아 사용하는 것.
  - 결합성을 class로 부터 분리.
  - Application 실행 시점에 객체 간의 관계를 결정, 주입
  - DI 방법 3가지
    - 생성자 주입
    - 필드 주입
    - Setter(수정자) 주

- Spring Container
  - Spring Application 내에서 자바 객체를 관리하는 공간.
  - 자바 객체를 Bean이라고 부름
  - 컨테이너의 역할은 의존성 주입(DI, Dependency Injection)을 통하여 Application을 구성하는 Bean들의 생명주기를 개발자 대신 관리함

  - 스프링 컨테이너의 종류는 크게 2가지
    - BeanFactory
    - ApplicationContext
