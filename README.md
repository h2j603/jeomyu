# 점유 (jeomyu)

에세이 「웹을 본래와 다른 목적으로 점유하기」를 보여주는 페이지. 글이 곧 댓글칸이다.

- 공개 주소: https://hyuk.xyz/jeomyu/ (GitHub Pages, 레포 h2j603/jeomyu, main 푸시 = 배포).
- 본문은 Suit, 제목·구분자(***)·리플은 Cafe24 PRO UP. 리플은 유니코드가 깨지지 않게 `pre-wrap`.
- 각주는 본문 구절에 별표(*) 밑줄 링크를 달고 페이지 하단 목록으로 보낸다. 본문은 원문 그대로.
- 방문자는 문단을 길게 눌러 그 자리에 리플을 단다: 이름·링크(URL, 선택)·본문(텍스트만). 리플을 누르면 앞으로 나온다.
- 저장소: Supabase 프로젝트 `jeomyu`(ref zrpwdzfhtljptkcmjavc, 도쿄). 테이블 `public.replies`, RLS: anon 읽기·쓰기 허용, 수정·삭제 불가. 키·DB 비번: ~/.config/supabase/jeomyu.env. 관리 SQL은 Management API(토큰 ~/.config/supabase/token).
- 원고 정본: ~/notes/web-essay-draft-v4.md. 인용 원문 확인 기록: ~/notes/web-essay-research/.

로컬 확인: `python3 -m http.server 8877` 후 http://127.0.0.1:8877/
