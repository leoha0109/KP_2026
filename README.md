# KP H2 2026 분기말 전망 — 종합 워크북

KP (Korean Paper) 달러 채권 스프레드의 2026년 H2 분기말 전망 모형 종합.

## 사이트 접속

GitHub Pages 활성화 후:
- **URL**: `https://<your-username>.github.io/<repo-name>/`
- 모바일·데스크탑 모두 지원
- 검색엔진 색인 차단 (URL을 아는 경우에만 접속 가능)

## 구성

- **Stage 1** — 학술 방법론 (IMF WP/10/281, WP/13/164, Fed FEDS 2019-074)
- **Stage 2** — ARDL-ECM 파이프라인 합성데이터 검증
- **Stage 3** — Bull / Base / Bear 시나리오 conditional forecast
- **Stage 4** — Block Bootstrap CI (비대칭 꼬리 위험)
- **Stage 5** — Track A + Track B 50:50 앙상블
- **Stage 6** — 표본 확장 (2022.1~) + Tail / Decoupling 시나리오
- **Transmission Calculator** — 인터랙티브 변수 입력 → 즉시 결과
- **패널 토론** — 가상 시뮬레이션 (4 역할 기반 모형 검토)

## 모형

| Track | 방법 | 표본 | 역할 |
|---|---|---|---|
| Track A | Beta-Scenario (일별 첫차분 회귀) | 2022.1~ (1,132 영업일) | 메인 점추정 |
| Track B | ARDL-ECM (월별) | 2014.1~ (146개월) | Misalignment 진단 |
| Ensemble | A·B 50:50 평균 | — | 최종 점추정 |
| Bootstrap | Track A 잔차 5-day block, 5,000 draws | — | CI 산출 |

## 데이터 출처

- Bloomberg KP OAS (KP 국책/공기업, 민간기업)
- Bloomberg / ICE 미국 IG, 아시아 IG, 신흥국 IG OAS
- FRED UST 10Y, MOVE 인덱스
- KOSPI, S&P 500

## 면책 조항

- 본 자료는 내부·연구 목적입니다.
- 패널 토론 섹션은 가상 시뮬레이션이며 실제 인물·기관의 의견이 아닙니다.
- 시나리오 가정과 점추정은 작성 시점의 view를 반영하며, 시장 상황에 따라 변동될 수 있습니다.
- 투자 권유가 아닙니다.

## 라이선스

내부 자료. 외부 배포·인용 시 문의 바랍니다.
