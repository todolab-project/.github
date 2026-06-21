# ToDoLab

**일정을 기록하는 도구를 넘어, 지속 가능한 일정 관리 경험을 설계합니다.**

ToDoLab은 백엔드와 모바일 클라이언트를 함께 발전시키며 제품 설계, 도메인 모델링, API 구조, 사용자 경험을 탐구하는 개인 개발 프로젝트입니다. 단순한 기능 구현보다 명확한 책임 분리와 검증 가능한 설계를 지향합니다.

## 프로젝트 구성

| 저장소 | 역할 | 주요 기술 |
| --- | --- | --- |
| [ToDoLab-backend](https://github.com/todolab-project/ToDoLab-backend) | 도메인 로직, API, 배치 및 서버 애플리케이션 | Java 25, Spring Boot 4, Spring MVC, Virtual Threads, JPA, QueryDSL, MySQL |
| [todolab-mobile](https://github.com/todolab-project/todolab-mobile) | iOS·Android·Web을 아우르는 모바일 클라이언트 | React Native, Expo, TypeScript |

## 개발 원칙

- 도메인의 의도가 드러나는 구조와 이름을 사용합니다.
- 단순한 구현을 우선하되, 확장 지점을 명확하게 설계합니다.
- 테스트를 통해 핵심 동작과 기술적 의사결정을 검증합니다.
- 백엔드와 클라이언트 사이의 계약을 일관되게 관리합니다.
- 기술 선택의 이유와 변화 과정을 문서로 남깁니다.

## 현재 상태

ToDoLab은 현재 활발히 개발 중입니다. 백엔드 기반을 안정화하고 모바일 경험을 확장하는 단계에 있습니다.
