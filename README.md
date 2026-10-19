# 2026 인천신용보증재단 홈페이지 개편 분석 및 제안 (웹 프레젠테이션)

Figma 16장 제안서를 GSAP 전환 효과로 넘겨 보는 정적 웹 페이지입니다. 참고: https://uiux-test.github.io/NPLEY-SPEP/

## 구성
- `index.html` — HTML·CSS·JS 한 파일. 장표 데이터(`SLIDES`)가 스크립트 안에 있음
- `assets/sNN.png` — Figma 원본 장표 (1280×720)
- `assets/bNN.png` — 타이틀 영역을 배경색으로 비운 본문 이미지
- 타이틀(큰 영문 단어 · 아이브로 · 헤드라인 줄 · 우측 설명)은 `sNN.png`에서 영역별로 잘라 마스크 안에서 올라오게 함

## 조작
←/→, 스페이스, 클릭(오른쪽 다음·왼쪽 이전), 스와이프 · G 전체 보기 · F 전체 화면 · `#s7`처럼 주소 뒤에 붙이면 해당 장으로 이동

## 원본
- Figma: https://www.figma.com/design/gKU3v3qKaXU5BWbYyvSURV (node 367:15729 · 최종)
- 내용을 바꾸면 해당 장 `sNN.png`를 교체하고 `bNN.png`를 다시 만들어야 함 (타이틀 영역 좌표는 `index.html`의 `SLIDES`)
