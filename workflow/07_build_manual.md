# 7단계. 파트별 최종 문서 초안 만들기

[← 이전](06_round2_interview.md) | [목차](../SUMMARY.md) | [다음 →](08_review_and_split.md)

## 지금 할 일

지금까지 만든 자료를 바탕으로 최종 문서 초안을 **파트별로 나누어** 만듭니다.

---

## 왜 이 단계가 있나요?

이전 단계들은 모두 원재료 수집이었습니다. 바로 최종본을 한 번에 만들면 내용이 그럴듯하게 채워지거나, 앞뒤 맥락이 섞이기 쉽습니다.

그래서 먼저 작은 초안을 여러 개 만들고, 다음 단계에서 합칩니다.

---

## 준비물

```text
outputs/source_register.md
outputs/01_answer_log.md
outputs/02_round1_summary.md
outputs/03_followup_questions.md
outputs/04_round2_summary.md
선택 자료 요약본
```

---

## 먼저 만들 폴더

로컬로 진행한다면 아래 폴더를 만듭니다.

```text
outputs/drafts/
```

ChatGPT Project로 진행한다면 파일 이름에 `draft_`를 붙여 구분합니다.

---

## 파일로 제공하는 방법

가능하면 긴 내용을 채팅에 한 번에 붙여넣지 말고 파일로 첨부하세요.

추천 첨부 방식:

```text
1_source_register.md
2_answer_log.md
3_round1_summary.md
4_followup_questions.md
5_round2_summary.md
6_optional_materials_summary.md
```

파일을 여러 개 한 번에 첨부해도 됩니다. 단, 민감한 원문은 넣지 말고 요약본을 사용하세요.

각 파일 안에 근거 ID가 있으면 유지하세요. 예를 들어 100문 답변은 `Q041`, 자료 목록은 `S002`, 2차 인터뷰는 `R2`처럼 표시해두면 최종 문서가 어디서 왔는지 추적하기 쉽습니다.

---

## 실행 방법

1. ChatGPT에 위 파일들을 첨부합니다.
2. [prompts/06_final_manual_deep.md](../prompts/06_final_manual_deep.md)를 기준으로 보거나, 아래 파트별 프롬프트 중 하나를 붙여넣습니다.
3. 한 번에 전체 문서를 만들지 말고, 아래 파트 중 하나만 선택해 생성합니다.
4. 근거가 약한 내용은 `추가 확인 필요` 또는 `평가 불가`로 남기게 합니다.
5. 각 결과를 `outputs/drafts/`에 저장합니다.

파트별 프롬프트:

```text
prompts/06a_build_identity_values.md
prompts/06b_build_work_communication.md
prompts/06c_build_llm_risks_growth.md
prompts/06d_build_active_context.md
prompts/06e_build_team_share.md
prompts/06f_build_public_profile.md
```

권장 생성 순서:

```text
1. outputs/drafts/05a_identity_values.md
2. outputs/drafts/05b_work_communication.md
3. outputs/drafts/05c_llm_risks_growth.md
4. outputs/drafts/06a_active_context.md
5. outputs/drafts/07a_team_share_one_pager.md
6. outputs/drafts/08a_public_profile.md (공개용이 필요할 때만)
```

`outputs/09_update_plan.md`는 첫 최종본이 나온 뒤, 운영을 시작할 때 만듭니다.

---

## 이 단계가 끝나면

```text
outputs/drafts/05a_identity_values.md
outputs/drafts/05b_work_communication.md
outputs/drafts/05c_llm_risks_growth.md
outputs/drafts/06a_active_context.md
outputs/drafts/07a_team_share_one_pager.md
outputs/drafts/08a_public_profile.md (선택)
```

---

## 다음으로

초안을 합치고, 제 답변처럼 느껴지는지 검수합니다.

다음: [초안을 합치고 검수하기](08_review_and_split.md)
