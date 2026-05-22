# UmaEasyPlay

우마무스메 게임 편의 도구 — 캡처 / 녹화 / 세미오토 / 웹뷰

---

## 🚀 처음 설치

| 파일 | 설명 |
|---|---|
| `UmaEasyPlay.7z` | 풀버전 전체 패키지 (최초 설치용) |
| `UmaEasyPlay_lite.7z` | 라이트버전 전체 패키지 (최초 설치용) |

원하는 버전의 `.7z` 파일을 다운로드 후 원하는 폴더에 압축 해제하여 사용하세요.

---

## 🔄 업데이트 (프로그램 내 자동)

최초 설치 이후 하위 컴포넌트는 **프로그램 실행 후 해당 탭에서 자동으로 다운로드 / 업데이트**됩니다.

| 파일 | 업데이트 위치 | 설명 |
|---|---|---|
| `UmaEasyPlay.exe` | 프로그램 내 자동 알림 | 메인 프로그램 업데이트 |
| `UmaEasyPlay_lite.exe` | 프로그램 내 자동 알림 | 라이트버전 업데이트 |
| `webview_host.exe` | 친구찾기 탭 | 웹뷰 호스트 |
| `UmaOCR.7z` | 팬수관리 탭 | OCR 엔진 |

---

## 📁 폴더 구조

```
UmaEasyPlay/
  ├── UmaEasyPlay.exe       ← 메인 실행 파일
  ├── UmaData/              ← 임시 데이터 (자동 생성)
  ├── bin/
  │   ├── webview_host.exe  ← 웹뷰 호스트 (프로그램 내 설치)
  │   └── UmaOCR/           ← OCR 엔진 (프로그램 내 설치)
  ├── config.ini            ← 설정 파일
  └── version.ini           ← 버전 정보

UmaEasyPlay_lite/
  ├── UmaEasyPlay_lite.exe  ← 라이트버전 실행 파일
  ├── UmaData/
  ├── bin/
  │   ├── webview_host.exe  ← 웹뷰 호스트 (프로그램 내 설치)
  │   └── UmaOCR/           ← OCR 엔진 (프로그램 내 설치)
  ├── config_lite.ini       ← 설정 파일
  └── version.ini           ← 버전 정보
```

---

## 📋 Releases 구성

| 태그 | 포함 파일 | 용도 |
|---|---|---|
| `main-vX.X.X` | `UmaEasyPlay.7z` | 풀버전 최초 설치 / 업데이트 |
| `lite-vX.X.X` | `UmaEasyPlay_lite.7z` | 라이트버전 최초 설치 / 업데이트 |
| `webview_host-vX.X.X` | `webview_host.exe` | 웹뷰 호스트 업데이트 |
| `umaocr-vX.X.X` | `UmaOCR.7z` | OCR 엔진 업데이트 |

---

## ⚠️ 주의사항

- Windows 10 / 11 전용
- 처음 실행 시 UAC(관리자 권한) 요청이 발생할 수 있습니다
- 백신 프로그램에서 오탐(false positive)이 발생할 경우 예외 처리 후 사용하세요

---

## 📜 라이센스

© 2026 UmaEasyPlay Team. All rights reserved.

- 본 소프트웨어의 무단 복제 · 배포 · 상업적 이용을 금지합니다.
- 개인 사용 목적으로만 사용 가능합니다.
