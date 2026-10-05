# OONGVID 다운로드

전시용 영상 플레이리스트 편집기 + 쇼 재생 프로그램.

## ⬇ [최신 버전 받기](https://github.com/seoyoongweb/OONGVID-releases/releases/latest)

| 컴퓨터 | 받을 파일 |
| --- | --- |
| 윈도우 | `OONGVID-Setup-버전.exe` |
| 맥 (애플 칩 M1~, macOS 14 이상) | `OONGVID-mac-arm64-버전.dmg` |
| 맥 (인텔, macOS 15 이상) | `OONGVID-mac-x64-버전.dmg` |
| 라즈베리파이 | `OONGVID-pi-버전.tar.gz` |

내 맥이 어느 쪽인지: 왼쪽 위 사과 메뉴 → 이 Mac에 관하여 → "칩"에 Apple M…이면 애플 칩, "프로세서"에 Intel이면 인텔.

## 설치

- **윈도우**: 받아서 실행 → 다음 → 설치. 새 버전이 나오면 프로그램이 알아서 받아요.
- **맥**: dmg를 열고 OONGVID를 응용 프로그램 폴더로 끌어다 놓기. 처음 열 때 막히면 시스템 설정 → 개인정보 보호 및 보안 → 맨 아래 **그래도 열기**. 그래도 안 되면 터미널에서 `xattr -cr /Applications/OONGVID.app`
- **라즈베리파이**: 압축 풀고 `install.sh` 더블클릭 → "터미널에서 실행". 업데이트도 같은 방법.

## 오픈소스 라이선스

윈도우·맥 설치 파일에는 mpv(GPL-2.0-or-later)와 FFmpeg(GPL-3.0-or-later)가 고치지 않은 원본 그대로 들어 있어요. 버전·소스 코드 주소·라이선스 전문은 각 릴리스의 `THIRD-PARTY-NOTICES.txt`와 설치한 프로그램의 `licenses` 폴더에 있어요.
