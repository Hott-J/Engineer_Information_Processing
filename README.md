# <Engineer_Information_Processing>
- - -
## 소프트웨어 설계
### 1. 요구사항 확인
<details markdown= "1">
<summary> 요구사항 확인 정리</summary>

## 1. 소프트웨어 생명 주기

> ### 소프트웨어 생명 주기(Life Cycle)

- 소프트웨어 개발 방법론의 바탕이 되어 소프트웨어를 개발하기 위해 정의하고 운용 유지보수 등의 과정을 각 단계별로 나눈 것

- 스프트웨어 개발 단계와 각 단계별 주요 활동 및 활동의 결과를 산출물로 표현

- 소프트웨어 생명 주기를 표현하는 형태를 소프트웨어 생명 주기 모형, 소프트웨어 프로세스 모형, 소프트웨어 공학 패러다임이라고 함

- 특정 모형을 선택하여 사용하거나 개별적인 모형을 사용할 수 있음

<br/>

> ### 폭포수 모형

- 폭포수가 거슬러 올라갈 수 없듯이 이전 단계를 확실히 마무리하고 다음 단계로 진행하는 개발 방법론

- 소프트웨어 공학에서 가장 오래되고 폭넓게 사용된 생명 주기 모형

- 한 단계가 끝나야 다음 단계로 넘어갈 수 있는 선형 순차적 모형

- 매뉴얼을 작성해야 함

- 단계를 끝내고 다음 단계로 가기 위해서는 결과물이 명확히 나와야함

<br/>

> ### 프로토타입 모형

- 요구사항을 정확히 파악하기 위해 실제 개발될 소프트웨어에 대한 시제품을 만들어 최종 결과물을 예측하는 모형

- 폭포수 모델의 단점을 보완하기 위해 만들어진 모형

- 사용자와 시스템 사이 인터페이스에 중점을 두어 개발

<br/>

> ### 나선형 모형

- 폭포수 모형과 프로토타입 모형의 장점에 위험 분석 기능을 추가한 모형

- 나선을 따라 돌듯이 여러 번의 개발 과정을 거쳐 점진적으로 완벽한 최종 소프트웨어를 개발

- 소프트웨어를 개발하면서 발생할 수 있는 위험을 관리하고 최소화하는 것이 목적

- 누락되거나 추가된 요구사항을 첨가할 수 있음

- 정밀하고 유지보수 과정이 필요 없음

<br/>

> ### 애자일 모형

- 고객의 요구사항 변화에 유연하게 대응할 수 있도록 일정한 주기를 반복하면서 진행하는 모형

- 좋은 것을 빠르고 낭비 없게 만들기 위해 고객과의 소통에 초점을 맞춘 모든 방법론을 통칭

- 스프린트 또는 이터레이션이라고 불리는 짧은 개발 주기를 반복

- 반복되는 주기마다 결과물에 해단 평가와 요구 수용

- 요구사항에 우선순위를 부여하여 개발 진행

- 애자일 모형을 기반으로 하는 모형에는 스크럼, XP, 칸반, Lean, 크리스탈, ASD, FDD, DSDM 등이 있음

<br/>

## 2. 스크럼 기법

> ### 스크럼의 개요

- 팀이 중심이 되어 개발의 효율성을 높임

- 팀원 스스로가 팀을 구성하고 개발 작업에 대한 모든 것을 스스로 해결할 수 있어야 함

<br/>

> ### 스크럼의 구성 요소

+ 제품 책임자

    * 개발될 제품에 대한 이해도가 높고 요구사항을 책임지고 의사 결정할 사람

    * 개발 의뢰자나 사용자가 담당

    * 이해관계자들의 의견을 종합하여 제품에 대한 요구사항을 작성

    * 백로그를 작성

    * 팀원들은 백로그에 스토리는 추가할 수 있지만 우선순위를 지정하는 것은 제품 책임자임

    * 테스트를 수행하면서 주기적으로 요구사항의 우선순위 갱신

+ 스크럼 마스터

    * 팀이 잘 수행할 수 있도록 객관적인 시각에서 조언을 해주는 가이드 역할

    * 일일 스크럼 회의를 주관하여 진행 사항을 점검하고 개발과정에서 발생된 장애 요소를 공론화하여 처리

