# Career The Future - TODO

## Phase 1: DB 스키마 & 글로벌 스타일
- [x] DB 스키마 설계 (analyses 테이블 추가)
- [x] 글로벌 CSS 변수 설정 (Navy Blue 테마)
- [x] Google Fonts 설정 (Inter + Pretendard)

## Phase 2: 랜딩 페이지 & 공통 레이아웃
- [x] 공통 Navbar 컴포넌트 (로고, 네비게이션, 로그인/로그아웃)
- [x] 랜딩 히어로 섹션 (헤드라인, 서브텍스트, CTA 버튼)
- [x] 핵심 기능 소개 섹션 (4가지 기능 카드)
- [x] 서비스 차별성 섹션
- [x] Footer 컴포넌트
- [x] 반응형 레이아웃 (모바일/태블릿/데스크탑)

## Phase 3: 단계별 온보딩 폼
- [x] 온보딩 페이지 라우트 (/analyze)
- [x] Step 1: 목표 자유 텍스트 입력
- [x] Step 2: 현재 수준 선택 (시작 전 / 조금 준비 중 / 실전 준비 중)
- [x] Step 3: 하루 투자 가능 시간 선택 (30분 / 1시간 / 2~3시간 / 4시간+)
- [x] 진행 상태 표시 (Progress Bar)
- [x] 단계 간 애니메이션 전환

## Phase 4: AI 분석 백엔드
- [x] tRPC 라우터 - career.analyze 프로시저 (publicProcedure)
- [x] LLM 호출 - 코칭 메시지 생성
- [x] LLM 호출 - JSON 로드맵 생성 (오늘/이번 주/30일)
- [x] 분석 결과 DB 저장 (로그인 사용자)
- [x] tRPC 라우터 - career.getHistory 프로시저 (protectedProcedure)

## Phase 5: 결과 대시보드 & 히스토리
- [x] 결과 페이지 (/result/:id)
- [x] Future Coach 코칭 메시지 카드
- [x] 분석 지표 표시 (목표 명확성, 실행력, 준비 수준, 시간 활용도)
- [x] 커리어 로드맵 타임라인 (1단계/2단계/3단계)
- [x] 오늘 할 일 / 이번 주 목표 / 30일 목표 카드
- [x] 히스토리 페이지 (/history) - 이전 분석 목록
- [x] 재분석 CTA 버튼

## Phase 6: 테스트 & 마무리
- [x] vitest 테스트 작성 (career.analyze 프로시저)
- [x] 반응형 UI 최종 점검
- [x] 체크포인트 저장
