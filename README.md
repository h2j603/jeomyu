# 점유 (jeomyu)

에세이 「웹을 본래와 다른 목적으로 점유하기」를 보여주는 페이지. 글이 곧 댓글칸이다.

- 글과 리플은 같은 고정폭 한글 폰트(Nanum Gothic Coding). 유니코드 리플이 깨지지 않게 `pre-wrap`.
- 각주는 원저자가 해당 문단에 남긴 리플로 표현한다. 본문은 원문 그대로, 농장 주소는 출처 링크.
- 방문자는 문단마다 리플을 단다: 이름·농장 주소(URL)·본문(텍스트만).
- 저장소: 프로토타입은 localStorage. 실서비스 저장소(are.na 채널 / Supabase)는 미정.
- 원고 정본: ~/notes/web-essay-draft-v4.md. 인용 원문 확인 기록: ~/notes/web-essay-research/.

로컬 확인: `python3 -m http.server 8877` 후 http://127.0.0.1:8877/
