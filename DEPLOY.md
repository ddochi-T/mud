# GitHub Pages 배포 방법

## 1. 기존 파일 정리

기존 저장소를 계속 사용할 경우, 예전 `index.html`과 `assets` 폴더를 새 배포본과 섞지 않는 것이 좋습니다. 기존 파일을 정리하거나 새 저장소를 만드세요.

## 2. 압축을 풀고 파일 올리기

1. 받은 ZIP 파일을 컴퓨터에서 풉니다.
2. 압축을 풀어 생긴 `mudflat-day-github-onefile` 폴더를 엽니다.
3. 폴더 자체가 아니라 **폴더 안의 파일들**을 선택합니다.
4. GitHub 저장소에서 `Add file` → `Upload files`를 누르고 파일들을 올립니다.
5. `Commit changes`를 누릅니다.

업로드 후 저장소의 첫 화면은 다음처럼 보여야 합니다.

```text
index.html
README.md
DEPLOY.md
CREDITS.md
.nojekyll
```

`mudflat-day-github-onefile/index.html`처럼 바깥 폴더 안에 들어가 있으면 안 됩니다. `assets` 폴더는 필요하지 않습니다.

## 3. GitHub Pages 켜기

1. 저장소의 `Settings`를 엽니다.
2. 왼쪽에서 `Pages`를 선택합니다.
3. `Build and deployment`의 Source를 `Deploy from a branch`로 선택합니다.
4. Branch는 `main`, 폴더는 `/(root)`를 선택합니다.
5. `Save`를 누릅니다.

잠시 뒤 다음 형식의 주소가 나타납니다.

```text
https://깃허브아이디.github.io/저장소이름/
```

GitHub에서 `index.html` 파일을 눌러 보는 화면은 웹앱 실행 화면이 아닙니다. 반드시 `Settings` → `Pages`에 표시된 주소로 접속하세요.

## 4. 화면이 예전과 같을 때

- Pages 배포가 끝날 때까지 1~3분 정도 기다립니다.
- 배포 주소에서 `Ctrl+F5`로 강력 새로고침합니다.
- 모바일에서는 브라우저의 캐시를 지우거나 시크릿 창에서 다시 엽니다.

