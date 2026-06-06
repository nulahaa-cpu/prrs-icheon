# PRRSV 통합 분석 대시보드 (경기 이천·여주)

PCR/유전자분석 + 현지 차단방역 설문 통합 대시보드.

## 구성 파일 (모두 저장소 루트에 함께 두기)
- `index.html` — 탭 허브(첫 화면)
- `dash_routes.html` — ① 추정 유입경로 (2층 AHP)
- `dash_tree.html` — ② 계통수 검증
- `dash_map.html` — ③ 계통 × 지리 + 설문 (점 클릭=설문전문, 계통 클릭=공통점)
- `dash_subtree.html` — ④ 계통별 하위 계통수 (NA73·JBNU-22)

지도/계통수 외부 라이브러리는 인터넷 연결 시 표시됩니다.

## 업데이트(GitHub)
변경된 파일을 같은 저장소에 다시 Upload(덮어쓰기) → Commit 하면 같은 주소가 갱신됩니다.
새 파일(dash_subtree.html)이 추가됐으니 이번엔 5개 파일 모두 올리세요.
