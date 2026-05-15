# 4단계. 1차 인터뷰 진행하기

[← 이전](03_answer_100_questions.md) | [목차](../SUMMARY.md) | [다음 →](05_generate_followups.md)

## 이 페이지에서 지금 할 일

100문 100답을 바탕으로 ChatGPT와 1차 인터뷰를 진행하고 `outputs/02_round1_summary.md`를 만듭니다.

---

## 왜 지금 이걸 하나요?

100문 100답은 넓게 훑는 단계입니다. 1차 인터뷰는 답변에 숨어 있는 구체적 장면, 예외, 감정의 뉘앙스, 판단의 이유를 더 깊게 확인하는 단계입니다.

---

## 준비물

```text
outputs/01_answer_log.md
outputs/source_register.md
필요하면 inputs/의 선택 자료
```

---

## 텍스트로 진행하는 방법

1. ChatGPT에 `01_answer_log.md`를 첨부합니다.
2. 필요하면 `source_register.md`도 첨부합니다.
3. [prompts/03_round1_interview.md](../prompts/03_round1_interview.md)를 붙여넣습니다.
4. ChatGPT가 한 질문씩 묻게 합니다.
5. 대화가 끝나면 요약을 `outputs/02_round1_summary.md`로 저장합니다.

---

## 음성으로 진행하는 방법

1. ChatGPT에 `01_answer_log.md`를 첨부합니다.
2. [prompts/03_round1_interview.md](../prompts/03_round1_interview.md)를 먼저 텍스트로 붙여넣습니다.
3. 음성 대화를 켭니다.
4. 30~60분 정도 편하게 말합니다.
5. 끝나면 반드시 아래처럼 요청합니다.

```text
방금 대화를 outputs/02_round1_summary.md로 저장할 수 있게 Markdown 형식으로 정리해줘.
내가 실제로 말한 내용, 너의 해석, 추가 확인 필요를 분리해줘.
```

---

## 이 단계에서 중요한 것

```text
ChatGPT가 답을 대신 만들면 안 된다.
답변이 추상적이면 실제 장면을 물어봐야 한다.
민감한 내용은 공개 범위를 표시해야 한다.
모르는 내용은 추가 확인 필요로 남긴다.
```

---

## 이 단계의 결과물

```text
outputs/02_round1_summary.md
```

---

## 다음 행동

1차 인터뷰 결과를 바탕으로 추가 질문을 생성합니다. 이 단계는 선택사항이 아닙니다.

다음: [추가 질문 생성하기](05_generate_followups.md)
