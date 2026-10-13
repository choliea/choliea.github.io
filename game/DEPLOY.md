# 플레이 가능한 방탈출 배포 방법

## 로컬 실행
`game/index.html` 파일을 브라우저에서 열면 됩니다. 별도 빌드나 설치가 필요 없습니다.

## GitHub Pages
1. GitHub 프로필 README 저장소(사용자명과 같은 이름의 공개 저장소)에 `README.md`, `assets/`, `game/`을 업로드합니다.
2. 저장소 **Settings → Pages → Build and deployment**에서 **Deploy from a branch**, `main`, `/ (root)`를 선택하고 저장합니다.
3. 공개 주소는 일반적으로 `https://choliea.github.io/game/` (저장소가 `choliea/choliea`인 경우)입니다. 실제 발급된 주소를 확인하세요.
4. README의 게임 링크는 `https://choliea.github.io/game/`으로 설정되어 있습니다.
5. **중요:** `game/index.html` 파일이 `choliea/choliea` 저장소의 최상위 `game/` 경로에 올라가 있어야 합니다. GitHub 프로필에 README가 표시되는 것만으로 Pages가 활성화된 것은 아닙니다.
6. `choliea.github.io`라는 별도 저장소를 Pages 사이트로 사용하는 경우, 그 저장소에도 `game/` 폴더를 배포해야 합니다.
7. 배포 후 `https://choliea.github.io/game/index.html`을 직접 확인하세요. Pages 빌드가 끝나기까지 잠시 걸릴 수 있습니다.

주의: README에서 HTML/JavaScript 게임을 직접 실행할 수 없으므로 GitHub Pages로 연결해야 합니다.

## 게임 구조
- 시계 → 4, 책장 → 2, 화분 → 7
- 세 단서를 수집하고 `427` 입력 시 탈출
- 힌트 3단계, 초기화, 사운드 토글, 모바일 화면 지원
- 외부 라이브러리나 추적 스크립트 없음
