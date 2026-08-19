# Repository standards

W-Gain의 활성 프로젝트는 다음 최소 기준을 목표로 합니다.

## Required

- 프로젝트 목적과 로컬 실행 방법을 설명하는 `README.md`
- 에이전트 작업 범위와 검증 명령을 담은 `AGENTS.md`
- Pull Request에서 실행되는 테스트 또는 정적 검사
- `main` 직접 변경을 제한하는 Pull Request 중심 흐름
- Secret과 운영 설정을 코드에서 분리하는 방법
- 배포 프로젝트의 Health check와 Rollback 절차

## Recommended

- Issue와 Pull Request의 변경 목적 연결
- 최소 권한의 `GITHUB_TOKEN`과 외부 자격 증명
- 커밋 SHA 또는 명시적 버전으로 식별되는 배포 산출물
- 의존성 및 Secret 노출 자동 점검
- 운영 장애와 복구 결과를 남기는 Runbook 또는 문서

## Agent readiness

에이전트에게 작업을 맡기기 전 다음 항목을 확인합니다.

- 완료 조건이 Issue에 명시되어 있는가?
- 에이전트가 실행할 검증 명령이 재현 가능한가?
- 수정 금지 영역과 사람 승인이 필요한 작업이 문서화되어 있는가?
- 에이전트가 `main`, 조직 설정, Secret 또는 운영 서버에 직접 접근하지 않는가?
