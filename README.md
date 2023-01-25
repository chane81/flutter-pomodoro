# pomodoro

Flutter ui challenge - pomodoro

## 환경

- version: 3.3.10

## 버전 관리 fvm 으로 사용하게 설정

- 참고
  - https://fvm.app
- setup
  ```bash
  $ fvm install 3.3.10
  $ fvm list
  $ fvm use 3.3.10
  ```
- vscode/settings.json 추가
  ```json
  // fvm 설정
  "dart.flutterSdkPath": ".fvm/flutter_sdk",
  "search.exclude": {
    "**/.fvm": true
  },
  "files.watcherExclude": {
    "**/.fvm": true
  }
  ```
- .gitignore 추가
  ```bash
  # fvm
  .fvm/flutter_sdk
  ```