+ 개발팀

    * 개발자 외에도 디자이너, 테스터 등 제품 개발을 위해 참여하는 모든 사람

    * 보통 최대 인원은 7~8명이 적당

 

+ 스크럼 개발 프로세스


출처 : https://www.edureka.co/blog/agile-scrum-tutorial/
- 제품 백로그(Product Backlog)

    * 개발에 필요한 요구사항을 우선순위에 따라 나열한 목록

    * 새롭게 도출되는 요구사항으로 인해 지속적 업데이트

    * 작성된 사용자 스토리를 기반으로 릴리즈 계획을 수립

+ 스프린트 계획 회의(Sprint Planning Meeting)

    * 이번 스프린트에서 수행할 작업을 대상으로 단기 일정 수립

    * 처리할 요구사항을 개발자들이 나눠서 작업할 수 있도록 태스크라는 작업 단위로 나눠 개발자 별로 수행할 작업 목록인 스프린트 백로그(Sprint Backlog) 작성

+ 스프린트(Sprint)

    * 실제 개발 작업을 진행하는 과정

    * 스프린트 백로그에 작성된 태스크를 대상으로 작업 시간이나 양을 추정한 후 개발 담당자에게 할당

    * 태스크를 할당할 때는 개발자가 원하는 태스트를 직접 선별하여 담당할 수 있도록 하는 것이 좋음

    * 할당된 태스크는 할 일, 진행 중, 완료의 상태를 가짐

+ 일일 스크럼 회의(Daliy Scrum Meeting)

    * 모든 팀원이 매일 약속된 시간에 짧은 시간동안 진행 상황을 점검

    * 스크럼 마스터는 발견된 장애 요소를 해결할 수 있도록 도와줌

    * 남은 작업 시간은 소멸 차트에 표시

+ 스프린트 검토 회의(Spring Review)

    * 부분 또는 완성 제품이 요구사항에 잘 부합되는지 사용자가 포함된 참석자 앞에서 테스트 수행

+ 스프린트 회고(Sprint Retrospective)

    * 스프린트가 끝나고 정해놓은 규칙을 잘 준수했는지, 개선할 점은 없는지 등을 점검하고 수행

<br/> 

## 3. XP(eXtreme Programming) 기법   

> ### XP의 개요

- 수시로 발생하는 고객의 요구사항에 유연하게 대응하기 위해 고객의 참여와 개발 과정의 반복을 극대화하여 개발 생산성을 향상시키는 기법

- 짧고 반복적인 개발주기, 단순한 설계, 고객의 적극적인 참여를 통해 빠르게 개발하는 것이 목적

- 릴리즈의 기간을 짧게 반복하면서 요구사항 반영에 대한 가시성을 높임

- XP의 5가지 핵심 가치 : 의사소통, 단순성, 용기, 존중, 피드백

<br/>

> ### XP 개발 프로세스


+ 사용자 스토리

    * 고객의 요구사항을 간단한 시나리오로 표현

+ 릴리즈 계획 수립

    * 몇 개의 스토리가 적용되어 부분적으로 기능이 완료된 제품을 제공하는 것에 대한 계획 수립

+ 스파이크

    * 요구사항의 신뢰성을 높이고 기술 문제에 대한 위험을 감소시키기 위해 별도로 만드는 프로그램

+ 이터레이션

    * 하나의 릴리즈를 더 세분화하여 한 단위

+ 승인 검사

    * 하나의 이터레이션 안에서 계획된 릴리즈 단위의 부분 완료 제품이 구현되면 수행하는 테스트

    * 사용자 스토리 작성 시 함께 기재한 테스트 사항에 대해 고객이 직접 수행

+ 소규모 릴리즈

    * 고객의 반응을 기능별로 확인하고 고객의 요구사항에 유연하게 대응

    * 진행된 이터레이션이 모두 완료되면 고객에 의한 최종 테스트 수행 후 최종 결과물을 고객에게 전달

<br/> 

> ### XP의 주요 실천 방법

- Pair Programming : 다른 사람과 함께 프로그래밍 수행

- Test-Driven Development : 실제 코드 작성 전 테스트 케이스를 먼저 작성하여 무엇을 해야할지 파악

