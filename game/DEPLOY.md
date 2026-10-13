# 플레이 가능한 방탈출 배포 방법

## 로컬 실행
`game/index.html` 파일을 브라우저에서 열면 됩니다. 별도 빌드나 설치가 필요 없습니다.

## GitHub Pages
1. GitHub 프로필 README 저장소(사용자명과 같은 이름의 공개 저장소)에 `README.md`, `assets/`, `game/`을 업로드합니다.
2. 저장소 **Settings → Pages → Build and deployment**에서 **Deploy from a branch**, `main`, `/ (root)`를 선택하고 저장합니다.
3. 공개 주소는 일반적으로 `https://사용자명.github.io/사용자명/game/`입니다. 실제 발급된 주소를 확인하세요.
4. README에서 `YOUR_USERNAME`을 본인 GitHub 사용자명으로 바꿉니다.

주의: README에서 HTML/JavaScript 게임을 직접 실행할 수 없으므로 GitHub Pages로 연결해야 합니다.

## 게임 구조
- 시계 → 4, 책장 → 2, 화분 → 7
- 세 단서를 수집하고 `427` 입력 시 탈출
- 힌트 3단계, 초기화, 사운드 토글, 모바일 화면 지원
- 외부 라이브러리나 추적 스크립트 없음
