# 실습 시나리오 - 팀 플레이

```
[버전 3 실습 과제]

목표:
Git을 개인 도구가 아니라 협업용 이력 관리 시스템으로 사용해본다.

규칙:
- main 직접 push 금지
- 모든 변경은 issue 기반
- 모든 커밋 메시지에 issue 번호 포함
- 모든 작업은 feature branch 에서 진행
- PR 후 최소 1명 리뷰
- pull 사용 금지, fetch 후 직접 merge/rebase 판단

과제:
- 팀 저장소 생성
- README, 팀 규칙 문서, 팀원 소개 문서, 주제 문서 작성
- 각자 feature branch 에서 작업
- PR 생성 및 리뷰
- 머지 방식 선택 후 반영
- README 수정 이력 테이블에서 conflict 발생시키고 해결
- fetch + rebase 로 remote 변경 반영
- 마지막에 팀별 git log 그래프 캡처 후 발표
```

### 버전 3 목표

```c
- 협업에서 왜 브랜칭 전략이 필요한지 이해
- 왜 PR과 코드리뷰가 필요한지 체감
- merge / squash / rebase merge 중 무엇을 선택할지 토론 가능
- 충돌은 "이상 상황"이 아니라 협업 구조에서 자연스럽게 생긴다는 걸 경험
- 커밋 컨벤션 / 이슈 / PR 단위가 왜 필요한지 이해
```
