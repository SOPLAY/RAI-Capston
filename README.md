# [RAI-Capston](https://soplay.github.io/RAI-Capston/)

RAI Capstone Design GIt Pages web

### Notification!!!

- `날씨 관련 페이지는 현재 개발 진행중`

## Logs

- 2021 11 20

  - 특정작물 실시간 시세 연동 (api 비동기 병렬 처리)
  - loading 표기 수정
  - api 비동기 병렬 로직 오류로 인해 직렬처리 되던것 변경( 800ms -> 200ms 개선)

- 2021 11 21

  - 비동기 로직 개선 (200ms -> 100ms내외)
  - 로그인 실패시 로직 변경

- 2021 11 25

  - Chart로직 개선 1~5개 항목 추가

- 2021 11 25

  - Chart로직 중복 증식 오류 패치

- 2021 12 01

  - 회원가입 페이지 구현 (실연동 X ) 및 오류 처리

- 2021_12_05

  - proxy 설정 및 날씨 정보 ajax요청 로직 변경
  - 날씨 정보 rss 파싱
  - 날씨정보 서울ㆍ인천ㆍ경기도 지역중 상세 도시 선택가능 처리
  - proxy 파일 버그로 인한 긴급 fix
  - proxy 개발 서버 / 배포 cros 오류 수정

- 2021_12_06

  - 회원가입 경고창 표시 변경
