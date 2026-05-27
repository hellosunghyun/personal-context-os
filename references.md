# 참고 자료

[목차](SUMMARY.md)

이 문서는 본문 흐름에 모두 넣기에는 넓은 배경 자료를 모아둔 참고문헌입니다. 제품 기능, 모델, 요금제, 파일 업로드, 메모리, GPTs 관련 세부 정책은 자주 바뀔 수 있으므로 항상 공식 문서를 우선 확인하세요.

확인일: 2026-05-27

## 최신 AI 개인화와 컨텍스트 관리

이 섹션은 개인화와 맥락 관리 관점에서 먼저 볼 자료를 묶은 길잡이입니다. 제품별 원문 링크는 아래 공식 문서 섹션에 둡니다.

- OpenAI Projects, Memory FAQ, GPTs: 파일, 채팅, 지침, 저장된 기억, 맞춤형 GPT 구성 요소를 확인할 때 참고. 원문 링크는 [OpenAI 공식 문서](#openai-공식-문서)의 해당 항목을 봅니다.
- Anthropic Effective context engineering for AI agents: 프롬프트 엔지니어링에서 컨텍스트 엔지니어링으로 이동하는 흐름과 context를 유한한 자원으로 보는 관점 참고. 원문 링크는 [Anthropic 엔지니어링 문서](#anthropic-엔지니어링-문서)의 해당 항목을 봅니다.

## AI 과의존, 저자성, 인지 리스크

- Tankelevitch, L., et al. (2025). [Understanding, Protecting, and Augmenting Human Cognition with Generative AI](https://arxiv.org/abs/2508.21036). 생성형 AI가 메타인지, 비판적 사고, 기억, 창의성에 미치는 영향을 다룬 CHI 2025 Tools for Thought 워크숍 종합.
- Sarkar, A., et al. (2024). [When Copilot Becomes Autopilot](https://arxiv.org/abs/2412.15030). 생성형 AI가 지식노동에서 비판적 사고를 약화시킬 수 있다는 문제와 "AI as critic" 설계 방향 참고.
- Choudhuri, R., et al. (2026). [Thinking Less, Trusting More](https://arxiv.org/abs/2601.22430). 생성형 AI에 대한 신뢰와 반복 사용이 인지적 참여와 어떤 관계가 있는지 참고.
- Harvard Business Review / Stanford / BetterUp. [AI-Generated "Workslop" Is Destroying Productivity](https://hbr.org/2025/09/ai-generated-workslop-is-destroying-productivity). AI 산출물이 겉으로는 매끈하지만 실질이 부족해 동료의 시간을 낭비하는 현상 참고.
- Axios. [AI "workslop" sabotages productivity, study finds](https://www.axios.com/2025/09/24/ai-workslop-workplace-efficiency-study). workslop 용어와 관련 조사 수치를 빠르게 확인할 때 참고.

## OpenAI 공식 문서

- OpenAI. [ChatGPT Custom Instructions](https://help.openai.com/en/articles/8096356). Custom Instructions의 적용 범위와 삭제/수정 기준을 확인할 때 참고.
- OpenAI. [Projects in ChatGPT](https://help.openai.com/en/articles/10169521-using-projects-in-chatgpt). Project 안에서 채팅, 파일, 지침을 묶는 방식과 공유/기능 제한을 확인할 때 참고.
- OpenAI. [File Uploads FAQ](https://help.openai.com/en/articles/8555545-file-uploads-faq). 파일 업로드, 보관, 제한을 확인할 때 참고.
- OpenAI. [Memory FAQ](https://help.openai.com/en/articles/8590148-memory-faq). Saved Memory, 과거 대화 참조, 메모리 삭제와 민감 정보 주의점을 확인할 때 참고.
- OpenAI. [GPTs in ChatGPT](https://help.openai.com/en/articles/8554407-gpts-in-chatgpt). GPTs의 지시문, 지식, 기능, 공유 범위를 확인할 때 참고.
- OpenAI. [Creating and editing GPTs](https://help.openai.com/en/articles/8554397-creating-and-editing-gpts). GPT를 만들고 수정할 때의 설정 항목을 확인할 때 참고.
- OpenAI. [Voice Mode FAQ](https://help.openai.com/articles/8400625-voice-mode-faq/). 음성 대화의 기능, 제한, 데이터 보관 주의점을 확인할 때 참고.
- OpenAI. [Prompt Engineering Guide](https://developers.openai.com/api/docs/guides/prompt-engineering). 프롬프트 구성 원칙을 넓게 참고.
- OpenAI. [Evaluation Best Practices](https://developers.openai.com/api/docs/guides/evaluation-best-practices). before/after 테스트와 평가 루프 설계의 배경으로 참고.

## Anthropic 엔지니어링 문서

- Anthropic. [Effective context engineering for AI agents](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents). 컨텍스트를 선별, 압축, 관리해야 한다는 관점의 주요 참고.
- Anthropic. [Building effective agents](https://www.anthropic.com/engineering/building-effective-agents). 에이전트와 워크플로를 구분하고 필요한 만큼만 복잡하게 설계하는 관점의 참고.
- Anthropic. [Equipping agents for the real world with Agent Skills](https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills). 지침, 스크립트, 리소스를 폴더 단위로 묶어 agent가 필요할 때 읽는 방식의 참고.
- Anthropic. [Demystifying evals for AI agents](https://www.anthropic.com/engineering/demystifying-evals-for-ai-agents). 평가 항목, 그레이더, 회귀 테스트를 설계할 때 참고.
- Anthropic. [Harness design for long-running application development](https://www.anthropic.com/engineering/harness-design-long-running-apps). 긴 작업을 작은 단위로 나누고 구조화된 산출물로 맥락을 이어가는 방식의 참고.
- Anthropic. [Contextual Retrieval in AI Systems](https://www.anthropic.com/engineering/contextual-retrieval). RAG와 검색 기반 맥락 제공의 한계를 이해할 때 참고.

## LLM 개인화, 프롬프팅, RAG

- Lewis, P., et al. (2020). [Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks](https://arxiv.org/abs/2005.11401). RAG 원전 계열.
- Wang, R., et al. (2024). [Role Prompting Guided Domain Adaptation with General Capability Preserve for Large Language Models](https://arxiv.org/abs/2403.02756). Role Prompting 용어와 구조를 확인할 때 참고.
- Tseng, Y.-M., et al. (2024). [Two Tales of Persona in LLMs: A Survey of Role-Playing and Personalization](https://arxiv.org/abs/2406.01171). Persona를 role-playing과 personalization으로 나눠 보는 관점의 참고.
- Zhang, J. (2024). [Guided Profile Generation Improves Personalization with LLMs](https://arxiv.org/abs/2409.13093). 개인화 맥락을 사용자 프로필 형태로 중간 정리하는 접근의 참고.

## 심리와 성격 개념

- The Myers & Briggs Foundation. [Myers-Briggs Type Indicator 공식 개요](https://www.myersbriggs.org/my-mbti-personality-type/myers-briggs-overview/). MBTI를 선호 경향의 언어로 설명할 때 참고.
- Carlyn, M. (1977). [An assessment of the Myers-Briggs Type Indicator](https://doi.org/10.1207/s15327752jpa4105_2). *Journal of Personality Assessment, 41*(5), 461-473. MBTI의 오래된 비판적 리뷰.
- Goldberg, L. R. (1990). [An alternative description of personality: The Big-Five factor structure](https://projects.ori.org/lrg/pdfs_papers/goldberg.big-five-factorsstructure.jpsp.1990.pdf). Big Five 원전 계열.
- John, O. P., & Srivastava, S. (1999). [The Big-Five trait taxonomy: History, measurement, and theoretical perspectives](https://pages.uoregon.edu/sanjay/pubs/bigfive.pdf). Big Five 정리 문헌.
- Ryan, R. M., & Deci, E. L. (2000). [Self-determination theory and the facilitation of intrinsic motivation, social development, and well-being](https://selfdeterminationtheory.org/SDT/documents/2000_RyanDeci_SDT.pdf). 자율성, 유능감, 관계성의 배경 참고.
- Hewitt, P. L., & Flett, G. L. (1991). [Perfectionism in the self and social contexts](https://hewittlab.sites.olt.ubc.ca/files/2014/11/Hewitt-Flett-1991-Perfectionism-in-the-self-and-social-contexts-conceptualization-assessment-and-association-with-psychopathology.pdf). 완벽주의를 다차원적으로 볼 때 참고.
- Hayes, S. C., et al. (1996). [Experiential avoidance and behavioral disorders](https://actmindfully.com.au/upimages/experiential_avoidance.pdf). 회피를 정서와 경험을 피하려는 기능적 패턴으로 볼 때 참고.
- Maslach, C., Schaufeli, W. B., & Leiter, M. P. (2001). [Job Burnout](https://doi.org/10.1146/annurev.psych.52.1.397). 번아웃의 대표 리뷰.

## 보안, 개인정보, 비식별화

- Garfinkel, S. L. (2015). [De-Identification of Personal Information](https://www.nist.gov/publications/de-identification-personal-information). NISTIR 8053. 개인 정보 비식별화와 재식별 위험을 설명할 때 참고.
- 개인정보보호위원회. (2025). [생성형 인공지능 개발·활용을 위한 개인정보 처리 안내서](https://m.pipc.go.kr/np/cop/bbs/selectBoardArticle.do?bbsId=BS217&mCode=D010030000&nttId=11439). 생성형 AI 수명주기에서 개인정보 처리와 보호 이슈를 확인할 때 참고.

## 협업과 개인 사용 설명서

- Atlassian. [My User Manual](https://www.atlassian.com/team-playbook/plays/my-user-manual). 협업용 개인 사용 설명서의 목적과 안전한 공유 흐름을 참고.

## 인지 부하와 질문 설계

- Sweller, J. (1988). [Cognitive load during problem solving: Effects on learning](https://doi.org/10.1016/0364-0213(88)90023-7). *Cognitive Science, 12*(2), 257-285. 한 번에 너무 많은 질문을 던지지 않는 설계의 배경 참고.
- Brosnan, K., Grun, B., & Dolnicar, S. (2021). [Cognitive load reduction strategies in questionnaire design](https://doi.org/10.1177/1470785320986797). 질문 설계에서 인지 부하를 줄이는 접근의 참고.

## 읽는 법

이 참고 자료들은 기능 설명, 개념 배경, 보안 기준을 확인하기 위한 자료입니다. 이 레포의 핵심은 특정 제품 기능 자체가 아니라, **개인 맥락을 안전하게 정리하고, 파일로 보관하고, 필요할 때 LLM에 제공하는 방법**입니다.
