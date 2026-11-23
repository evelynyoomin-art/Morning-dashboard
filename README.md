# 우리집 모닝 대시보드 · 태리 · 태민

태리(7세)·태민(4세) 아침 루틴 대시보드를 아이패드 사파리에서 '홈 화면에 추가'해 쓰기 위한 정적 페이지입니다.

- 주소: https://evelynyoomin-art.github.io/morning-dashboard/
- `index.html` 하나에 폰트·그림·스크립트가 모두 들어 있어 인터넷 없이도 한 번 열린 뒤에는 빠르게 뜹니다.
- 루틴 체크 상태는 기기(사파리)의 로컬 저장소에 저장됩니다. 기기마다 따로 기록됩니다.
- 검색 노출을 막아 두었습니다(`robots.txt`, `noindex`).

## 배포 방식

`main` 브랜치에 푸시하면 GitHub Actions(`.github/workflows/pages.yml`)가 자동으로 Pages에 배포합니다.
대시보드를 고칠 때는 `index.html`을 바꿔 푸시하면 1~2분 뒤 반영됩니다.
