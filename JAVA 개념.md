# JAVA 개념

### 목차

* [개요](#개요)
  * [자바](#자바)
  * [자바의 종류](#자바의-종류)
  * [자바 개발 도구](#자바-개발-도구)



## 개요

1. 프로그램: CPU 명령어의 나열
2. 기계어: 컴퓨터가 이해하는 유일한 언어 (0과 1로 구성)
3. 프로그래밍 언어(인간) -> **컴파일러** -> 기계어(컴퓨터)로 변환
4. 자바: 프로그래밍 언어의 일종



### 자바

* 1991, 썬마이크로시스템즈의 제임스 고슬링(James Gosling) 개발
* 초창기: 간단하고 버그가 없으며 네트워크 기능을 내장한 프로그램을 작성하는 언어를 목표.
* 자바는 플랫폼 중립적인 언어이기 때문에 웹 기반의 응용 프로그램에 이상적.
* 2009년 오라클이 썬마이크로시스템즈를 인수하면서 현재는 오라클에서 자바의 최신 버전을 제공하고 있다.

* 일반적인 프로그래밍 언어는 플랫폼에 종속된다.
  * ex. c++
  * 일반적인 프로그래밍 언어로 만들어진 프로그램은 컴파일러에 의해 특정 CPU의 기계어로 변환된다.
  * CPU가 다른 컴퓨터에서는 실행되지 않는다.
* **자바는 플랫폼에 종속되지 않는다.**
  * 가상 기계(VM: Virtual Machine) 개념을 사용한다.
  * 소스 프로그램을 가상 컴퓨터의 기계어로 번역하고 이것은 자바 가상 기계(Java Virtual Machine)에 의해 실행된다.
  * 자바로 개발된 프로그램은 CPU나 운영 체제의 종류에 관계없이 어디서나 실행할 수 있다.
* 자바 프로그램 실행과정
  1. 소스 코드 -> 컴파일러 -> 바이트 코드: 자바 언어로 작성된 프로그램을 가상 컴퓨터의 기계어가 들어있는 파일(바이트 코드)로 변환
  2. 바이트 코드 -> 자바 가상 기계(JVM) -> 파일 실행: JVM(Java Virtual Machine)은 특수한 가상 컴퓨터 S/W
  3. 두 단계로 나눠서 컴파일하고 실행하는 이유: 응용 프로그램들을 다시 컴파일하지 않아도 모든 컴퓨터에서 실행되도록 하기 위해서이다.



### 자바의 종류

* Java SE(Standard Edition)
  * 자바 언어의 핵심 기능을 제공
  * 자바 언어의 기본적인 타입과 객체에서부터 네트워킹, 보안, 데이터베이스 접근, 그래픽 사용자 인터페이스(GUI), XML 파싱에 사용되는 고수준의 클래스까지 모두 정의한다.
* Java EE(Enterprise Edition)
  * Java SE 플랫폼 상에 구축된다.
  * 기업용 애플리케이션을 개발하는 데 필요한 여러가지 도구 및 라이브러리들을 모아 놓은 것.
* Java ME(Micro Edition)
  * Java SE의 부분집합에, 모바일 장치를 위한 특수한 클래스 라이브러리가 추가된 것



### 자바 개발 도구

* 자바 프로그램을 개발하기 위해 자바 컴파일러가 필요하다.
* JDK(Java Development Kit): 자바 컴파일러와 자바 가상 기계(JVM), 디버깅 도구, 각종 유틸리티 등의 도구들.

#### JRE vs JDK

* JRE(Java Runtime Environment)
  * 자바 프로그램을 실행하기 위한 라이브러리, 자바 가상 기계, 기타 컴포넌트들을 제공한다.
  * 자바 프로그램을 실행만 할 뿐 개발을 하지 않는 일반인들을 위한 환경.
* JDK(Java Development Kit)
  * JRE에 자바 프로그램을 개발하는 데 필요한 컴파일러, 디버거와 같은 도구들을 추가한 것
  * JDK 안에 JRE가 포함되어 있다.
  * <u>개발자를 위한 환경.</u>



***

[참고] 천인국, Power Java, INFINITYBOOKS(2018)