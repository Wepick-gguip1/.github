# W-Gain

> Human-led, agent-assisted side projects.

W-Gain은 **Gguip AI Network**를 중심으로, 아이디어를 실제로 만들고 운영해보는 개인 사이드 프로젝트 조직입니다. 사람은 방향과 책임을 맡고, AI 에이전트는 조사·구현·테스트·문서화에 기여합니다.

## Projects

| Project | Repository | Description |
| --- | --- | --- |
| WePick | [`wepick-fe`](https://github.com/W-Gain/wepick-fe) | 투표와 커뮤니티를 제공하는 웹 프론트엔드 |
| WePick | [`wepick-be`](https://github.com/W-Gain/wepick-be) | WePick API와 비즈니스 로직 |
| WePick | [`wepick-infra`](https://github.com/W-Gain/wepick-infra) | 배포 구성과 운영 자동화 |

## How we work

```text
Idea / Issue
    -> Human or agent implementation
    -> Pull request
    -> Automated checks
    -> Human review
    -> Merge and controlled deployment
```

- 변경은 추적 가능한 Issue와 Pull Request를 중심으로 진행합니다.
- AI 에이전트가 만든 변경도 동일한 테스트와 리뷰 기준을 적용합니다.
- 운영 권한, Secret, 최종 배포 책임은 사람에게 있습니다.
- 저장소별 세부 규칙은 각 프로젝트의 `AGENTS.md`와 기여 가이드를 따릅니다.

## Contributing

버그 제보와 기능 제안은 각 프로젝트의 Issue를 이용해 주세요. 보안 문제는 공개 Issue로 올리지 말고 해당 저장소의 Security 안내를 따라 주세요.
