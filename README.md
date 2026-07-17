# 코스닥 캔들 차트 수정 파일

기존 `kosdaq-candle-dashboard` 저장소에서 다음 파일을 같은 경로에 덮어씁니다.

- `index.html`
- `.github/workflows/update.yml`

새 `index.html`은 코스닥 전용 `data.json` 구조를 사용하며 코스피 코드와 완전히 분리되어 있습니다.

자동 갱신은 평일 한국시간 오후 4시(UTC 07:00), 장 마감 후 종가 기준입니다. 노션 임베드 주소는 그대로 사용합니다.

https://rkdtjdgk0409-dev.github.io/kosdaq-candle-dashboard/
