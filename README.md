# NTK Fix 확장 저장소

Tachimanga, Mihon, Komikku 계열 앱에서 사용할 수 있는 개인용 한국어 확장 저장소입니다.

## 저장소 주소

아래 주소 하나를 확장 저장소로 등록하면 Newtoki, Toki, Black toon, Jjaptoon webtoon 확장 4개를 설치하고 업데이트할 수 있습니다.

```text
https://raw.githubusercontent.com/wankyo83/ntk-fix/main/index.min.json
```

## 포함된 확장

| 확장 | 버전 | 아이콘 | 기본 주소 | 비고 |
|---|---:|---|---|---|
| Newtoki | 1.4.28 | 흰색 토끼 | `newtoki1.org` | Manga 실제 본문 이미지 구조 대응, 뷰어·다운로드 목록 수집 수정 |
| Toki | 1.4.34 | 파란색 토끼 | `toki31.com` | Manga 실제 본문 이미지 구조 대응, Newtoki 강제 우회 제거 |
| Black toon | 1.4.6 | 검정색 토끼 | `blacktoon417.com` | 공식 주소 안내 페이지에서 최신 도메인 자동 감지 |
| Jjaptoon webtoon | 1.4.1 | 빨간색 토끼 | `www.jjaptoon004.com` | 공식 `domain.json`에서 최신 도메인 자동 감지, 전체 회차 지원 |

## 설치 방법

1. 앱의 확장 또는 저장소 설정 화면을 엽니다.
2. 위의 `index.min.json` 주소를 저장소 URL로 추가합니다.
3. 저장소를 새로고침합니다.
4. 표시되는 확장을 각각 설치합니다.

저장소 목록이 이전 상태로 보이면 앱을 완전히 종료한 뒤 저장소를 다시 새로고침하세요.

> Android에서 기존 NTK 1.4.11을 설치했던 경우 Newtoki 1.4.12 이상은 서명키가 달라 자동 업데이트되지 않을 수 있습니다. 이때 기존 NTK 확장만 삭제한 뒤 Newtoki를 다시 설치하세요. 보관함과 열람 기록은 만화 앱에 저장되지만 확장 도메인 설정은 다시 입력해야 할 수 있습니다.

## 자동 주소 변경

- Toki 주소가 변경되면 확장 설정에서 도메인 숫자를 변경할 수 있습니다.
- Black toon은 공식 주소 안내 페이지에서 최신 바로가기 주소를 확인합니다.
- Jjaptoon webtoon은 `https://www.jjaptoon.com/data/domain.json`의 공식 최신 주소를 확인합니다.
- 확인한 주소는 6시간 동안 캐시하므로 매 요청마다 안내 페이지를 다시 불러오지 않습니다.

## 안내

이 저장소는 Tachimanga, Mihon, Komikku 또는 대상 사이트와 제휴하지 않은 개인용 수정본입니다.
