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

## 피드백 수집 — 4.1
Google Forms 응답 주소(/viewform)를 메인 피드백 버튼에 설정했습니다. GitHub Issues는 보조 기술 버그 제보 링크로 유지합니다.
방문자에게 혼란을 주던 별도 GitHub 초안 작성폼은 제거했습니다.
Google Forms 설정에서 응답 허용, 로그인 필요 여부, 조직 제한, 1회 응답 제한을 확인하세요. 이 환경에서 설문 응답 화면 접근은 검증되지 않았습니다.
설문 변경은 site-config.js 또는 editor.html에서 가능합니다.

## 포함된 실물 자료
- 한국어/영어 게임 배너
- 한국어 플레이 스크린샷 8장 (`game-01.png`~`game-08.png`)
- 한국어 오프닝 경량화 MP4 (`video/hansan-opening-web.mp4`) 약 14MB, 원본 59MB에서 압축.

데모: https://walexjung.github.io/hansan-demo/
홈페이지: https://walexjung.github.io/hansan-official/
