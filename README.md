# 도도 대시보드 (dodo_dashboard)

4차 실시간 모의 트레이딩 봇팀(28팀 · 프로젝트 A·B·C·H·E)의 **결과 화면 전용** 저장소입니다.

- 보기: <https://areeahri-create.github.io/dodo_dashboard/>
- 구성: `index.html` 한 파일. 데이터 스냅샷이 파일 안에 들어 있어 열기만 하면 바로 표시됩니다.
- 갱신: PC 팀장 **도도**(`pc_runner.py`)가 15분마다 새 화면을 만들어 이 저장소의 `index.html` 로 올립니다. 링크는 그대로 두고 새로 고침만 하면 됩니다.
- 안전: 실제 자금·실제 주문·거래소 키·계좌번호·개인정보는 담기지 않습니다. 가격은 바이낸스 공개 시세, 체결·손익은 전부 컴퓨터 안에서 계산한 **모의(페이퍼) 트레이딩** 결과입니다.
- 코드·기록 저장소는 비공개인 <https://github.com/areeahri-create/dodo> 에 따로 있습니다.

## GitHub Pages 켜기 (처음 한 번)

이 저장소가 공개 화면을 서빙하려면 Pages 가 켜져 있어야 합니다.

1. 저장소 → **Settings** → 왼쪽 **Pages**
2. **Build and deployment → Source**: `Deploy from a branch`
3. **Branch**: `main`, 폴더: `/ (root)` → **Save**
4. 1~2분 뒤 <https://areeahri-create.github.io/dodo_dashboard/> 가 열립니다.
