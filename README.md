# PRRSV 통합 분석 대시보드 (경기 이천·여주)

PCR/유전자분석 + 현지 차단방역 설문을 통합한 PRRSV 유입경로·계통·지리 분석 대시보드입니다.

## 구성 파일
- `index.html` — 탭 허브 (이 파일이 첫 화면)
- `dash_routes.html` — ① 추정 유입경로 (2층 AHP 모델)
- `dash_tree.html` — ② 계통수 검증 (실제 ORF5 트리 vs K-means)
- `dash_map.html` — ③ 계통 × 지리 + 설문 (지도, 점 클릭=설문전문, 계통 클릭=공통점)

※ 4개 파일은 같은 폴더(저장소 루트)에 함께 있어야 합니다.
※ 지도 탭 배경은 인터넷 연결 시에만 표시됩니다.

## GitHub Pages에 올리는 법
1. github.com 로그인 → 우상단 **New repository** → 이름 예: `prrs-icheon`, **Public** 선택 → Create
2. 저장소 화면에서 **Add file ▸ Upload files** → 이 폴더의 `index.html`, `dash_routes.html`, `dash_tree.html`, `dash_map.html`, `README.md` 를 모두 드래그 → 아래 **Commit changes**
3. 상단 **Settings ▸ Pages** → Source: **Deploy from a branch** → Branch: **main / (root)** → **Save**
4. 1~2분 뒤 `https://<아이디>.github.io/prrs-icheon/` 주소 생성 → 이 링크를 공유

## 수정·데이터 추가 시
- 새 파일을 같은 저장소에 **다시 Upload(덮어쓰기) → Commit** 하면 **같은 주소**가 자동 갱신됩니다.
- 새 사이트를 만들 필요 없습니다. URL은 그대로입니다.
