# 이상향 — Mandal-Art

개인 만다르트 목표 관리 앱. 브라우저에서 바로 실행되며 데이터는 기기 로컬에만 저장됩니다.

**[→ 바로 사용하기](https://bethej2love-lab.github.io/narang-mandart-chart/mandart.html)**

## 기능

- 9×9 만다르트 그리드 (8개 영역 × 8개 항목)
- 항목별 체크 및 누적 밝기로 달성도 시각화
- 연속 달성 스트릭 추적
- 기록 메모 및 날짜별 달력 체크
- 영역별 달성률 통계 (오늘 / 주 / 월)
- 장기 목표 관리 (격월 · 분기 · 연)
- Claude API 기반 AI 코멘트 (본인 API 키 필요)
- 항목명 · 체크 주기 직접 편집 가능
- 모바일 최적화

## 사용법

1. 위 링크 접속
2. 셀 탭 → 체크 / 두 번 탭 → 취소
3. AI 코멘트 탭 → API 키 입력 (기기에만 저장, 유출 없음)
4. 설정 탭 → 항목명과 주기 커스터마이징

## 데이터 저장

모든 데이터는 브라우저 `localStorage`에만 저장됩니다.  
서버 전송 없음. API 키도 동일.

## 기술 스택

Vanilla HTML/CSS/JS · GitHub Pages · Anthropic Claude API
