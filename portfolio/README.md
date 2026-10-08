# 이명준 포트폴리오 사이트

이 폴더는 GitHub Pages로 배포됩니다. `master` 브랜치에 수정이 올라가면 1~2분 뒤 사이트에 자동으로 반영됩니다.

- 사이트 주소: https://leemyeungjun.github.io/portfolio/

## 수정하는 방법

1. GitHub에서 `portfolio/index.html`을 열고 연필 아이콘(Edit)을 누릅니다.
2. `✏️` 주석으로 섹션이 나뉘어 있습니다. 바꾸고 싶은 섹션에서 글자만 고칩니다.
3. 아래쪽 **Commit changes**를 누르면 1~2분 뒤 사이트에 반영됩니다.

## 자주 바꾸는 곳

| 바꿀 내용 | 찾을 곳 |
|---|---|
| 상단 소개 문구 | `class="lead"` |
| 직함 문구(타이핑 애니메이션) | 스크립트의 `const phrases=[...]` |
| 숫자 카드 (20+, 10만+, GOLD) | `class="stats"` |
| 학력·경력 | `class="hist"` |
| 프로젝트 설명 | `<article class="feat rv">` 블록. 제목은 `<h3>`, 목록은 `<li>` |
| 프로젝트 번호 | `class="num"` (예: `01 / 09`) |
| Unity·툴 카드 | `<article class="card rv">` 블록 |
| 이메일 | `id="mail"` |

## 이미지 바꾸기

`portfolio/img/` 폴더에 같은 이름으로 새 이미지를 올리면 교체됩니다. 새 이미지를 추가했다면 `index.html`의 `<img src="img/파일이름">` 경로를 맞춰 주세요.

| 파일 | 쓰이는 곳 |
|---|---|
| `profile.webp` | 프로필 사진 |
| `bubble-1, 2, 4.webp` | 버블헌터 오리진 |
| `crown-1, 3, 4.webp` | 왕관을 지켜라 |
| `themonster-1~2.webp` | TheMonster |
| `thefuture-1~4.webp` | TheFuture |
