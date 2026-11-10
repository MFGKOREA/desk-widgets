# DeskWidgets 배포

Windows 바탕화면 위젯 **DeskWidgets**의 업데이트 파일만 두는 저장소입니다. 소스 코드는 두지 않습니다.

- `latest.json`: 최신 버전 정보 (버전 · 업데이트 파일 이름 · SHA-256 · Electron 버전)
- `DeskWidgets-<버전>-app.zip`: 작은 업데이트 파일 (프로그램 본체 `resources/app.asar` 만, 수 MB)
- 설치된 프로그램은 켤 때와 6시간마다(낮에만) `latest.json`을 확인해서, 새 버전이면 업데이트 파일을 받아 **SHA-256 검증** 후 스스로 업데이트합니다. 설정·계정은 각 PC의 `%APPDATA%\DeskWidgets`에 있어 그대로 유지됩니다.
- 처음 설치와 Electron 런타임이 바뀌는 업데이트는 전체 설치 파일(약 160MB, GitHub 파일 크기 제한으로 여기에는 두지 않음)이 필요합니다. 받은 zip 은 트레이 메뉴 → **업데이트 파일로 설치 (zip 선택)**으로 설치합니다.
