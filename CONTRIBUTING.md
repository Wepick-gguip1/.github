# Contributing to W-Gain projects

W-Gain은 사람과 AI 에이전트의 기여를 같은 품질 기준으로 검토합니다.

## Before starting

1. 대상 저장소의 `README.md`, `CONTRIBUTING.md`, `AGENTS.md`를 확인합니다.
2. 기존 Issue와 Pull Request에 같은 작업이 없는지 검색합니다.
3. 동작 변경은 먼저 Issue에 목적과 완료 조건을 적습니다.

## Branch and Pull Request

- 브랜치 이름은 `feat/<topic>`, `fix/<topic>`, `docs/<topic>`, `agent/<issue>-<topic>` 형식을 권장합니다.
- 한 Pull Request에는 하나의 목적만 담습니다.
- 관련 Issue, 검증 결과, 위험 요소와 롤백 방법을 Pull Request에 기록합니다.
- 자동 검사가 통과하기 전에는 병합하지 않습니다.
- AI 에이전트가 실질적인 변경을 만들었다면 Pull Request에 사용 사실과 사람이 검토한 범위를 표시합니다.

## Quality and safety

- 저장소별 테스트와 정적 검사를 실행합니다.
- Secret, 토큰, 개인 서버 주소, 운영 데이터는 커밋하지 않습니다.
- 새 의존성은 필요성과 유지보수 상태를 확인합니다.
- 데이터 마이그레이션과 배포 변경은 복구 절차를 함께 준비합니다.

## Conduct

명확하고 존중하는 방식으로 의견을 교환하고, 사람이나 도구가 아니라 코드와 근거를 중심으로 리뷰합니다.
