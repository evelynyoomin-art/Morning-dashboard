# 우리집 모닝 대시보드 · 태리 · 태민

태리(7세)·태민(4세) 아침 루틴 대시보드를 아이패드 사파리에서 '홈 화면에 추가'해 쓰기 위한 정적 페이지입니다.

- 주소: https://evelynyoomin-art.github.io/Morning-dashboard/
- `index.html` 하나에 폰트·그림·스크립트가 모두 들어 있어, 한 번 열린 뒤에는 인터넷이 느려도 빠르게 뜹니다.
- 루틴 체크 상태와 준비물 메모는 그 기기의 브라우저 저장소(localStorage)에 저장됩니다. 기기마다 따로 기록됩니다.
- 검색 노출을 막아 두었습니다(`robots.txt`, `noindex`).

## 저녁 대시보드 (`evening.html`)

- 주소: https://evelynyoomin-art.github.io/Morning-dashboard/evening.html
- 태리·태민의 저녁 8단계 루틴과 "꿈나라 출발"(21:30) 카운트다운, 8개를 모두 누르면 꿈나라 축하 화면이 뜹니다.
- 홈 화면 아이콘은 `evening-icon.png`(달·별·구름). 체크 상태와 준비물 메모는 아침 대시보드와 따로 저장됩니다.
- 고칠 때는 `evening.html`을 바꿔 `main`에 푸시하면 됩니다.

## 운영 방법

- GitHub Pages: Settings → Pages → Source "Deploy from a branch", Branch `main` / `(root)`.
- 대시보드를 고칠 때는 `index.html`을 바꿔 `main`에 푸시하면 1~2분 뒤 자동으로 다시 배포됩니다.
