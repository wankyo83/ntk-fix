# NTK 확장 저장소

Tachimanga, Mihon, Komikku 계열 앱에서 사용할 수 있는 개인용 한국어 확장 저장소입니다.

## 저장소 주소

아래 주소 하나를 등록하면 확장 5개를 설치하고 업데이트할 수 있습니다.

```text
https://raw.githubusercontent.com/wankyo83/ntk-fix/main/index.min.json
```

## 배포 구성

| 확장 | 버전 | 아이콘 | 기능 |
|---|---:|---|---|
| Newtoki | 1.4.29 | 흰색 토끼 | Webtoon 전용 |
| ntk manga_v1 | 1.4.1 (초기 v1) | 흰색 토끼 | Manga 전용, 기본 이미지 뷰어와 다운로드 지원 |
| Toki | 1.4.35 | 파란색 토끼 | Webtoon 전용 |
| Black toon | 1.4.6 | 검정색 토끼 | Webtoon, 최신 도메인 자동 감지 |
| Jjaptoon webtoon | 1.4.1 | 빨간색 토끼 | Webtoon, 최신 도메인 자동 감지 |

## 변경 사항

- 기존 Newtoki 확장에서 NTK Manga 소스를 제거했습니다.
- 기존 Toki 확장에서 Toki Manga 소스를 제거했습니다.
- 새 Manga 코드를 별도 패키지 `ntk manga_v1`으로 배포합니다.
- `ntk manga_v1`은 회차 이미지를 앱 기본 뷰어에 전달하며 앱 다운로드 기능과 같은 이미지 목록을 사용합니다.

## 설치

1. 앱의 확장 저장소 설정을 엽니다.
2. 위 `index.min.json` 주소를 추가합니다.
3. 저장소를 새로고침합니다.
4. 필요한 확장을 각각 설치하거나 업데이트합니다.

기존 Manga 보관함은 소스 ID가 변경되므로 `ntk manga_v1`으로 마이그레이션해야 할 수 있습니다.
