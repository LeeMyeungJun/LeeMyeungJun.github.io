# CLAUDE.md — 이명준 포트폴리오 사이트

이 폴더(`portfolio/`)는 `LeeMyeungJun/LeeMyeungJun.github.io` 저장소 안에 있고, GitHub Pages로 배포됩니다.
`master`에 push하면 1~2분 뒤 https://leemyeungjun.github.io/portfolio/ 에 반영됩니다.

## 구조
- `index.html` — 사이트 전체. HTML·CSS·JS가 한 파일에 있습니다. 섹션은 `<!-- ✏️ ... -->` 주석으로 나뉩니다.
- `img/*.webp` — 프로필 사진과 게임 스크린샷.
- `README.md` — 사람이 직접 고칠 때 보는 안내.

## 규칙
- 내용 수정은 HTML 텍스트만 고칩니다. 디자인(CSS)과 애니메이션(JS)은 요청이 있을 때만 바꿉니다.
- 이미지는 `img/`에 파일로 두고 `src="img/파일명"`으로 참조합니다. base64로 HTML에 넣지 않습니다. 새 이미지는 WebP, 긴 변 900px 이하로 줄입니다.
- 프로젝트를 추가·삭제하면 `class="num"`의 번호(`01 / 09` 등)를 전체에 맞게 다시 매깁니다.
- 공개 사이트입니다. 전화번호, 회사 내부 코드·리소스, 비공개 저장소 링크는 넣지 않습니다.
- 저장소 루트의 `app-ads.txt`, `thirty-privacy/`, `README.md`는 다른 앱이 쓰는 파일이므로 건드리지 않습니다.
- 확인되지 않은 수치나 경력은 쓰지 않습니다.

## 확인
1. `python -m http.server 8000`을 저장소 루트에서 실행하고 http://localhost:8000/portfolio/ 를 엽니다.
2. 데스크톱 폭과 휴대폰 폭(약 390px)에서 가로 스크롤이 생기지 않는지, 콘솔 오류가 없는지 봅니다.
3. 커밋 메시지는 `docs: <무엇을 바꿨는지>` 형식으로 쓰고 `master`에 push합니다.
