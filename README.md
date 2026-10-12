# monitoring-site

계측 AI 모니터링 소개 페이지 — https://monitoring.mint-soft.com

정적 HTML 한 벌이다. `main` 에 올리면 GitHub Pages 가 그대로 내보낸다(빌드 없음). 도메인은 `CNAME` 파일이 정한다.

- `index.html` 본문과 스타일
- `assets/` 제품 화면(시연용 데이터로 찍은 것), `og.png` 는 공유용 미리보기 그림
- `robots.txt`, `sitemap.xml`, `llms.txt` 검색 엔진과 AI 답변 엔진용


미리 보기: `python3 -m http.server 4000` 후 http://localhost:4000
