# GitHub Pages 개발자 포트폴리오

빌드 과정 없이 GitHub Pages에 바로 올릴 수 있는 정적 원페이지 개발자 포트폴리오입니다.

## 구성

- `index.html`: 소개, 기술 스택, 프로젝트, 타임라인, 연락처
- `styles.css`: 반응형 레이아웃과 시각 스타일
- `script.js`: 모바일 메뉴, 현재 섹션 표시, 간단한 인터랙션
- `assets/portfolio-visual.png`: 첫 화면 이미지 자산

## 내 정보로 바꾸기

아래 값을 먼저 검색해서 본인 정보로 교체하세요.

- `<YOUR_NAME>`
- `YOUR_GITHUB_ID`
- `YOUR_LINKEDIN_ID`
- `your.email@example.com`
- 프로젝트 제목, 설명, Demo/GitHub 링크

## 로컬 확인

`index.html` 파일을 브라우저로 열면 됩니다. 별도 서버나 빌드 명령은 필요하지 않습니다.

## GitHub Pages 배포

1. GitHub에서 새 저장소를 만듭니다.
2. 이 폴더의 파일을 저장소 루트에 업로드하거나 `git push`로 올립니다.
3. 저장소의 `Settings`로 이동합니다.
4. 왼쪽 메뉴에서 `Pages`를 선택합니다.
5. `Build and deployment`에서 `Source`를 `Deploy from a branch`로 설정합니다.
6. `Branch`를 `main`, 폴더를 `/ (root)`로 선택하고 저장합니다.
7. 잠시 후 표시되는 Pages 주소로 접속해 `index.html`, `styles.css`, `script.js`, 이미지가 정상 로드되는지 확인합니다.

개인 메인 페이지 주소를 쓰려면 저장소 이름을 `YOUR_GITHUB_ID.github.io` 형식으로 만들면 됩니다.
