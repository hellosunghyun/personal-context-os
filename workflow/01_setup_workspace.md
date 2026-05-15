# 1단계. 작업 공간 만들기

[← 이전](00_linear_flow.md) | [목차](../SUMMARY.md) | [다음 →](02_collect_context.md)

## 지금 할 일

답변, 요약, 최종 문서를 저장할 공간을 만듭니다.

---

## 왜 이 단계가 있나요?

이 작업은 한 번의 채팅으로 끝나지 않습니다. 100문 100답, 인터뷰, 추가 질문, 최종 문서가 쌓입니다. 처음부터 저장 위치를 정해야 나중에 맥락이 섞이지 않습니다.

---

## 방법 A. 로컬 폴더로 진행

컴퓨터에 아래 폴더를 만듭니다.

```text
my-personal-context-os/
  inputs/
  outputs/
  outputs/drafts/
  archive/
```

용도는 다음과 같습니다.

```text
inputs/
- 포트폴리오, 회고, 피드백 요약 등 원자료

outputs/
- 답변 기록, 인터뷰 요약, 최종 사용 설명서

outputs/drafts/
- 최종 문서로 합치기 전의 파트별 초안

archive/
- 과거에는 맞았지만 지금은 덜 맞는 내용
```

---

## 방법 B. ChatGPT Project로 진행

ChatGPT Project를 사용할 수 있다면 하나 만들어도 좋습니다.

추천 이름:

```text
Personal Context OS
개인 사용 설명서
```

Project 안에는 처음부터 모든 결과물을 만들지 않습니다. 지금은 작업 기준과 첫 기록 파일만 준비합니다.

```text
source_register.md
01_answer_log.md
```

아래 파일들은 나중에 각 단계가 끝날 때 생성합니다.

```text
02_round1_summary.md
03_followup_questions.md
04_round2_summary.md
outputs/drafts/*.md
05_full_manual.md
06_active_context.md
07_team_share_one_pager.md
```

Project를 쓰면 같은 작업의 채팅과 파일을 한곳에 모아둘 수 있습니다. 다만 제품 기능, 파일 개수 제한, 메모리 방식은 계속 바뀔 수 있습니다. 이 가이드는 특정 기능을 전제로 하기보다, 파일 이름과 공개 범위를 분명히 남기는 방식을 우선합니다.

민감한 자료를 넣기 전에는 보안 기준을 먼저 확인하세요. 원문을 그대로 올릴지, 요약본만 올릴지, 아예 올리지 않을지를 `source_register.md`에 표시합니다.

---

## 지금 바로 만들 파일

[templates/source_register.md](../templates/source_register.md)를 복사해서 아래 위치에 저장합니다.

```text
outputs/source_register.md
```

---

## 이 단계가 끝나면

```text
작업 폴더 또는 ChatGPT Project
outputs/source_register.md
```

---

## 다음으로

선택 자료를 모으고 위험도를 분류합니다.

다음: [선택 자료 모으기](02_collect_context.md)
