# ERP 테스트 (2개 제품 라인)

반도체 장비 제작사용(V4-장비사)과 SMC 대리점용(V4-대리점) 자체 ERP 테스트.

## 버전 지도

V4-장비사 최신: https://728haven-oss.github.io/erp/ (FAT/SAT 검수·마일스톤 트리거·분개장·견적 원가구성 반영)

V4-장비사 보존본: https://728haven-oss.github.io/erp/v4/

V4-대리점 (SMC 전용): https://728haven-oss.github.io/erp/smc/ — SMC 원장(E가·DC율·마진율), 수신함/송출, 이중 거래명세서+차액, 세트조립, 감사 리포트 (샘플 데이터)

구버전 보존: v3 https://728haven-oss.github.io/erp/v3/ · v2 https://728haven-oss.github.io/erp/v2/ · v1 https://728haven-oss.github.io/erp/v1/

## 안내

설계 문서: 저장소의 ERP_*.md 11종. 실데이터 테스트판은 보안상 로컬 파일로만 제공(공개 사이트에는 샘플만).

데이터는 각 브라우저(localStorage)에 저장 — 이전은 앱 내 [백업(JSON)] → [복원]. 테스트 계정: kim/1234(관리자) · lee2/1234(책임자) · park/1234(사용자)
