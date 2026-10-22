# 광진 철거 가이드 업로드 안내

## 홈페이지 설정
- 홈페이지: https://gwangjin-demolition-guide.github.io/
- Organization: gwangjin-demolition-guide
- Repository: gwangjin-demolition-guide.github.io
- Visibility: Public
- Branch: main
- Pages Source: Deploy from a branch
- Folder: /(root)

## 처음 업로드하는 순서
1. ZIP을 PC에 다운로드하고 마우스 오른쪽 버튼 → 모두 압축 풀기를 선택합니다.
2. GitHub에서 gwangjin-demolition-guide Organization을 만들거나 해당 Organization으로 이동합니다. 이름 사용 가능 여부는 GitHub에서 확인하세요.
3. 그 안에 gwangjin-demolition-guide.github.io라는 이름으로 저장소를 만들고 Public을 선택합니다. README를 초기 생성해도 됩니다.
4. 저장소의 Code 화면에서 Add file → Upload files를 누릅니다. 처음 만든 빈 저장소는 uploading an existing file 링크를 이용할 수 있습니다.
5. 압축 해제 폴더 자체가 아니라 폴더 안의 index.html, assets 폴더, favicon.png, robots.txt, sitemap.xml, .nojekyll, README.md를 모두 끌어다 놓습니다. index.html이 저장소 최상위에 있어야 합니다.
6. Commit changes로 저장합니다. 기본 브랜치가 main인지 확인합니다.
7. Settings → Pages → Build and deployment에서 Source를 Deploy from a branch로 선택합니다.
8. Branch는 main, 폴더는 /(root)로 선택하고 Save를 누릅니다.
9. Actions에서 Pages 배포가 완료된 뒤 홈페이지 URL을 엽니다. 배포까지 몇 분 걸릴 수 있습니다.
10. 이미지가 위아래 잘림 없이 나오는지 확인하고 이미지의 상단·중간·하단을 눌러 같은 구글폼이 새 탭으로 열리는지 확인합니다.
11. 본문 아래 점포리턴 버튼은 별도의 광진구 철거 안내 페이지로 이동하는지 확인합니다.
12. 모바일에서도 글, 표 스크롤, 이미지, 버튼을 확인하세요.

## 수정·재업로드
index.html은 본문·SEO·링크, assets/css/style.css는 디자인을 담당합니다. 수정한 파일을 같은 경로에 다시 업로드하고 Commit changes를 누릅니다. Pages 배포가 끝난 후 Ctrl+F5로 새로고침합니다. 주소가 바뀌면 canonical, OG, JSON-LD, robots.txt, sitemap.xml의 기준 URL을 모두 바꾸세요.

## 이미지와 링크
- 첨부 ZIP에서 확인한 랜딩 원본: 936×7593px, 783,370바이트. 원본 바이트를 그대로 적용했으며 재압축·크롭·확대 저장하지 않았습니다. HTML width="936" height="7593"을 지정했습니다. 화면에서는 본문 폭에 맞춰 비율을 유지하여 표시합니다.
- 이미지 전체를 표준 a 태그로 감싸 구글폼을 연결했습니다. target=_blank, rel=noopener noreferrer를 적용했습니다.
- 고정 문의 URL: https://docs.google.com/forms/d/e/1FAIpQLSfdzNitwdwclnvlcy6wj8D73z8kBuRSHsiyCp-L3XB9agx9bQ/viewform?usp=header
- 본문 타겟링크: https://store-return.netlify.app/gwangjin-gu-demolition-company/
- 입력의 ttps:// 오타를 https://로 수정했습니다.
- 별도 정사각형 썸네일: assets/images/thumbnail.webp. Open Graph·Twitter 공유 이미지로 사용합니다.
- 파비콘: favicon.png, 64×64px.

## 콘텐츠 확인과 한계
제공된 원고의 핵심 내용을 유지했습니다. 지원금은 공식 검색 결과에서 신규 신청 마감(2026-10-21 18:00)과 일반 한도 안내를 확인했습니다. 상세 공고는 리디렉션 문제로 전체 대조하지 못했습니다. 폐업일별 한도 등 개별 조건은 제공 원고에 기반하므로 공고 원문을 확인하세요. 배너의 지원금·실적·만족도 표현은 검증된 사이트 실적이 아닙니다. 정부 지원 신청은 상담 구글폼과 별개입니다.

기술적 SEO는 초기 HTML 본문, title·description·canonical·OG·Twitter, WebSite·WebPage JSON-LD, robots.txt·sitemap.xml·favicon을 포함합니다. 검색 노출과 순위는 보장하지 않습니다. 소유확인 코드는 발급된 경우에만 별도 추가하세요.

실제 저장소 생성이나 배포는 수행하지 않았습니다. HTML 구조·파일 경로·이미지 크기·링크 속성·ZIP 무결성을 검사했습니다. 브라우저 렌더링 및 실제 외부 폼 접속 검사는 수행하지 않았습니다.

## 썸네일 제작
이미지 생성 기능으로 별도 제작했습니다. 프롬프트: 광진구 철거업체 안내용 정사각형 상업형 이미지. 국내 빈 상가 철거 현장과 안전모·클립보드, 네이비·아이보리·앰버 색상. 제목 광진구 철거업체, 부제 견적보다 먼저 원상복구 범위, 하단 폐업 철거·비용·계약 체크. 지원금 보장과 가짜 실적 제외.
