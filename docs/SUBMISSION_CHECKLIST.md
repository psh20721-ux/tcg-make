# 제출 체크리스트

작성/검증 상태: 2026-11-16

| 제출 항목 | 현재 상태 | 자료/남은 작업 |
|---|---|---|
| 바닐라 프론트 3개 이상 메뉴 | 구현·로컬 브라우저 검증 완료 | 홈/덱 탐색/AI 상담/출처 |
| Python api/ 구조 | 구현·단위/로컬 HTTP 검증 완료 | api/recommend.py, backend/coach.py |
| 실제 AI API 호출 코드 | 구현 완료, 실 호출 대기 | API 키 설정 후 직접 입력→결과 확인 |
| 로딩·빈 입력·오류·시간 초과 처리 | 자동 검증 완료 | 모의 제공자/로컬 오류 테스트 |
| 모바일/태블릿/PC | 로컬 검증 완료 | 390/768/1440px |
| GitHub 코드 업로드·커밋 이력 | 사용자가 Codespaces에서 진행 예정 | https://github.com/psh20721-ux/tcg-make |
| Vercel 공개 URL | 미배포 | docs/DEPLOYMENT.md 순서로 배포 |
| 공개 URL에서 실제 AI 검증 | 미검증 | 배포·환경 변수 설정 이후 확인 |
| README/환경 변수/배포 안내 | 작성 완료 | README.md, .env.example |
| 서비스 기획서 | 작성 완료 | docs/SERVICE_PLAN.md |
| 코드 구조·학습 목표 설명 | 작성 완료 | docs/ARCHITECTURE.md |
| 데스크톱/모바일 스크린샷 | 로컬 캡처 완료 | evidence/screenshots/ |
| AI 상담 장면 | 모의 응답 캡처 완료, 실제 AI 캡처 대기 | ai-mock-flow.png는 실제 AI 증빙 아님 |
| AI 코딩 도구 과정 | 실제 대화 발췌·작업 기록 포함 | evidence/AI_CODING_PROCESS.md |

## 제공 스크린샷의 의미

- `desktop-home.png`: 데스크톱 홈.
- `mobile-home.png`: 모바일 홈.
- `mobile-decks.png`: 모바일 덱 목록.
- `ai-not-configured.png`: 실제 API 키 미설정 시 503 오류 안내 화면.
- `ai-mock-flow.png`: **검증용 모의 API 응답**, 실제 Google Gemini 호출 아님. 화면에도 표시.

실제 AI 호출을 한 뒤 키·개인정보 없이 새 스크린샷을 제출 패키지에 추가해야 합니다. `.gitignore`에서 `live-*`를 기본 제외하므로 검토 후 필요하면 `git add -f evidence/screenshots/live-ai.png`로 명시적으로 추가합니다.

## 제출 전 본인이 채울 항목

- 실제 Vercel URL:
- GitHub 최종 커밋 URL:
- 공개 URL 검증 날짜:
- 실제 AI 호출 성공 날짜/모델:
- 실제 AI 화면 증빙 파일:

완료되지 않은 항목을 완료로 바꾸거나 모의 응답을 실제 AI 결과로 표시하지 않습니다.