- Whole Team : 개발에 참여하는 모든 구성원은 각기 역할이 있어 책임을 다해야 함

- Continuous Intergration : 모듈 단위로 나눠 개발한 코드는 하나의 작업이 마무리되면 지속적으로 통합

- Design Improvement / Refactoring : 프로그램 기능의 변경 없이 시스템을 재구성

- Small Release : 릴리즈 기간을 짧게 하여 고객의 요구 변화에 신속하게 대응

<br/> 

## 4. 현행 시스템 파악

> ### 현행 시스템 파악 절차


+ 1단계

    * 시스템 구성 파악 : 조직의 업무를 담당하는 기간 업무와 이를 지원하는 업무로 구분하여 나타낸 구성을 파악

    * 시스템 기능 파악 : 현재 제공하는 기능들을 주요, 하부, 세부 기능으로 구분하여 계층형으로 표시

    * 시스템 인터페이스 파악 : 주고받는 데이터의 종류, 형식, 프로토콜, 연계 유형, 주기 등을 명시

+ 2단계

    * 아키텍쳐 구성 파악 : 어떠한 기술 요소들이 사용되는지 최상위 수준에서 계층별로 표현한 구성 파악

    * 소프트웨어 구성 파악 : 업무 처리를 위해 설치되어 있는 소프트웨어의 제품명, 용도, 라이선스 적용 방식 등을 명시

+ 3단계

    * 하드웨어 구성 파악 : 단위 업무 시스템들이 운용되는 서버의 주요 사양과 수량 및 이중화 적용 여부 명시

    * 네트워크 구성 파악 : 서버의 위치, 서버 간의 네트워크 연결 방식을 네트워크 구성도로 작성

<br/>

## 5. 개발 기술 환경 파악
> ### 개발 기술 환경의 정의

- 개발하고자 하는 소프트웨어와 관련된 O/S, DBMS, Middle Ware 등을 선정할 때 고려해야 할 사항을 기술하고 오픈 소스 사용 시 주의해야 할 내용을 제시

<br/>

> ### 운영체제(Operating System)

- 컴퓨터 시스템 자원을 효율적으로 관리하여 사용자가 컴퓨터를 편리하고 사용할 수 있도록 환경을 제공하는 소프트웨어

- 요구사항 식별 시 고려사항 : 가용성, 성능, 기술 지원, 주변 기기, 구축 비용

<br/>

> ### 데이터베이스 관리 시스템(DBMS)

- 사용자와 데이터베이스 사이에서 사용자의 요구에 따라 정보를 생성해주고 관리해주는 소프트웨어

- 요구사항 식별 시 고려사항 : 가용성, 성능, 기술 지원, 상호 호환성, 구축 비용

<br/>

> ### 웹 애플리케이션 서버(WAS)

- 사용자의 요구에 따라 변하는 동적인 컨텐츠를 처리하기 위해 사용되는 미들웨어

- 요구사항 식별 시 고려사항 : 가용성, 성능, 기술 지원, 구축 비용

<br/>

> ### 오픈 소스(Open Source)

- 누구나 제한없이 사용할 수 있도록 소스 코드를 공개한 것

- 라이선스를 만족하는 소프트웨어

- 요구사항 식별 시 고려사항 : 라이선스의 종류, 사용자의 수, 기술의 지속 가능성

<br/>

## 5. 요구사항 정의
> ### 요구사항의 개념과 특징

- 소프트웨어가 어떤 문제를 해결하기 위해 제공하는 서비스에 대한 설명과 정상적으로 운영되는데 필요한 제약조건 등

- 요구사항이 제대로 정의되어야 이를 토대로 이후 과정의 목표와 계획의 수립이 가능

<br/>

> ### 요구사항의 유형

+ 기술하는 내용에 따른 분류

    * 기능 요구사항 : 시스템이 무엇을 하고 어떤 기능을 하는지에 대한 사항
    
    * 비기능 요구사항 : 품질이나 제약사항에 대한 사항

+ 기술 관점과 대상의 범위에 따른 분류

    * 사용자 요구사항 : 사용자의 관점에서 본 시스템이 제공해야 할 사항

    * 시스템 요구사항 : 개발자의 관점에서 본 시스템 전체가 사용자와 다른 시스템에 제공해야 할 사항

