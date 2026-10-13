# IKISE 랜딩페이지 (이랑코치)

정적 HTML 한 페이지. 빌드 과정 없음.

## 구성
- `index.html` — 페이지 전체 (CSS·JS 포함)
- `img/` — 제품·개발자 사진, `og.jpg`(링크 미리보기 이미지)

## Vercel 배포
1. GitHub에 이 폴더 내용을 올린다 (저장소 루트에 index.html이 오도록)
2. vercel.com → Add New → Project → 저장소 Import
3. Framework Preset: **Other**, Build Command·Output Directory 비워둠 → Deploy

## 배포 후 할 일
- `index.html`의 `og:image`를 전체 주소로 교체: `https://<배포주소>/img/og.jpg`
- 카카오톡 상담 버튼: 스크립트 상단 `KAKAO_URL = ""`에 오픈채팅 주소 입력
