# 토끼 확장 저장소

Tachimanga, Mihon, Suwayomi, Komikku 계열 앱에서 사용할 수 있는 개인용 한국어 확장 저장소입니다.

## 저장소 주소

```text
https://raw.githubusercontent.com/wankyo83/ntk-fix/main/index.min.json
```

위 주소 하나를 앱의 확장 저장소 설정에 등록하면 아래 확장들을 설치하고 업데이트할 수 있습니다.

## 확장 목록

### 웹툰 — 파란 DC 아이콘

- Newtoki 웹툰
- Toki 웹툰
- Blacktoon 웹툰
- Jjaptoon 웹툰
- SBXH 웹툰
- Naver 웹툰

### 만화 — 노란 DC 아이콘

- Newtoki 만화
- Toki 만화
- SBXH 만화
- 11toon 만화

### 웹툰·만화 통합

- WFWF 웹툰
- WFWF 만화

WFWF는 하나의 APK에 웹툰과 만화 소스가 함께 들어 있어 파란색과 노란색을 조합한 DC 아이콘을 사용합니다.

## 이번 정리 내용

- Newtoki/Toki/SBXH 웹툰·만화 6종에서 Suwayomi AndroidCompat의 `Stub!` 오류를 일으키던 `View.measure/layout` 호출 제거
- 기존 Android Debug 인증서와 패키지 ID를 유지하고 버전 코드를 올려 업데이트 설치 지원
- 중복된 구형 Toki 확장을 제거하고 최신 Toki 웹툰·만화만 유지
- 확장 이름을 `사이트명 + 웹툰/만화` 형식으로 통일
- 웹툰은 파란 DC 아이콘, 만화는 노란 DC 아이콘으로 통일
- 실험용 토끼허브는 배포 목록에서 제외

## 설치·업데이트

1. 앱의 확장 저장소 설정을 엽니다.
2. 위 `index.min.json` 주소를 추가합니다.
3. 저장소 또는 확장 목록을 새로고침합니다.
4. 원하는 확장을 설치하거나 업데이트합니다.

목록이 이전 상태로 보이면 앱을 완전히 종료한 다음 저장소 목록을 다시 새로고침하세요.

이 프로젝트는 Tachimanga, Mihon, Tachiyomi 또는 각 대상 사이트와 제휴하지 않은 개인용 수정본입니다.
