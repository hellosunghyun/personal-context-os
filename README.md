# Personal Context OS Guide

LLM에게 더 좋은 답변을 받기 위한 공개용 워크북입니다.

이 레포의 목표는 **가장 멋진 문장**을 만드는 것이 아닙니다. 목표는 다음에 가깝습니다.

> 내가 어떤 맥락에서 어떤 답변을 납득하는 사람인지 정리하고, LLM이 그 맥락을 참고해 **내가 쓴 것처럼 자연스럽고 바로 쓸 수 있는 답변**을 더 자주 만들게 하는 것.

이 레포는 성격검사, 자기소개서, 프롬프트 모음집이 아닙니다.  
**개인 맥락을 수집하고, 정리하고, 검수하고, 업데이트하는 실행 가이드**입니다.

---

## 지금 당장 할 일

처음이라면 아래 순서만 따라가면 됩니다.

1. [START_HERE.md](START_HERE.md)를 연다.
2. 로컬 폴더나 ChatGPT Project를 하나 만든다.
3. [workflow/01_setup_workspace.md](workflow/01_setup_workspace.md)에 따라 작업 공간을 만든다.
4. [workflow/03_answer_100_questions.md](workflow/03_answer_100_questions.md)에서 100문 100답을 진행한다.
5. [workflow/04_round1_interview.md](workflow/04_round1_interview.md)부터 순서대로 진행한다.

중요합니다. 100문 100답은 최종 문서가 아닙니다.  
나중에 인터뷰와 최종 프롬프트에서 사용할 **원재료**입니다.

---

## 전체 흐름

```text
0. 준비
1. 자료 수집
2. 100문 100답
3. 1차 인터뷰
4. 추가 질문 생성
5. 2차 인터뷰
6. 최종 사용 설명서 생성
7. 저자성 검수와 버전 분리
8. 업데이트 시스템 운영
```

각 단계는 [SUMMARY.md](SUMMARY.md)에 정리되어 있습니다.

---

## 음성으로 해야 하나요?

아닙니다.

- 텍스트로 혼자 작성해도 됩니다.
- ChatGPT와 텍스트 채팅으로 한 문제씩 진행해도 됩니다.
- ChatGPT 음성 대화로 편하게 말해도 됩니다.

음성은 필수가 아니라, **머릿속에서 아직 정리되지 않은 생각을 필터링 없이 말하기 쉬운 입력 방식**입니다. 자세한 설명은 [docs/02_tools_and_modes.md](docs/02_tools_and_modes.md)와 [workflow/03_answer_100_questions.md](workflow/03_answer_100_questions.md)를 보세요.

---

## 결과물

끝까지 진행하면 최소한 아래 파일을 만들 수 있습니다.

```text
outputs/01_answer_log.md
outputs/02_round1_summary.md
outputs/03_followup_questions.md
outputs/04_round2_summary.md
outputs/05_full_manual.md
outputs/06_active_context.md
outputs/07_team_share_one_pager.md
outputs/08_public_profile.md
outputs/09_update_plan.md
```

ChatGPT에게 결과를 받을 때는 채팅창에 긴 텍스트만 받지 말고, 가능하면 **Markdown 파일 형태로 생성해달라고 요청**하세요.

---

## 주의

이 레포는 민감한 개인 맥락을 다룹니다. 회사 기밀, 타인 개인정보, 고객 정보, 인사평가 원문, 건강/심리 관련 세부 정보는 그대로 넣지 마세요. 먼저 [docs/03_security.md](docs/03_security.md)를 읽는 것을 권장합니다.
