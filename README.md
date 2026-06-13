# 보험설계사 원데이 자동화 세미나 — 랜딩 페이지 (디럭스/애니메이션 버전)

`index.html` 한 파일이 전부입니다. 빌드 불필요. 외부 의존성은 구글폰트와 Jotform 신청 폼(인터넷 로드)뿐.
JS가 켜진 브라우저에서 스크롤 진행바·스크롤 연동 타임라인·카드 3D 틸트·자석 CTA·히어로 파티클·손전등 커서·숫자 카운트업이 동작합니다. (JS가 꺼져도 내용은 그대로 보입니다.)

## Codespace 미리보기
터미널: `python3 -m http.server 8000` 실행 후, 포워딩된 포트를 브라우저로 엽니다.

## GitHub Pages 게시
1. `git add . && git commit -m "deploy landing" && git push`
2. 저장소 Settings → Pages → Branch: main / (root) → Save
3. 1~2분 뒤 `https://<아이디>.github.io/<저장소>/`

## 수정
- 일정·장소·참가비·문구: index.html 텍스트 직접 수정
- 신청 폼 교체: index.html의 form.jotform.com/261632446737058 두 곳을 새 폼 URL로 교체

## 현재 정보
- 2026년 7월 11일 (토) 09:30–18:00 · 한성대학교 컨퍼런스홀 · 570,000원 · 선착순 70명