<br/>

> ### 요구사항 개발 프로세스

+ 요구사항 도출

    * 요구사항이 어디에 있고 어떻게 수집할지 식별하고 이해하는 과정

    * 인터뷰, 설문, 브레인스토밍, 워크샵, 프로토타이핑, 유스 케이스 등

    * 브레인스토밍 : 3인 이상이 자유롭게 아이디어를 산출해 내는 방법

    * 유스케이스 : 사용자의 요구사항을 기능 단위로 표현

+ 요구사항 분석

    * 개발 대상에 대한 사용자의 요구사항 중 명확하지 않거나 모호하여 이해되지 않는 부분을 발견하고 걸러내는 과정

+ 요구사항 명세

    * 요구사항을 분석한 후 승인될 수 있도록 문서화하는 과정

    * 소프트웨어 요구사항 명세서 : 소프트웨어가 반드시 제공해야 하는 기능, 특징, 제약조건을 명시

+ 요구사항 확인

    * 개발 자원을 요구사항에 할당하기 전에 요구사항 명세서가 정확하게 작성되었는지 검토하는 과정

<br/>

## 6. 요구사항 분석 기법
> ### 요구사항 분류

+ 요구사항을 명확히 확인할 수 있도록 정해진 기준으로 분류

    * 기능/비기능 요구사항 분류

    * 제품/과정으로 분류

    * 우선순위로 분류

<br/>

> ### 개념 모델링

- 요구사항의 현실 세계의 상황을 단순화하여 개념적으로 표현하는 과정 

- 실세계 문제에 대한 모델링은 요구사항 분석의 핵심

- 개체와 개체 간의 관계 및 종속성을 반영

- 개념 모델은 다양하게 표현

- 주로 UML을 사용
<br/>

> ### 요구사항 할당

- 요구사항을 만족시키기 위한 구성 요소를 식별

<br/> 

> ### 요구사항 협상

- 요구사항이 서로 충돌될 경우 해결하는 과정

- 적절한 기준점을 찾아 합의하는게 좋음

- 서로 충돌하는 경우 우선순위를 부여하면 해결에 도움이 됨

<br/>

> ### 정형 분석

- 구문과 의미를 같은 정형화된 언어를 이용해 요구사항을 수학적 기호로 표현하고 분석하는 과정

<br/>

## 7. 요구사항 확인 기법
> ### 요구사항 검토

- 문서화된 요구사항을 훑어보면서 확인하는 과정

- 시스템 정의서, 시스템 사양서, 소프트웨어 요구사항 명세서 등을 완성한 시점에 이루어짐

<br/>

> ### 프로토타이핑

- 초기 도출된 요구사항을 토대로 프로토타입을 만든 후 개발이 진행되는 동안 도출되는 요구사항을 반영하면서 지속적으로 프로토타입을 재작성하는 과정

+ 장점

    * 빠르고 반복되는 제작을 할 수 있어 발전된 결과물을 얻을 수 있음

    * 최종 시스템을 완성하기 전에 추가 또는 변경된 요구사항에 대한 피드백 가능

+ 단점

    * 사용자의 관심이 핵심에서 벗어나 프로토타입 제작에만 집중될 수 있음

    * 지속적이고 반복적인 개선에 대한 비용이 부담될 수 있음

<br/>

> ### 모델 검증

- 요구사항 분석 단계에서 개발된 모델이 요구사항을 충족하는지 검증하는 과정

<br/> 

> ### 인수 테스트

- 사용자가 실제로 사용될 환경에서 요구사항이 모두 충족되는지 사용자 입장에서 확인하는 과정

<br/>

## 8. UML(Unified Modeling Language)
> ### UML의 개요

- 시스템 개발 과정에서 시스템 개발자와 고객 또는 개발자 상호 간의 의사소통이 원활하게 이루어지도록 표준화한 객체지향 모델링 언어

- 객체지향 방법론의 장점을 통합하였으며 OMG(Object Management Group)에서 표준으로 지정

- 구성 요소 : 사물, 관계, 다이어그램

<br/> 

> ### 사물

- 모델을 구성하는 가장 중요한 기본 요소

- 다이어그램 안에서 관계가 형성될 수 있는 대상

