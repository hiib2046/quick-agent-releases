# Quick Agent

단축키로 여는 작은 ChatGPT 대화창입니다. 텍스트나 캡처 이미지를 직접 붙여넣고 ChatGPT에 질문할 수 있습니다.

[최신 설치 파일 다운로드](https://github.com/hiib2046/quick-agent-releases/releases/latest)

## 설치와 사용

1. 최신 릴리즈의 `Quick-Agent-VERSION-setup-unsigned.exe`를 다운로드해 설치합니다.
2. 앱에서 ChatGPT 로그인 창을 열고 본인의 계정으로 로그인합니다.
3. `Ctrl + Alt + Space`로 창을 열고, 질문을 입력하거나 `Ctrl+V`로 텍스트와 이미지를 붙여넣습니다.
4. `Enter`로 보내고, 줄바꿈은 `Shift + Enter`를 사용합니다.

현재 설치 파일은 Windows x64용 미서명 테스트 빌드입니다. WebView2 Runtime과 .NET Framework 4.8이 필요합니다. 다른 PC에서의 설치, 로그인과 전송은 사용 환경에서 확인해야 합니다.

## 업데이트

현재는 새 버전 설치 파일을 다운로드해 수동으로 업데이트합니다. 앱 안의 자동 업데이트는 아직 제공하지 않습니다. 새 설치 파일은 기존 앱을 교체하고 사용자 데이터를 유지하도록 구성되어 있지만, 실제 업그레이드 확인은 별도로 필요합니다.

## 데이터

각 사용자가 본인의 ChatGPT 계정으로 로그인합니다. 설치 파일에는 개발자의 로그인 프로필과 개인 대화 기록을 포함하지 않습니다. 로그인 이후 생성되는 사용자 데이터는 각자의 PC에 저장되며 공유하지 마세요.

이 저장소는 설치 파일과 변경 내용을 배포하는 용도입니다. 프로젝트 소스는 별도의 비공개 저장소에서 관리합니다.

## 파일 확인

릴리즈의 `SHA256SUMS.txt`와 설치 파일의 SHA-256 값을 비교할 수 있습니다.

```powershell
Get-FileHash -LiteralPath .\Quick-Agent-VERSION-setup-unsigned.exe -Algorithm SHA256
```
