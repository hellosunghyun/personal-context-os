# Changelog

[목차](SUMMARY.md)

## v1.0.1

- 첫 생성 흐름과 완성 후 운영/확장 흐름을 분리.
- 최종 문서를 한 번에 생성하지 않고 파트별 초안 생성 후 합치는 방식으로 변경.
- `prompts/06_merge_manual_outputs.md`를 추가해 파트 초안 통합 단계를 명확히 함.
- `FINISH.md`를 추가해 첫 생성 흐름의 마지막 도착점을 명확히 하고, 9단계에서 100문 100답으로 돌아가던 순환 링크를 제거.
- `templates/answer_log.md`를 Q1~Q100까지 바로 기록할 수 있게 확장.
- `LICENSE.md`를 실제 MIT License 전문으로 교체.
- `source_register.md`에 원문 위치, 업로드/보관 위치, 삭제/갱신 기준을 추가.
- 최종 생성/병합/검수 프롬프트에 근거 ID, 평가 불가, 추가 확인 필요 기준을 추가.
- `active_context.md`에 사용 규칙, 사용 금지 정보, 최근성, 예시 요청을 추가.
- GPTs 확장 문서에 Instructions, Knowledge, Conversation starters, Capabilities 매핑을 추가.
- prompts, templates, examples, tests 사이의 뜬금없는 교차 navigation을 정리.

## v1.0.0

- 처음 보는 사람이 따라 할 수 있도록 전체 구조를 처음부터 재작성.
- 필수 흐름을 `준비 → 자료 수집 → 100문 100답 → 1차 인터뷰 → 추가 질문 → 2차 인터뷰 → 최종 문서 → 검수/분리 → 업데이트`로 정렬.
- 100문 100답을 쉬운 질문, 설명, 예시 중심으로 재작성.
- 텍스트 진행과 음성 진행을 각 단계에서 명확히 분리.
- 결과물을 Markdown 파일로 저장하는 방식을 기본으로 설계.
- 선택사항은 GPTs/챗봇, 팀 공유, 음성 사용 등으로 제한.
