# HANSAN: WAR DIARY — Official Website v2

〈한산: 난중일기〉 공식 홈페이지용 정적 웹사이트입니다. GitHub Pages에서 별도 빌드 없이 동작합니다.

## 게시하기 (기존 hansan-official 저장소 업데이트)

1. 이 ZIP 파일을 압축 해제합니다.
2. GitHub의 `walexjung/hansan-official` 저장소를 엽니다.
3. `Add file` → `Upload files`에서 이 폴더의 **파일과 폴더 내용**을 업로드합니다. `index.html`, `images/hero-sea.svg`, `images/chart-art.svg`, `images/favicon.svg`, `images/social-card.svg`가 저장소 최상위와 `images/` 위치에 배치되어야 합니다.
4. 기존 `index.html`과 `README.md` 파일을 덮어쓰고 `Commit changes`를 클릭합니다. GitHub Pages가 이미 설정되었다면 별도 활성화는 필요하지 않습니다.
5. `https://walexjung.github.io/hansan-official/`에서 변경사항을 확인합니다. 배포 작업은 저장소 `Actions` 탭에서도 확인할 수 있습니다.

> 참고: 기존 파일을 하나씩 수정할 수도 있고 GitHub 웹 업로드로 덮어쓸 수도 있습니다. ZIP 파일 자체를 업로드하면 작동하지 않습니다.

## 실제 게임 화면 추가

다음 파일명을 그대로 사용하여 `images/` 폴더에 올립니다.
- `images/screenshot-1.jpg`: 가장 인상적인 실제 게임 장면
- `images/screenshot-2.jpg`: 대화·퍼즐 등 다른 실제 게임 장면

파일이 아직 없으면 사이트에는 안내용 디자인 카드가 표시됩니다. 해당 카드가 실제 게임 화면인 것처럼 표현하지 않습니다.

## 오프닝 영상 추가

자체 제작한 영상을 `video/hansan-opening.mp4`라는 이름으로 추가하면 영상 플레이어가 나타납니다. 큰 영상 파일은 GitHub 업로드 용량 제한에 걸릴 수 있습니다. 가능하면 720p 또는 1080p H.264 압축본을 사용하고, 큰 영상은 별도 동영상 호스팅으로 전환하세요. `video/README.txt`는 현재 영상 파일이 없음을 의미합니다.

## 링크·문구 확인

- 데모 링크: `https://walexjung.github.io/hansan-demo/`
- 피드백 링크: `https://github.com/walexjung/hansan-official/issues/new` (Issues 활성화 및 GitHub 로그인 필요)
- STOVE: 상점 링크는 심사 완료 후 추가하세요. 상태 문구도 그때 수정해야 합니다.
- AI 활용·역사적 각색 고지 문구는 사실과 맞는지 출시 전 직접 검수하세요.
- 외부 영화 포스터·스틸컷·상표 이미지는 포함하지 않았습니다. 장식 삽화는 게임 스크린샷이 아닙니다.

## 기술 구성

HTML, CSS, 바닐라 JavaScript, SVG. 한국어/영어 전환, 반응형 메뉴, Open Graph 정보, 기본 키보드 접근성을 지원합니다. Google Fonts를 연결했지만 폰트 연결에 실패해도 기본 폰트로 표시됩니다.
