# 박건민 — 게임 개발자 포트폴리오

정적 포트폴리오 사이트입니다. HTML, CSS, 바닐라 JavaScript만 사용하며 외부 이미지나 런타임 프레임워크에 의존하지 않습니다.

## 파일 구성

- `index.html`: 페이지 내용, 제목, 검색·공유용 메타 정보
- `styles/main.css`: 색상, 레이아웃, 반응형 스타일, 모션
- `scripts/main.js`: 모바일 메뉴와 스크롤 인터랙션
- `favicon.svg`: 브라우저 탭 아이콘
- `README.md`: 수정 및 배포 안내
- `vite.config.ts`: Replit 미리보기용 설정 (GitHub Pages에는 필요하지 않음)

## 수정할 내용

- `index.html`: 소개 문구, 기술, 활동, 프로젝트, 연락처를 수정합니다. 활동의 기간·세부 내용과 프로젝트는 실제 정보를 추가한 뒤 빈 안내를 바꿔 주세요.
- `styles/main.css`: 색상은 파일 상단의 CSS 변수에서 조정할 수 있습니다.
- `scripts/main.js`: 모바일 메뉴, 현재 섹션 표시, 스크롤 등장 효과를 관리합니다.

모든 페이지 에셋 링크는 상대 경로이므로 저장소 하위 경로에서도 동작합니다.

## GitHub Pages 배포

이 포트폴리오 폴더 안의 `index.html`, `styles/`, `scripts/`, `favicon.svg` 파일을 전용 GitHub 저장소의 최상위 경로에 올립니다. 전체 Replit 워크스페이스를 그대로 올리는 경우에는 이 파일들이 저장소 최상위가 아니므로, 사이트 파일만 복사해 주세요.
1. 해당 파일들을 GitHub 저장소의 최상위 경로에 커밋합니다.
2. 저장소의 **Settings → Pages**로 이동합니다.
3. **Build and deployment**에서 **Deploy from a branch**를 선택합니다.
4. 사이트 파일이 들어 있는 브랜치(예: `main`)와 폴더(`/ (root)`)를 지정하고 저장합니다.
5. Pages가 제공하는 주소에서 게시 결과를 확인합니다.

일반 GitHub Pages 배포에는 빌드나 백엔드가 필요하지 않습니다. Replit 미리보기는 워크스페이스 최상위에서 `pnpm --filter @workspace/geonmin-portfolio run dev`로 실행할 수 있습니다.
