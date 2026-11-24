# 오세진 | 서비스 기획 / PM

그리드위즈에서 전기차 충전 앱, 관제 웹, 충전기를 기획하고 개발팀과 현장 검증을 진행했습니다. SSAFY에서는 팀장과 PM을 맡아 서비스 흐름을 설계하고, 웹과 백엔드 구현에도 참여했습니다.

[sptrain6@naver.com](mailto:sptrain6@naver.com)

## 그리드위즈 | 2022.06–2024.12

- **GRID M** — 첫 유료 충전을 검증하기 위해 결제와 충전기 연동을 우선 개발 범위로 잡았습니다. 제조사, 개발팀과 결제 승인부터 충전 시작까지 현장에서 시험했습니다.
- **SKYBLUE** — 충전소를 찾은 신규 고객이 휴대전화 번호로 인증할 수 있도록 번호 입력부터 인증 완료까지 앱 화면을 설계했습니다.
- **Oaktree** — 내부 관제 웹을 법인 고객에게 제공하기 위해 고객 계정에서 볼 수 있는 충전기 운영 정보와 조작 권한을 정의했습니다.

## SSAFY 팀 프로젝트

### [SceneCrew](https://github.com/userofthefreedom/TIL/blob/master/projects/scenecrew.md) | 공연 운영

공연 중 문제가 생기면 현장 팀원이 음성으로 보고하고, 총괄이 웹에서 대응안을 승인하는 웹·Android 서비스입니다.

6인 팀 PM으로 **수신기 호환, 예약 충돌, 설치 시간**을 고려한 장비 교체 조건을 구현했습니다. 총괄이 승인한 변경은 담당자의 앱에 새 업무로 전달됩니다.

`React` `Capacitor` `Spring Boot` `FastAPI`

### [깃든 Gitden](https://github.com/userofthefreedom/TIL/blob/master/projects/gitden.md) | 첫 오픈소스 기여

입문 개발자가 자기 기술과 난이도에 맞는 GitHub 이슈를 고르고, PR 제출 이후 진행 상태까지 확인하는 웹 서비스입니다.

6인 팀장으로 이슈 추천 점수 로직과 학습 화면을 개선했습니다. 사용자 테스트에서 참가자가 질문에 답하기 전에 배경을 알고 싶어 한다는 점을 확인해 **저장소와 이슈 설명을 먼저 읽도록** 흐름을 바꿨습니다.

`React` `Spring Boot` `FastAPI` `GitHub API` / **SSAFY 공통 프로젝트 우수상**

### [Pickage](https://github.com/userofthefreedom/TIL/blob/master/projects/pickage.md) | npm 패키지 비교

라이브러리를 도입하거나 교체하려는 개발자가 최대 3개 패키지의 사용 추이, 기능, GitHub 활동을 비교하는 웹 서비스입니다.

6인 팀장으로 비교 항목을 설계하고 GitHub 이슈 요약과 PDF·Markdown 보고서 내보내기를 구현했습니다. 같은 프로젝트에서 같은 달에 함께 바뀐 의존성은 **‘관측된 이동’**으로 표시해 교체 후보를 검토할 때 참고할 수 있게 했습니다.

`React` `Spring Boot` `Python` `DuckDB` `Apache Spark`

### [FirstHome Navigator AI](https://github.com/userofthefreedom/FirstHome_Navigator_AI) | LH 청약 추천과 자금 계획

첫 주택을 준비하는 사용자가 조건에 맞는 LH 공공분양 공고를 찾고, 주택형별 납부 일정과 월 준비 금액을 확인하는 웹 서비스입니다.

3인 팀장으로 청약 추천과 자금 계산 기준을 설계하고 백엔드를 구현했습니다. 공고문에서 뽑은 **납부 회차와 금액**은 필수 항목과 합계를 확인한 뒤 자금 계획에 반영하도록 했습니다.

`Vue 3` `Django REST Framework` `pdfplumber` `pypdf` / **SSAFY 관통 프로젝트 우수상**
