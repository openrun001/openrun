# OPEN RUN 무료 홈페이지

이 폴더는 GitHub Pages에 그대로 업로드할 수 있는 정적 홈페이지입니다.

## 1. 사진 교체

`assets` 폴더 안의 아래 파일을 같은 파일명으로 교체하세요.

- `hero.jpg` : 첫 화면 대표사진, 가로형 권장
- `portfolio-seafood.jpg` : 회·해산물
- `portfolio-meat.jpg` : 고기·구이
- `portfolio-korean.jpg` : 한식·찌개
- `portfolio-cafe.jpg` : 카페·디저트

권장 크기:
- hero.jpg: 2400 × 1600px 이상
- 포트폴리오: 긴 변 1600px 이상
- JPG 품질 80~90%

## 2. 연락처 변경

`index.html`을 메모장으로 열고 `01043580920`을 검색하여 원하는 번호로 변경하세요.

## 3. GitHub Pages 무료 배포

1. github.com 회원가입
2. 오른쪽 위 + 버튼 → New repository
3. Repository name에 `openrun` 입력
4. Public 선택 → Create repository
5. 이 폴더 안의 파일 전체를 업로드
6. 저장소 상단 Settings → Pages
7. Build and deployment의 Source를 `Deploy from a branch`
8. Branch를 `main`, 폴더를 `/root`로 선택 후 Save
9. 잠시 후 `https://사용자이름.github.io/openrun/` 주소로 공개

## 4. 기존 구글 사이트에서 연결

기존 구글 사이트 첫 화면의 버튼 링크를 새 GitHub Pages 주소로 연결하거나,
새 홈페이지 주소만 고객에게 전달하면 됩니다.

## 5. 수정 가능한 부분

- 문구: index.html
- 색상/글씨 크기: styles.css
- 사진: assets 폴더
- 움직임: script.js
