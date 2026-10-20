# 북부대공 소개 페이지

GitHub Pages에서 바로 올릴 수 있는 정적 사이트 파일입니다.

## 올리는 순서

1. GitHub에서 새 저장소(repository)를 만듭니다.
2. 이 압축 파일을 풀고, 압축 안의 **파일과 폴더 전체**를 저장소의 최상위에 올립니다. `index.html`, `assets`, `music`이 같은 위치에 있어야 합니다.
3. 저장소의 **Settings → Pages**로 이동합니다.
4. **Build and deployment**에서 **Deploy from a branch**를 고르고, `main` 브랜치의 `/(root)`를 선택한 뒤 저장합니다.
5. 잠시 기다리면 같은 Pages 설정 화면에 사이트 주소가 표시됩니다.

## 들어 있는 것

- `index.html`: 페이지 시작 파일
- `style.css`, `app.js`, `characters.js`, `tracks.js`: 화면과 동작
- `assets/`: 인물 그림
- `music/`: 재생목록 음원
- `.nojekyll`: GitHub Pages가 정적 파일을 그대로 제공하도록 하는 설정 파일

## 참고

- 음악 파일도 함께 올라가야 재생됩니다.
- 소개 순서와 전체 재생 순서는 클라우스 → 막스 → 빅터 → 에반 → 데릭 → 카인 → 필립입니다.
- 개별 곡과 소개글은 `tracks.js`, `characters.js`에서 수정할 수 있습니다.
- 저장소에 올린 파일은 공개 저장소의 경우 누구나 열어보고 내려받을 수 있습니다.