+ 구조 사물

    * 시스템의 개념적, 물리적 요소 표현

    * 클래스, 유스케이스, 컴포넌트, 노드 등

+ 행동 사물

    * 시간과 공간에 따른 요소들의 행위 표현

    * 상호작용, 상태 머신 등

+ 그룹 사물

    * 요소들의 그룹으로 묶어서 표현

    * 패키지

+ 주해 사물

    * 부가적인 설명이나 제약조건 등 표현

    * 노트

<br/>

> ### 관계

- 사물과 사물 사이의 연관성 표현

+ 연관 관계

    * 2개 이상의 사물이 서로 관련되어 있음을 표현

    * 실선과 화살표로 연결하여 표현하지만 양방향 관계의 경우 화살표 없이 실선으로 연결하여 표현



+ 사람과 집이 1:1 관계

   * 교수는 1명 이상의 학생을 가르치고 학생은 1명 이상의 교수에게 가르침을 받음

+ 집합 관계

    * 하나의 사물이 다른 사물에 포함되어 있는 관계

    * 부분(포함되는 쪽)에서 전체(포함하는 쪽)로 속이 빈 마름모를 연결하여 표현


+ 프린터는 컴퓨터에 연결해서 사용할 수 있음

   - 포함 관계

    * 집합 관계의 특수한 형태로 포함하는 사물의 변화가 포함되는 사물에게 영향을 미치는 관계

    * 부분(포함되는 쪽)에서 전체(포함하는 쪽)로 속이 채워진 마름모를 연결하여 표현


+ 문을 열 수 있는 키는 하나이고 해당 키로 다른 문은 열 수 없음
   - 의존 관계

    * 사물 사이에 연관은 있으나 필요에 의해서 서로에게 영향을 주는 짧은 시간 동안만 연관을 유지하는 관계

    * 영향을 주는 사물이 영향을 받는 사물 쪽으로 점선 화살표 연결


+ 출석률은 학점을 낼 때 영향을 미침
   
   - 일반화 관계

    * 하나의 사물이 다른 사물에 비해 일반적인지 구체적인지 표현

    * 구체적인 사물에서 일반적인 사물 쪽으로 속이 빈 화살표를 연결


+ 실체화 관계

    * 사물이 할 수 있거나 해야 하는 기능으로 서로를 그룹화할 수 있는 관계

    * 사물에서 기능 쪽으로 속이 빈 점선 화살표 연결

<br/>

> ### 다이어그램

- 사물과 관계를 도형으로 표현

- 정적 모델링에서는 주로 구조적 다이어그램을 사용하고 동적 모델링에서는 주로 행위 다이어그램 사용

+ 구조적 다이어그램

    * 클래스 다이어그램 : 클래스, 클래스가 가지는 속성, 클래스 사이 관계 표현

    * 객체 다이어그램 : 인스턴스를 특정 시점의 객체와 객체 사이의 관계로 표현

    * 컴포넌트 다이어그램 : 구현 단계에서 사용되며 컴포넌트 간의 관계나 인터페이스를 표현

    * 배치 다이어그램 : 구현단계에서 사용되며 결과물, 프로세스, 컴포넌트 등 물리적 요소들의 위치 표현

    * 복합체 구조 다이어그램 : 복잡한 구조를 가지는 클래스 혹은 컴포넌트의 내부 구조 표현
    
    * 패키지 다이어그램 : 유스케이스나 클래스 등의 모델 요소들을 그룹화한 패키지들의 관계 표현

+ 행위 다이어그램

    * 유스케이스 다이어그램 : 사용자의 요구를 분석하여 기능 모델링 작업에 사용됨

    * 시퀀스 다이어그램 : 상호 작용하는 시스템이나 객체들이 주고받는 메시지 표현

    * 커뮤니케이션 다이어그램 : 객체들이 주고받는 메시지를 표현할 뿐 아니라 객체들 간의 연관까지 표현

    * 상태 다이어그램 : 하나의 객체가 자신이 속한 클래스의 상태 변화 혹은 다른 객체와의 상호 작용에 따라 어떻게 변화하는지 표현

    * 활동 다이어그램 : 객체의 처리 로직이나 조건에 따른 처리의 흐름을 순서에 따라 표현

    * 상호작용 개요 다이어그램 : 상호작용 다이어그램 간의 제어 흐름 표현

    * 타이밍 다이어그램 : 객체 상태 변화와 시간 제약을 명시적으로 표현

