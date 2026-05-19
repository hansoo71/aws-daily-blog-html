# Agent Guide

- `src/YYYYMMDD/`를 원본 작업본, `docs/YYYYMMDD/`와 `docs/index.html`을 GitHub Pages 배포본으로 유지한다.
- Markdown 수집물은 LLM Wiki/GBrain 로컬 source에만 저장하고, public repo에는 HTML/이미지/prompt log만 둔다.
- 이미지 경로는 dated page와 latest page 모두에서 HTTP 200이 되도록 `docs/images/` 또는 dated images를 함께 관리한다.
- 민감자료, 비공개 고객자료, 원문 전체 추출본은 public repo에 커밋하지 않는다.
