# NTK Fix extension repository

Tachimanga용 NTK 확장 저장소입니다. 장편 작품의 회차 목록에서 모든 페이지를 불러오도록 수정했습니다.

## Tachimanga 저장소 주소

```text
https://raw.githubusercontent.com/wankyo83/ntk-fix/main/index.min.json
```

위 주소가 기본 저장소 주소입니다. 이전에 안내한 `repo.json`과 `repo-v148.json`도 같은 최신 버전을 가리키도록 함께 갱신합니다.

GitHub 원본 캐시 때문에 업데이트가 바로 보이지 않을 때는 아래 현재 버전 주소를 사용할 수 있습니다.

```text
https://raw.githubusercontent.com/wankyo83/ntk-fix/main/repo-v149.json
```

## 업데이트 규칙

- APK를 수정할 때마다 Android `versionCode`와 `versionName`을 올립니다.
- `index.min.json`의 `code`, `version`, `apk`도 같은 버전으로 변경합니다.
- 기존 설치 위에 업데이트할 수 있도록 항상 같은 서명 키를 사용합니다.

이 프로젝트는 Tachimanga, Mihon, Tachiyomi 또는 대상 웹사이트와 제휴하지 않은 개인용 수정본입니다.