</details>

### 2. 화면 설계
<details markdown= "2">
<summary> 화면 설계 정리</summary>
   
## 1. 사용자 인터페이스(User Interface)
> ### 사용자 인터페이스의 개요

- 사용자와 시스템 간의 상호작용을 원활하게 도와주는 장치나 소프트웨어

- 사용자 인터페에스의 3가지 분야

    * 정보 제공과 전달을 위한 물리적 제어에 관한 분야

    * 콘텐츠의 상세적인 표현과 전체적인 구성에 관한 분야

    * 모든 사용자가 편리하고 간편하게 사용하도록 하는 기능에 관한 분야

 

> ###사용자 인터페이스의 구분

- CLI(Command Line Interface) : 명령과 출력이 텍스트 형태로 이루어지는 인터페이스

- GUI(Graphic User Interface) : 아이콘이나 메뉴를 마우스로 선택하여 작업을 수행하는 인터페이스

- NUI(Natural User Interface) : 말이나 행동으로 조작하는 인터페이스

 

> ### 사용자 인터페이스의 기본 원칙

- 직관성, 유효성, 학습성, 유연성

 

> ### 사용자 인터페이스의 설계 지침

- 사용자 중심, 일관성, 단순성, 결과 예측 가능, 가시성, 표준화, 접근성, 명확성, 오류 발생 해결

 
## 2. UI 표준 및 지침
> ### UI 표준 및 지침의 개요

- UI 표준과 지침을 토대로 기술의 중립성(표준), 보편적 표현 보장성(접근성), 기능의 호환성이 고려되었는지 확인


> ### 한국형 웹 콘텐츠 접근성 지침(KWCAG)

- 장애인과 비장애인이 동등하게 접근할 수 있는 웹 콘텐츠 제작의 방법 제시

- 웹 콘텐츠 접근성 지침 준수를 위한 고려사항

- 네비게이션 : 사용자가 사이트에서 원하는 정보를 빠르게 찾도록 도와주는 장치 

> ### 전자정보 웹 표준 준수 지침

- 정부기관의 홈페이지 구축시 반영해야 할 최소한의 규약

- 전자정부 웹 표준 준수 지침 사항

    * 내용의 문법 준수

    * 내용과 표현의 분리

    * 동작의 기술 중립성 보장

    * 플러그인의 호환성

    * 콘텐츠의 보편적 표현

    * 운영체제에 독립적인 콘텐츠 제공

    * 부가 기능의 호환성 확보

    * 다양한 프로그램 제공

## 3. UI 설계 도구
> ### UI 설계 도구

- 사용자의 요구사항에 맞게 UI를 설계할 때 사용하는 도구


> ### 와이어프레임

- 기획 초기 단계에서 제작하는 것으로 페이지에 대한 대략적인 레이아웃이나 UI 요소 등에 대한 뼈대를 설계

- 와이어프레임 툴 : 손그림, 파워포인트, 키노트, 스케치, 일러스트, 포토샵 등

> ### 키노트
> ### 목업

- 와이어프레임보다 좀 더 실제 화면과 유사하게 만드는 정적인 형태의 모형

- 목업 툴 : 파워 목업, 발사믹 목업 등


출처 : https://www.mockupworld.co/free/category/iphone/
 

> ### 스토리보드

- 와이어프레임에 콘텐츠에 대한 설명이나 페이지 간 이동 흐름 등을 추가한 문서

- 디자이너와 개발자가 최종적으로 참고하는 작업 지침서

- 서비스 구축을 위한 모든 정보가 담겨 있어야 함

- 스토리보드 툴 : 파워포인트, 키노트, 스케치, Axure 등


출처 : https://m.blog.naver.com/durandot/100205321229
 

> ### 프로토타입

- 와이어프레임이나 스토리보드 등에 인터랙션을 적용해 실제 구현된 것처럼 테스트가 가능한 동적인 형태의 모형

- 작성 방법에 따라 페이퍼/디지털 프로토타입으로 나눔

- 프로토타입 툴 : HTML/CSS, Axure, Flinto, 네이버 포로토나우, 카카오 오븐 등


