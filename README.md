# 박호빈 (HOBIN)

기획하고, 프로토타입으로 먼저 검증합니다.<br/>
세 개 만들어 배포했고 그중 둘은 지금도 돌아갑니다. 가장 큰 건 9월 하루 평균 1,040명, 광고비는 0원입니다.

[포트폴리오 PDF](https://drive.google.com/file/d/14xj-RtopAwvstIkpYcmLiTPdMxYEfAOT/view) · [노션 상세](https://little-hearing-108.notion.site/Product-Portfolio-3cbcc7dc54d881fbb735fa86a2034399) · [Velog](https://velog.io/@hobin/posts) · parkhb1181@gmail.com

<br/>

## Shipped

**[FC Detox](https://fcdetox.com)** - FC 온라인 뽑기 · 강화 시뮬레이터 · 2026.07~ 운영 중 · [코드 발췌](https://github.com/parkhb1181/fc-detox-showcase)<br/>
구매 전에 결과를 미리 돌려보는 웹 서비스. 기획·개발·운영 혼자.<br/>
누적 방문 61,169회 · 재방문율 34% · 참여 시간 12분 · 사용자가 올린 소개글 조회 22,465회 · 광고비 0원

**[덕모임](https://duckmoim.com)** - K-pop 오프라인 이벤트 동행 · 2026.08~ 개발 중 · KDT 파이널 프로젝트, 4인 팀 PM·프론트엔드 · [팀 레포](https://github.com/potenup-final/duckmoim-backend)<br/>
주제를 회의로 정하지 않고 후보 3개를 X에 같은 방식으로 올려 비교. 생일카페 정보안이 방문 5배 · 체류 2배로 확정.<br/>
1차 로그인·행사 조회·모집글·신고·백오피스, 2차 채팅·알림으로 범위를 나눠 백엔드 3명과 일정 합의

**[ADsP 합격 패턴](https://adsp-app.vercel.app)** - 자격증 학습 웹앱 · 2026.05~ 운영 중 · [코드 발췌](https://github.com/parkhb1181/adsp-showcase)<br/>
출제 빈도 높은 부분만 남겨 최소 학습으로 합격선을 넘게 하는 서비스. 결제를 만들기 전에 버튼만 띄워 클릭률부터 봤습니다.<br/>
누적 방문 5,262회 · 검색 유입 53% · 재방문율 26.6% · PG 실거래 심사 중

**[GRANDSLAM](https://grandslamlol.vercel.app)** - LoL 올타임 드래프트 시뮬레이터 · 2026.06 종료 · [repo](https://github.com/parkhb1181/LOL)<br/>
3일 스프린트로 배포해 "공유로 계속 퍼질 것"이라는 가설을 검증하고 접었습니다. 공유 버튼 대신 캡처로 퍼진다는 걸 여기서 배웠습니다.<br/>
누적 방문 1,152회 · 재방문 세션 17% (Clarity)

<sub>누적 방문은 Vercel Analytics 일 방문자 합계, 재방문율 · 참여 시간 · 검색 유입은 GA4 기준 (2026.09.23~24)</sub>

<br/>

## How I work

- 만들기 전에 수요를 확인하고, 만든 뒤에는 제 지표부터 의심합니다. 페이지뷰 272만이 중복 집계였던 적이 있습니다
- 어렵다는 기능은 직접 붙여보고 범위를 정합니다
- 반복 구현은 Claude Code에 맡기고, 무엇을 어디까지 만들지는 직접 정합니다

<br/>

## Stack

TypeScript · Next.js (App Router) · React · Tailwind CSS<br/>
Java · Spring Boot · MySQL · Supabase(Postgres) · SQL(Metabase)<br/>
Vercel · Cloudflare R2 · GitHub Actions · GA4 · Microsoft Clarity · Search Console

KDT 백엔드 부트캠프 (원티드 포텐업, 2026.04~09)
