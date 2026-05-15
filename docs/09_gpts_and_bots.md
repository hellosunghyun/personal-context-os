# GPTs와 챗봇으로 확장하기

[← 이전](08_team_sharing.md) | [목차](../SUMMARY.md) | [다음 →](../workflow/00_linear_flow.md)

## 이 페이지에서 알게 되는 것

완성된 사용 설명서를 반복적으로 쓰기 위해 GPTs나 챗봇으로 확장하는 방법을 이해합니다.

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
prompt_rules.md
```

full_manual.md 전체를 넣는 것은 항상 최선이 아닙니다. 너무 길고 민감할 수 있습니다.

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
```

---

## 다음 행동

이제 실제 워크플로를 시작합니다.

다음: [일직선 실행 흐름](../workflow/00_linear_flow.md)
