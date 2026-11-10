# DeskWidgets 배포

Windows 바탕화면 위젯 **DeskWidgets**의 배포 파일만 올리는 저장소입니다. 소스 코드는 두지 않습니다.

- 새 버전은 [Releases](../../releases)에 올라갑니다. 각 Release에는 실행 파일 zip과 `latest.json`이 있습니다.
- 설치된 프로그램은 6시간마다(낮에만) `releases/latest/download/latest.json`을 확인해서 새 버전이 있으면 내려받아 파일 검증(SHA-256) 후 스스로 업데이트합니다. 설정·계정은 각 PC의 `%APPDATA%\DeskWidgets`에 있어 그대로 유지됩니다.
- 처음 한 번은 zip을 받아 압축을 풀고 `DeskWidgets.exe`를 실행하거나, 이미 설치된 프로그램의 트레이 메뉴 → **업데이트 파일로 설치 (zip 선택)**로 설치합니다.
