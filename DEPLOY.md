# GitHub Pages 배포 방법

## 1. 저장소 만들기

1. GitHub에 로그인합니다.
2. 오른쪽 위의 `+` 버튼에서 `New repository`를 선택합니다.
3. 저장소 이름을 `mudflat-day`처럼 영문으로 입력합니다.
4. 가장 간단하게 배포하려면 `Public`을 선택합니다.
5. `Create repository`를 누릅니다.

## 2. 파일 올리기

1. 이 압축 파일을 컴퓨터에서 먼저 풉니다.
2. 새 저장소에서 `Add file`을 누르고 `Upload files`를 선택합니다.
3. 압축을 푼 폴더 안의 파일과 `assets` 폴더를 모두 끌어다 놓습니다.
4. `Commit changes`를 누릅니다.

중요: `index.html`이 저장소의 첫 화면에서 바로 보여야 합니다. `mudflat-day-github` 폴더 자체를 한 번 더 올리면 주소가 정상적으로 열리지 않습니다.

## 3. GitHub Pages 켜기

1. 저장소의 `Settings`를 선택합니다.
2. 왼쪽 메뉴에서 `Pages`를 선택합니다.
3. `Build and deployment`의 Source에서 `Deploy from a branch`를 선택합니다.
4. Branch는 `main`, 폴더는 `/(root)`를 선택합니다.
5. `Save`를 누릅니다.

잠시 뒤 다음 형식의 주소가 생성됩니다.

```text
https://깃허브아이디.github.io/저장소이름/
```

## 4. 웹앱 수정본 반영

같은 이름의 파일을 새 버전으로 교체하고 `Commit changes`를 누르면 GitHub Pages가 자동으로 다시 배포합니다.

수정 후 예전 화면이 보이면 브라우저에서 `Ctrl+F5`를 눌러 새로고침합니다.

## 확인할 점

- `index.html`과 `assets` 폴더의 위치를 바꾸지 않습니다.
- 파일 이름의 대문자와 소문자를 바꾸지 않습니다.
- 음원과 영상 파일을 삭제하면 해당 장면의 소리나 움직임이 나오지 않습니다.
- 공개 전 `CREDITS.md`의 음원 출처와 라이선스를 확인합니다.

