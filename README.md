# UmaEasyPlay

우마무스메 게임 편의 도구 — 캡처 / 녹화 / 세미오토 / 웹뷰

---

## 📦 배포 파일

| 파일 | 설명 |
|---|---|
| `webview_host.exe` | 인게임 웹뷰 호스트 (친구찾기 · 스킬검색 · 상성계산기 · 주자설정) |
| `UmaOCR.7z` | OCR 엔진 (팬수관리) |

---

## 🔧 설치 방법

### webview_host.exe (풀버전 · 라이트버전 공통)
1. 프로그램 실행 후 **친구찾기** 탭 이동
2. 다운로드 버튼 클릭 → `bin/` 폴더 선택
3. 자동 설치 완료

### UmaOCR (풀버전 · 라이트버전 공통)
1. 프로그램 실행 후 **팬수관리** 탭 이동
2. 다운로드 버튼 클릭 → `bin/` 폴더 선택
3. 자동 압축 해제 및 설치 완료

---

## 📁 폴더 구조

```
UmaEasyPlay/
  ├── UmaEasyPlay.exe       ← 메인 실행 파일
  ├── UmaData/              ← 임시 데이터 (자동 생성)
  ├── bin/
  │   ├── webview_host.exe  ← 웹뷰 호스트
  │   └── UmaOCR/           ← OCR 엔진
  ├── config.ini            ← 설정 파일
  └── version.ini           ← 버전 정보

UmaEasyPlay_lite/
  ├── UmaEasyPlay_lite.exe
  ├── UmaData/
  ├── bin/
  │   ├── webview_host.exe
  │   └── UmaOCR/
  ├── config_lite.ini
  └── version.ini           ← 추가
```

---

## 📋 버전 정보

Releases 탭에서 각 컴포넌트의 최신 버전을 확인하세요.

- `webview_host-vX.X.X` — 웹뷰 호스트 업데이트
- `umaocr-vX.X.X` — OCR 엔진 업데이트
- `main-vX.X.X` — 메인 프로그램 업데이트

---

## ⚠️ 주의사항

- Windows 10 / 11 전용
- 처음 실행 시 UAC(관리자 권한) 요청이 발생할 수 있습니다
- 백신 프로그램에서 오탐(false positive)이 발생할 경우 예외 처리 후 사용하세요

---

## 📜 라이센스

© 2025 UmaEasyPlay Team. All rights reserved.

- 본 소프트웨어의 무단 복제 · 배포 · 상업적 이용을 금지합니다.
- 개인 사용 목적으로만 사용 가능합니다.