출처 : https://ovenapp.io/
 

> ### 유스케이스

- 사용자 측면에서의 요구사항으로 사용자가 원하는 목표를 달성하기 위해 수행할 내용 기술


출처 : http://www.hanbit.co.kr/media/channel/view.html?cms_code=CMS8900361225&cate_cd=
 

## 4. UI 요구사항 확인
> ### UI 요구사항 확인의 개요

- 새로 개발할 시스템에 적용할 UI 관련 요구사항을 조사해서 작성하는 단계


> ### 목표 정의

- 사용자들을 대상으로 인터뷰를 하고 사용자들의 의견이 수렴된 비즈니스 요구사항을 정의

- 인터뷰 진행 시 유의 사항

    * 사업적, 기술적 요구사항을 명확히 이해

    * 가능한 개별적인 진행

    * 한 시간을 넘기지 않는게 좋음

    * 사용자 리서치 시작 전 해야 함 

> ### 활동 사항 정의

- 조사한 요구사항을 토대로 앞으로 해야 할 활동 사항을 정의

- 기술의 발전 가능성을 파악하고 UI 디자인의 방향 제시

 

> ### UI 요구사항 작성

- 여러 경로로 수집된 사용자의 요구사항을 검토하고 분석하여 UI 개발 목적에 맞게 작성해야 함

- 실 사용자 중심으로 작성

- 여러 사람의 인터뷰를 통해 다양한 의견을 수렴하여 작성

 

> ### 요구사항 요소 확인

- 파악된 요구사항 요소의 종류와 각각의 표현 방식 등을 검토

- 요구사항 요소 : 데이터 요구, 기능 요구, 제품/서비스의 품질, 제약 사항

 

> ### 정황 시나리오 작성

- 사용자의 요구사항을 도출하기 위해 작성

- 사용자가 목표를 달성하기 위해 수행하는 방법을 순차적으로 묘사

- 개발하는 서비스의 모습을 상상하는 첫번째 단계로 사용자 관점에서 시나리오를 작성해야 함

 

> ### 요구사항 작성

- 정황 시나리오를 토대로 작성
 
 
## 5. 품질 요구사항
> ### 품질 요구사항

- 소프트웨어의 기능, 성능, 만족도 등 소프트웨어에 대한 요구사항이 얼마나 충족하는 가를 나타내는 것

- ISO/IEC 9126 : 국제 표준으로 소프트웨어 품질 특성과 평가를 위한 표준 지침



 

## 6. UI 프로토타입 제작 및 검토
> ### UI 프로토타입의 개요

- 사용자 요구사항을 기반으로 실제 동작하는 것처럼 만든 동적인 형태의 모형

- 테스트 가능

- 최대한 간단하게 만들어야 함

- 일부 핵심적인 기능을 제공하지만 최종 제품의 작동 방식을 이해시켜줄 기능은 반드시 포함되어야 함

- 실제 사용자를 대상으로 테스트해야 함

 

> ### UI 프로토타입의 장단점

- 장점

    * 사용자를 설득, 이해시키기 쉬움

    * 요구사항을 점검하며 혼선은 예방하므로써 개발 시간을 줄일 수 있음

    * 사전 오류 검출 가능

- 단점

    * 프로토타입 제작으로 인해 작업 시간을 증가시킬 수 있음

    * 필요 이상의 자원 소모 가능

    * 부분적으로 작업 시 중요한 작업이 생략될 수 있음

 

> ### 프로토타이핑의 종류

- 페이퍼 프로토타입

    * 아날로그 방법(스케치, 글, 그림) 등을 이용하여 직접 작성

    * 제작 기간이 짧고, 제작 비용이 적을 경우, 업무 회의가 빠를 경우, 급하게 만들어야 하는 경우 사용

- 디지털 프로토타입

    * 프로그램을 사용하여 작성

    * 재사용이 필요하거나, 완성 제품과 비슷하게 만들어야 하거나, 숙련된 전문가가 있을 때 사용

 

> ### UI 프로토타입 계획 및 작성 시 고려사항

