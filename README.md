# 가로세로 낱말퀴즈 — 배포 빌드

**빌드 ID**: `20260402_112543`  
**파일**: `index.html` (단일 파일, 1.38MB)

## 실행 방법

`index.html` 파일을 iPad Safari 또는 Chrome에서 열면 됩니다.  
인터넷 연결 없이 **완전 오프라인**으로 작동합니다.

## 기술 사양

| 항목 | 값 |
|------|-----|
| 파일 구조 | 단일 HTML (이미지 Base64 인라인 포함) |
| 외부 의존성 | **없음** |
| 터치 방식 | touchstart 이벤트 (300ms 딜레이 없음) |
| 뷰포트 | 100dvh / -webkit-fill-available |
| 폰트 | Apple SD Gothic Neo / Malgun Gothic (시스템) |
| 대상 기기 | iPad Safari, Android Chrome |

## 게임 내용

- 한국어 낱말 퍼즐 15개 (5레벨 × 3판)
- Z-스테어케이스 격자 구조, 단어당 9개
- 보석 💎 · 열쇠 🔑 · 컬렉션 시스템
- 힌트: 첫 글자 공개 (💎5 소모)

## 원본 대비 변경사항

1. Google Fonts CDN 제거 → 시스템 폰트
2. 터치 이벤트 전환 (onclick → touchstart)
3. iPad Safari 뷰포트 수정
4. 격자 셀 최솟값 48px
5. 소프트키보드 레이아웃 안정화
6. 컬렉션 캐릭터 이미지 (아/야/이 용사, 천지, 개벽)
7. 힌트 시스템 (틀렸지롱 캐릭터)
