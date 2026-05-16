# 다른 방법론과의 차이

[← 이전](04_why_not_mbti.md) | [목차](../SUMMARY.md) | [다음 →](06_use_cases.md)

## 여기서 볼 것

이 가이드가 persona prompting, custom instructions, context engineering, RAG, GPTs, 개인 에이전트 흐름과 어떻게 다른지 설명합니다.

---

## 한 줄 요약

이 가이드는 **개인 단위 Context Engineering 워크북**입니다.

---

## Persona Prompting과의 차이

Persona Prompting은 보통 이렇게 시작합니다.

```text
당신은 뛰어난 컨설턴트입니다.
당신은 엄격한 편집자입니다.
당신은 친절한 코치입니다.
```

이 방식은 모델의 답변 스타일을 빠르게 조정하는 데 유용합니다. 하지만 사용자의 실제 맥락을 충분히 제공하지는 않습니다.

출처 메모: Persona Prompting은 LLM에게 역할이나 사용자 페르소나를 부여하는 접근과 연결됩니다. 이 문서에서는 persona 연구 전체를 설명하지 않고, [persona/role prompting 관련 참고문헌](../references.md#llm-개인화-프롬프팅-rag)을 배경으로만 둡니다.

이 가이드는 반대로 시작합니다.

```text
이 요청을 하는 사람은 어떤 맥락을 가진 사람인가?
이 사람은 어떤 답변을 만족스럽게 느끼는가?
이 사람에게는 어떤 표현이 남의 말처럼 느껴지는가?
```

---

## Custom Instructions와의 차이

Custom Instructions는 짧은 선호를 저장하는 데 좋습니다.

```text
답변은 한국어로 해줘.
결론부터 말해줘.
예시는 실무 중심으로 해줘.
```

하지만 긴 회고, 답변 취향, 팀 공유 기준, 업데이트 로그까지 담기에는 부족할 수 있습니다.

이 가이드는 Custom Instructions에 넣을 핵심 문장을 만들기 위한 원본 시스템에 가깝습니다.

출처 메모: Custom Instructions의 적용 범위와 제한은 [OpenAI Custom Instructions 문서](../references.md#openai-공식-문서)를 기준으로 확인하세요.

---

## Context Engineering과의 관계

Context Engineering은 모델에게 어떤 정보를 언제, 얼마나, 어떤 구조로 제공할지 설계하는 접근입니다.

이 가이드는 그 관점을 개인에게 적용합니다.

```text
모든 정보를 항상 넣지 않는다.
full_manual과 active_context를 나눈다.
지금 필요한 맥락만 첨부한다.
좋았던 답변과 싫었던 답변을 업데이트한다.
```

출처 메모: 컨텍스트를 유한한 자원으로 보고 선별, 압축, 갱신해야 한다는 관점은 [Anthropic의 context engineering 문서](../references.md#anthropic-엔지니어링-문서)를 참고했습니다.

---

## RAG와의 차이

RAG는 보통 문서 검색과 지식 기반 질의응답에 가깝습니다.

이 가이드는 검색 가능한 지식만 다루지 않습니다.

```text
답변 취향
말투
맥락
불편한 표현
팀원과의 소통 패턴
납득하고 받아들이는 기준
```

즉, 지식 검색보다 **사용자 맥락 정렬**에 가깝습니다.

출처 메모: RAG의 원전 계열과 검색 기반 맥락 제공의 배경은 [RAG 참고문헌](../references.md#llm-개인화-프롬프팅-rag)에 정리했습니다.

---

## GPTs와의 차이

GPTs는 특정 목적의 맞춤형 ChatGPT를 만드는 기능입니다. 이 가이드의 결과물은 GPTs를 만들 때 지식 파일이나 지시문으로 활용될 수 있습니다.

```text
이 가이드 = 개인 맥락을 만드는 워크북
GPTs = 그 맥락을 반복적으로 쓰는 인터페이스
```

출처 메모: GPTs의 구성 요소와 공유 범위는 [OpenAI GPTs 문서](../references.md#openai-공식-문서)를 확인하세요.

---

## 개인 에이전트 흐름과의 차이

일부 개인 에이전트 흐름은 장기 기억, 스킬, 자동화, 자기 개선 루프를 강조합니다.

이 가이드는 그보다 작고 안전한 출발점입니다.

```text
먼저 수동으로 개인 맥락을 정리한다.
그다음 필요하면 GPTs나 챗봇으로 확장한다.
자동화보다 저자성, 검수, 보안을 먼저 둔다.
```

출처 메모: Agent Skills, 긴 작업 하니스, 에이전트 평가 루프는 [Anthropic 엔지니어링 문서](../references.md#anthropic-엔지니어링-문서)를 참고했습니다. 이 가이드는 그보다 작게 시작하는 수동 워크북입니다.

---

## 다음으로

실제로 어디에 쓸 수 있는지 예시를 봅니다.

다음: [사용 예시](06_use_cases.md)