- 계획 시 고려사항

    * 일정은 아키텍처가 확정 ~ 프로젝트 실제 분석 작업 완료 사이에 진행해야 함

    * 프로토타입을 통해서 발생하는 이슈를 모두 취합하여 해결 방법을 제시

    * 진행하면서 가장 많은 시간이 소요된 구간을 찾아 그 원인을 분석하여 해결 방법을 제시

- 작성 시 고려사항

    * 프로젝트의 상황을 감안해서 프로토타입의 범위를 정해야 함

    * 완성된 프로토타입이 실제 개발에 참조될 수 있는 지 확인

 

> ### UI 프로토타입 제작 단계
<img src="/다운로드/ui 프로토타입 제작 단계.png" width="40%" height="30%" title="ui prototype" alt="ui prototype "></img>

## 6. UI 설계서 작성
> #### UI 설계서의 개요

- 사용자의 요구사항을 바탕으로 UI 설계를 구체화하여 작성하는 문서

 
> ### UI 설계서 작성 순서


 

## 7. UI 상세 설계
> ### UI 시나리오 문서의 개요

- UI 설계서를 바탕으로 실제 설계 및 구현을 위해 모든 화면에 대한 자세한 설계를 진행

- 시나리오를 작성해야 함

- 사용자 인터페이스의 기능 구조, 대표 화면, 화면 간 상호작용의 흐름, 다양한 상황에서의 예외 처리 등을 문서로 정리

 

> ### UI 시나리오 문서 작성 원칙

- 개발자가 전체 UI 기능과 작동 방식을 이해할 수 있도록 구체적으로 작성

- UI 요소와 인터랙션을 일반 규칙으로 정의

- 인터랙션의 흐름을 정의하고 인터랙션의 순서, 분기, 조건, 반복 등을 명시

- 예외 상황에 대비한 다양한 케이스를 정의


출처 : https://m.blog.naver.com/durandot/100205321229
 

> ### UI 시나리오 문서 작성을 위한 일반 규칙

- 주요 키의 위치와 기능

    * 모든 화면에 공통적으로 배치되는 주요 키의 위치와 기능을 설명

    * 여러 화면 간 일관성 보장

- 공통 UI 요소

    * UI 요소를 언제 어떤 형태로 사용할 지 정의

    * 사용자의 조작에 대한 반응하는지에 대한 흐름을 설명

- 기본 스크린 레이아웃

    * 모든 화면에 공통적으로 나타나는 요소들에 대한 위치와 속성을 정의

- 기본 인터랙션 규칙

    * 터치 제스처 등에 공통적으로 사용되는 조작 방법과 화면 전환 효과 등을 기술

- 공통 단위 태스크 흐름

    * 많은 기능들에 공통적으로 사용되는 삭제, 검색, 매너 모드 상태 등에 대한 인터랙션 흐름 설명

- 케이스 문서

    * 다양한 상황에서 공통적으로 적용되는 시스템의 동작을 정의한 문서

 

> ### UI 시나리오 문서의 요건

- 완전성 : 누락되지 않도록 상세히 기술

- 일관성 : 서비스의 목표, 요구사항, UI 스타일이 모두 일관성을 유지해야 함

- 이해성 : 누구나 쉽게 이해할 수 있도록 설명

- 가독성 : 표준화된 템플릿을 활용하여 읽기 쉽도록 해야 함

- 수정 용이성 : 시나리오의 수정, 개선이 쉬워야 함

- 추적 용이성 : 변경 사항이 언제 어떻게 왜 발생했는지 쉽게 추적할 수 있어야 함

 

## 8. HCI / UX / 감성공학
> ### HCI(Human Computer Interaction or Interface)

- 사람이 시스템을 보다 편리하고 안전하게 사용할 수 있도록 개발, 연구하는 학문

- 최종 목표는 시스템을 사용하는데 있어 최적의 사용자 경험을 만드는 것

 

> ### UX(User Experience)

- 사용자가 시스템이나 서비스를 이용하면서 느끼고 생각하게 되는 총제적인 경험

 

> ### 감성 공학

- 제품이나 작업환경을 사용자의 감성에 맞도록 설계 제작하는 기술
</details>

### 3. 애플리케이션 설계
<details markdown= "2">
<summary> 애플리케이션 설계 정리</summary>
</details>

### 4. 인터페이스 설계
<details markdown= "2">
<summary> 인터페이스 설계 정리</summary>
</details>
