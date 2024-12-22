# 수강신청 시스템 (Client-Server 기반)

## 🎯 프로젝트 배경 및 필요성
현대의 분산 시스템 환경에서 효율적인 데이터 처리와 사용자 경험 개선은 중요한 과제입니다. 본 프로젝트는 **김정호 교수님의 클라이언트-서버 프로그래밍 멘토링 수업**에서 제안된 실습 과제로, 클라이언트-서버 모델의 실질적인 구현을 통해 이론적 학습과 실무적 경험을 병행하기 위해 시작되었습니다.  

특히, 본 프로젝트는 Java RMI(Remote Method Invocation)를 기반으로 클라이언트-서버 통신을 구현하며, 이를 통해 다음의 목표를 달성하고자 합니다:
1. 클라이언트-서버 모델의 원리와 데이터 처리 방식에 대한 심층적인 이해.
2. 향후 분산 시스템 설계 패턴(Pipe & Filter, Event-Bus)과의 비교를 통해 다양한 소프트웨어 아키텍처의 장단점 분석.
3. 클라이언트와 서버 간의 통합적 데이터 관리 및 비즈니스 로직 처리 경험.

이러한 접근은 향후 확장성과 유지보수성이 뛰어난 시스템 설계의 기초를 다지기 위한 핵심 학습 과정으로 기능합니다.

---

## 📌 프로젝트 개요
본 프로젝트는 Java RMI를 활용하여 분산 환경에서의 클라이언트-서버 기반 수강신청 시스템을 개발하였습니다. 클라이언트는 사용자로부터의 요청을 처리하고, 서버는 이를 기반으로 데이터의 생성, 조회, 수정, 삭제(CRUD) 작업을 수행합니다. 이를 통해 사용자는 강의 정보를 조회하고, 수강신청 작업을 간단하게 수행할 수 있습니다.

---

## 💡 프로젝트 소개
- **목표**:
  1. 클라이언트-서버 모델을 활용한 수강신청 시스템 설계 및 구현.
  2. 분산 환경에서의 데이터 통신 및 관리의 효율성 증대.
  3. **Pipe & Filter**, **Event-Bus**와 같은 소프트웨어 설계 패턴의 장단점 분석 및 코드 구현 비교.

- **핵심 학습 내용**:
  - 클라이언트-서버 구조에서의 역할 분리와 통신 메커니즘 이해.
  - Java RMI를 이용한 원격 메서드 호출(Remote Method Invocation) 구현.
  - 다양한 아키텍처 패턴의 비교를 통한 설계 전략 강화.

- **기술 스택**:
  - Java, RMI (Remote Method Invocation)
  - 객체지향 설계 및 분산 시스템 개발.

---

## 🔑 주요 기능
1. **사용자 관리**
   - 사용자 추가, 삭제, 정보 조회, 비밀번호 변경.
   - 인증 시스템을 통한 보안 강화.

2. **학생 관리**
   - 학생 데이터의 생성, 조회, 수정, 삭제.
   - 특정 학생의 수강 과목 목록 확인.

3. **강의 관리**
   - 강의 정보 추가, 삭제 및 세부 정보 조회.
   - 선수 과목 조건 확인 및 관리.

4. **수강신청**
   - 학생의 수강 과목 등록 및 조회.
   - 선수 과목 조건 검증 후 수강신청 허용.

---

**본 프로젝트는 클라이언트-서버 모델의 학습과 함께, Pipe & Filter 및 Event-Bus 설계 패턴과의 비교를 통해 보다 심도 있는 소프트웨어 개발 경험을 제공하는 것을 목표로 합니다.**
