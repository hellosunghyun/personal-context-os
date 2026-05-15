# GPTs와 챗봇으로 확장하기

[← 이전](08_team_sharing.md) | [목차](../SUMMARY.md)

## 이 페이지에서 알게 되는 것

완성된 사용 설명서를 반복적으로 쓰기 위해 GPTs나 챗봇으로 확장하는 방법을 이해합니다.

처음 사용 설명서를 만드는 중이라면 아직 만들 필요가 없습니다. 먼저 `active_context.md`와 공유용 문서가 실제로 쓸 만한지 확인하세요.

---

## GPTs란?

GPTs는 특정 목적에 맞게 지시문, 지식 파일, 기능을 설정해 사용하는 맞춤형 ChatGPT입니다.

이 가이드에서는 GPTs를 필수로 쓰지 않습니다. 하지만 반복적으로 같은 맥락을 제공해야 한다면 유용할 수 있습니다.

---

## 언제 GPTs로 만들면 좋은가

```text
매번 active_context.md를 첨부하기 귀찮다.
나만의 글쓰기 보조 GPT를 만들고 싶다.
피드백 소화, 아이디어 정리, 커리어 문서 작성처럼 반복 작업이 있다.
팀에서 공통 워크북 진행자를 만들고 싶다.
```

---

## 넣으면 좋은 파일

```text
active_context.md
answer_taste_log.md
team_share_one_pager.md
prompts/00_project_context.md의 핵심 규칙
```

full_manual.md 전체를 넣는 것은 항상 최선이 아닙니다. 너무 길고 민감할 수 있습니다.

---

## 어디에 무엇을 넣나요?

GPTs나 챗봇으로 확장할 때는 파일을 한곳에 다 넣기보다 역할을 나눕니다. 제품 화면 이름은 바뀔 수 있지만, 개념은 아래처럼 맞추면 됩니다.

```text
Instructions:
- 이 GPT가 해야 할 일
- 답변 원칙
- 금지할 행동
- 공개 범위 확인 규칙

Knowledge 또는 참고 파일:
- active_context.md
- answer_taste_log.md 중 민감하지 않은 요약
- team_share_one_pager.md

Conversation starters:
- 실제로 자주 묻는 요청 3~5개

Capabilities 또는 tools:
- 웹 검색이 필요한 작업인지
- 파일 분석이 필요한 작업인지
- 이미지나 코드 기능이 필요한지
```

처음부터 GPTs로 만들 필요는 없습니다. `active_context.md`를 일반 채팅에 몇 번 붙여 써보고, 반복해서 쓸 만하다는 확신이 생긴 뒤에 옮깁니다.

---

## GPTs 지시문 예시

```text
이 GPT는 특정 사용자의 active_context.md와 answer_taste_log.md를 참고해 답변한다.
목표는 가장 화려한 답변이 아니라, 사용자가 납득하고 바로 쓸 수 있는 답변을 만드는 것이다.
사용자가 말하지 않은 경험은 만들지 않는다.
필요한 정보가 부족하면 먼저 질문한다.
민감한 내용은 공개용 표현으로 완화한다.
```

---

## 주의

```text
GPTs는 문서를 대신 읽어주는 인터페이스이지, 나를 완벽히 아는 존재가 아니다.
민감한 파일은 넣지 않는다.
업데이트한 active_context를 주기적으로 교체한다.
파일을 교체했으면 예전 파일이 남아 있지 않은지 확인한다.
GPT가 내 말을 과하게 업그레이드하면 answer_taste_log에 나쁜 예시로 남긴다.
```

---

## 다음 행동

필수 흐름을 아직 시작하지 않았다면 [일직선 실행 흐름](../workflow/00_linear_flow.md)으로 돌아갑니다. 이미 문서를 완성했다면 [첫 생성 완료](../FINISH.md)에서 품질 테스트와 업데이트 루틴을 확인합니다.

돌아가기: [목차](../SUMMARY.md)
