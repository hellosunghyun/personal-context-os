# 완성 후. 업데이트 시스템 운영하기

[← 이전](../FINISH.md) | [목차](../SUMMARY.md) | [다음 →](../tests/manual_quality_test.md)

## 완성 후 운영할 때 할 일

한 번 만든 사용 설명서를 오래 쓰기 위해 업데이트 방식을 정합니다.

처음 사용 설명서를 만드는 중이라면 이 문서는 건너뛰어도 됩니다. `outputs/05_full_manual.md`와 `outputs/06_active_context.md`가 생긴 뒤에 다시 봐도 늦지 않습니다.

---

## 왜 나중에 이걸 하나요?

사람은 변합니다. 문서를 만들고 끝내면 금방 낡습니다. 하지만 매번 전체를 다시 쓰면 부담이 큽니다.

그래서 업데이트는 전체 재작성보다 **변경분 관리**로 합니다.

---

## 추천 운영 구조

```text
full_manual.md
- 전체 원본
- 자주 바꾸지 않음

active_context.md
- 실제 LLM에게 자주 첨부하는 핵심 파일
- 월 1회 갱신

answer_taste_log.md
- 좋았던 답변과 싫었던 답변 기록
- GPT가 내 답변 취향을 더 잘 맞추게 하는 자료

event_update_log.md
- 큰 사건 직후 기록
- 프로젝트 종료, 피드백, 갈등, 번아웃, 이직 고민 등

archive/
- 과거에는 맞았지만 현재는 덜 맞는 내용
```

---

## 월간 업데이트

월 1회 아래 질문만 답합니다.

```text
최근 한 달 동안 새로 알게 된 내 패턴은?
이제 덜 맞는 설명은?
반복해서 좋았던 GPT 답변은?
반복해서 싫었던 GPT 답변은?
active_context.md에 추가하거나 뺄 내용은?
```

[prompts/09_update.md](../prompts/09_update.md)를 사용하면 됩니다.

---

## 사건 기반 업데이트

큰 사건이 생긴 직후에는 [templates/event_update_log.md](../templates/event_update_log.md)를 작성합니다.

예:

```text
큰 프로젝트 종료
인사평가 수신
팀원과 갈등
GPT 답변이 매우 좋았거나 매우 나빴던 경우
면접이나 커리어 전환
번아웃 또는 회복 경험
```

---

## 품질 테스트

분기마다 [tests/manual_quality_test.md](../tests/manual_quality_test.md)를 사용합니다.

목표는 문서가 길어졌는지가 아니라, 실제 답변이 더 내 것처럼 나오는지 확인하는 것입니다.

---

## 이 단계의 결과물

```text
outputs/09_update_plan.md
outputs/answer_taste_log.md
outputs/event_update_log.md
```

---

## 다음 행동

완성된 문서가 실제 답변 품질을 바꾸는지 확인합니다.

다음: [품질 테스트 질문](../tests/manual_quality_test.md)
