# START HERE: 처음 15분에 할 일

[목차](SUMMARY.md) | [다음 →](workflow/00_linear_flow.md)

이 문서는 처음 보는 사람이 **지금 당장 무엇을 해야 하는지** 알려주는 시작 페이지입니다.

---

## 이 가이드로 무엇을 만들게 되나요?

첫 번째 목표는 나에 대한 세 가지 핵심 문서를 만드는 것입니다.

```text
1. full_manual.md
   나에 대한 전체 사용 설명서. 본인용 원본.

2. active_context.md
   LLM에게 자주 첨부할 짧은 핵심 맥락 파일.

3. team_share_one_pager.md
   팀원이나 가까운 협업자에게 공유할 수 있는 1페이지 요약.
```

처음부터 완벽한 문서를 만들 필요는 없습니다. 먼저 원재료를 모으고, 그다음 파트별로 초안을 만든 뒤 합칩니다.

`public_profile.md`, `update_plan.md`, GPTs/챗봇 확장, 월간 업데이트는 **완성 후에 필요할 때** 다룹니다.

이 가이드는 최신 기능을 모두 쓰는 법이 아니라, 지금 쓰고 있는 수동 맥락 정리 방식을 문서화한 것입니다. 기능이 바뀌어도 원자료, 근거, 공개 범위, 저자성 검수는 남아야 합니다.

---

## 15분 버전

시간이 거의 없다면 이것만 하세요.

1. `outputs/` 폴더를 만든다.
2. [templates/answer_log.md](templates/answer_log.md)를 복사해 `outputs/01_answer_log.md`로 저장한다.
3. [questions/00_how_to_use_questions.md](questions/00_how_to_use_questions.md)를 읽는다.
4. [questions/01_identity.md](questions/01_identity.md)의 1번부터 5번까지만 답한다.
5. 답변을 ChatGPT에 붙여넣고 아래처럼 말한다.

```text
아래는 나에 대한 사용 설명서를 만들기 위한 초기 답변이다.
아직 부족한 내용이 많다.
이 답변을 바탕으로 추가로 물어볼 질문 10개를 만들어줘.
내 답변을 추정해서 채우지 말고, 질문만 만들어줘.
```

이렇게 하면 최소한 시작할 수 있습니다.

---

## 추천 버전

제대로 하려면 아래 순서로 진행합니다.

1. [workflow/01_setup_workspace.md](workflow/01_setup_workspace.md) 작업 공간 만들기
2. [workflow/02_collect_context.md](workflow/02_collect_context.md) 선택 자료 모으기
3. [workflow/03_answer_100_questions.md](workflow/03_answer_100_questions.md) 100문 100답 진행하기
4. [workflow/04_round1_interview.md](workflow/04_round1_interview.md) 1차 인터뷰 진행하기
5. [workflow/05_generate_followups.md](workflow/05_generate_followups.md) 추가 질문 만들기
6. [workflow/06_round2_interview.md](workflow/06_round2_interview.md) 2차 인터뷰 진행하기
7. [workflow/07_build_manual.md](workflow/07_build_manual.md) 파트별 최종 문서 초안 만들기
8. [workflow/08_review_and_split.md](workflow/08_review_and_split.md) 초안을 합치고 검수하기
9. [FINISH.md](FINISH.md)에서 첫 생성 완료 상태 확인하기

완성 후 계속 운영할 때만 [workflow/09_update_system.md](workflow/09_update_system.md)를 봅니다.

---

## 지금 하지 않아도 되는 것

아래는 처음 실행할 때 바로 하지 않아도 됩니다.

```text
GPTs나 개인 챗봇 만들기
팀원에게 공유하기
월간 업데이트 루틴 만들기
분기별 품질 테스트 하기
```

이 항목들은 사용 설명서 초안이 나온 뒤에 판단해도 늦지 않습니다.

---

## 텍스트와 음성 중 무엇을 쓰나요?

둘 다 가능합니다.

```text
텍스트가 좋은 경우:
- 생각을 천천히 정리하고 싶다.
- 나중에 그대로 파일로 보관하고 싶다.
- 민감한 내용을 더 조심스럽게 다루고 싶다.

음성이 좋은 경우:
- 머릿속에서 필터링되지 않은 생각을 먼저 꺼내고 싶다.
- 글로 쓰면 너무 오래 걸린다.
- 말하면서 생각이 정리되는 편이다.
```

이 가이드에서는 대화가 필요한 단계마다 **텍스트 방식**과 **음성 방식**을 함께 안내합니다.

---

## 가장 중요한 원칙

```text
GPT 답변이 마음에 든다고 바로 쓰지 않는다.
내가 요청할 때 얼핏 상상했던 방향과 맞는지 확인한다.
너무 멋있지만 내 말처럼 느껴지지 않으면 낮춘다.
좋은 답변이 아니라 내 것이 되는 답변을 남긴다.
정확히 평가하기 어렵다면 좋은 예시와 나쁜 예시만이라도 남긴다.
```

다음 문서: [workflow/00_linear_flow.md](workflow/00_linear_flow.md)
