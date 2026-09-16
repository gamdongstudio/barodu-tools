# BARODU Tools

링크에서 기존 정보를 가져올 때 쓰는 **BARODU 공식 도구**입니다.

[BARODU PAGE MAKER](https://barodu-page-maker.pages.dev)에서 네이버 블로그 · 네이버 스마트플레이스 · 홈페이지 주소를 넣으면,
BARODU Tools가 이 컴퓨터에서 그 페이지를 열어 글과 사진을 읽어 제작기에 넘겨줍니다.

사진 직접 올리기, 직접 입력 같은 기본 제작 기능은 BARODU Tools 없이도 쓸 수 있습니다.

## 다운로드

**[BARODU Tools 최신 버전 받기](https://github.com/gamdongstudio/barodu-tools/releases/latest/download/BARODU-Tools-Setup.exe)**

또는 [Releases](https://github.com/gamdongstudio/barodu-tools/releases) 에서 버전별로 받을 수 있습니다.

## 설치

1. `BARODU-Tools-Setup.exe` 를 실행합니다.
2. 처음 실행할 때 Windows 확인 창이 뜨면 **추가 정보 → 실행** 을 누릅니다.
   (아직 코드 서명 인증서를 붙이지 않은 파일이라 이 창이 뜹니다)
3. 설치가 끝나면 화면 오른쪽 아래 시계 옆에 BARODU Tools 아이콘이 생깁니다.

관리자 권한은 필요하지 않습니다. 이 사용자 계정에만 설치됩니다.

## 이 프로그램이 하는 일

- 사용자가 직접 넣은 **공개 페이지 주소 한 개**를 열어 글과 사진 주소를 읽습니다.
- 읽은 내용은 이 컴퓨터 안에서만 제작기로 넘어갑니다. BARODU 서버로 보내지 않습니다.
- 네이버 아이디·비밀번호를 받지 않고 저장하지 않습니다.
- 이 컴퓨터(127.0.0.1)와 공식 제작기 주소에서 온 요청에만 답합니다.

## 지우기

Windows 설정 → 앱 → **BARODU Tools** → 제거

## 파일 확인 (SHA-256)

각 Release 설명에 설치파일의 SHA-256 값이 적혀 있습니다. 받은 파일이 같은지 확인하려면 PowerShell에서:

```powershell
Get-FileHash .\BARODU-Tools-Setup.exe -Algorithm SHA256
```
