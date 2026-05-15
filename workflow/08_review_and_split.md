# 8단계. 초안을 합치고 검수하기

[← 이전](07_build_manual.md) | [목차](../SUMMARY.md) | [다음 →](../FINISH.md)

## 이 페이지에서 지금 할 일

파트별 초안을 최종 파일로 합치고, 실제로 내 것인지 확인한 뒤 본인용/팀원용/공개용 버전을 정리합니다.

---

## 왜 지금 이걸 하나요?

GPT 답변이 마음에 들어도 바로 쓰면 안 됩니다.  
좋은 답변과 내 답변은 다를 수 있습니다.

---

## 저자성 검수 기준

아래 질문에 답해보세요.

```text
내가 요청하기 전 얼핏 상상한 방향과 비슷한가?
내가 실제로 쓸 법한 표현인가?
너무 멋있게 업그레이드된 부분은 없는가?
내가 말하지 않은 경험이나 동기가 들어갔는가?
불편하거나 과한 심리 해석은 없는가?
팀원에게 공유하면 오해될 부분은 없는가?
근거 ID 없이 단정한 문장이 있는가?
평가할 수 없는 내용을 평가한 것처럼 썼는가?
```

---

## 1. 파트 초안 합치기

1. `outputs/drafts/`의 초안 파일을 모두 첨부합니다.
2. [prompts/06_merge_manual_outputs.md](../prompts/06_merge_manual_outputs.md)를 사용합니다.
3. 근거 ID, 충돌, 평가 불가 항목이 사라지지 않게 합칩니다.
4. 아래 최종 파일로 합칩니다.

```text
outputs/05_full_manual.md
outputs/06_active_context.md
outputs/07_team_share_one_pager.md
outputs/08_public_profile.md (필요할 때만)
```

---

## 2. 저자성 검수

1. `outputs/05_full_manual.md`를 ChatGPT에 첨부합니다.
2. [prompts/07_authorship_review.md](../prompts/07_authorship_review.md)를 사용합니다.
3. 내 말 같지 않은 문장, 근거가 약한 해석, 공개 범위가 섞인 부분을 수정합니다.

---

## 3. 버전 분리 확인

1. [prompts/08_split_versions.md](../prompts/08_split_versions.md)를 사용합니다.
2. 팀원용에서 민감한 내용이 제거됐는지 확인합니다.
3. 공개용을 만들었다면 공개 가능한 내용만 남았는지 확인합니다.
4. 수정된 결과를 다시 저장합니다.

---

## 버전 분리 기준

```text
본인용:
- 가장 솔직함
- 민감한 자기 이해와 회복 루틴 포함

팀원용:
- 업무 방식, 소통 방식, 피드백 방식 중심
- 민감한 심리 정보는 행동 패턴으로 완화

공개용:
- 포트폴리오, 블로그, 자기소개에 쓸 수 있는 수준
- 사적 취약성 제거
```

---

## 이 단계의 결과물

```text
outputs/05_full_manual.md 수정본
outputs/06_active_context.md 수정본
outputs/07_team_share_one_pager.md 수정본
outputs/08_public_profile.md 수정본 (공개용을 만들었을 때만)
```

---

## 다음 행동

마지막으로 완료 페이지에서 결과물이 사용 가능한 상태인지 확인합니다.

다음: [첫 생성 완료](../FINISH.md)
