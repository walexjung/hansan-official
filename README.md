# HANSAN: WAR DIARY — 공식 홈페이지 4.0

실제 사용자 제공 게임 스크린샷 8장과 한국어 오프닝 영상을 포함한 GitHub Pages용 정적 홈페이지입니다.

## 빠른 배포
1. ZIP을 압축 해제합니다.
2. **이 폴더 안의 파일과 하위 폴더를** https://github.com/walexjung/hansan-official 저장소의 최상위에 업로드합니다. ZIP 파일 자체나 `hansan-official-v4` 폴더를 통째로 중첩하여 업로드하지 마세요.
3. `index.html`, `editor.html`, `site-config.js`, `images/`, `video/`가 저장소 최상위에 있어야 합니다.
4. Commit changes를 누르고 GitHub Pages 배포 후 홈페이지를 새로고침합니다.

## 홈페이지에서 이미지 업로드/저장
- `/editor.html` 접속: 로컬 PC의 이미지·동영상을 선택해 미리보기할 수 있습니다.
- Chrome / Edge에서 `홈페이지 폴더 선택`을 누르고 **로컬에 준비한 홈페이지 폴더**를 선택하면 선택 파일을 `images/` 또는 `video/` 아래에 지정된 파일명으로 저장합니다.
- 지원하지 않는 브라우저는 `파일 다운로드`로 파일을 받습니다. 다운로드한 파일은 해당 하위 폴더에 배치합니다.
- **중요:** GitHub Pages는 정적 사이트입니다. `editor.html`만으로 GitHub의 원격 저장소 파일이 변경되지 않습니다. 변경 후 GitHub에 파일을 업로드하고 Commit해야 공개됩니다.

## 피드백 수집
- 메인 페이지는 방문자가 질문 종류·진행 정도·의견을 입력한 후, GitHub Issues의 새 글 작성창으로 이동하도록 구성했습니다. **GitHub 로그인 및 방문자의 최종 제출 클릭이 필요**합니다.
- 방문자에게 로그인 없는 접수 경험을 제공하려면 Google Forms 또는 Tally에서 공개 설문을 만든 다음 `/editor.html`에서 링크를 입력하고 `site-config.js`를 저장·GitHub에 게시하세요.
- 설문 URL이 설정되면 상단의 `피드백 제출하기` 버튼에 연결됩니다. 아래의 구체적 의견 작성폼은 여전히 GitHub 제출이므로, 100% 로그인 없는 접수를 원할 경우 별도 폼 백엔드/임베드 개발이 필요합니다.
- 공개 Github Issues에 개인정보를 쓰지 않도록 방문자에게 경고합니다.

## 포함된 실물 자료
- 한국어/영어 게임 배너
- 한국어 플레이 스크린샷 8장 (`game-01.png`~`game-08.png`)
- 한국어 오프닝 경량화 MP4 (`video/hansan-opening-web.mp4`) 약 14MB, 원본 59MB에서 압축.

데모: https://walexjung.github.io/hansan-demo/
홈페이지: https://walexjung.github.io/hansan-official/
