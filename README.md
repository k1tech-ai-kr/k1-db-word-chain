# 끝말잇기 사전 명사 20만

K1 앱 허브(케이원테크) 학습 앱이 내려받는 **확장 자료(DB)** 저장소입니다. 버전 1.0.0 · 2026-10-23

표준국어대사전 명사 208,358개(한글 두 글자 이상, 첫 글자 자음별 19조각) — 끝말잇기 인정 사전.

- 쓰는 앱: word-chain
- 앱이 내려받는 파일: `data/가.json`, `data/까.json`, `data/나.json`, `data/다.json`, `data/따.json`, `data/라.json`, `data/마.json`, `data/바.json`, `data/빠.json`, `data/사.json`, `data/싸.json`, `data/아.json`, `data/자.json`, `data/짜.json`, `data/차.json`, `data/카.json`, `data/타.json`, `data/파.json`, `data/하.json`
- 모든 파일의 크기와 SHA-256은 [manifest.json](manifest.json)에 있습니다. 앱은 내려받은 뒤 해시를 확인합니다.

## 출처·이용 조건

- 국립국어원 표준국어대사전·한국어기초사전 — CC BY-SA 2.0 KR (출처: 국립국어원, 변경: 표제어 정규화·필터·형식 변환)

자료마다 조건이 다릅니다. 저장소 전체를 하나의 라이선스로 보지 마세요. 동일조건변경허락(CC BY-SA) 자료를 고쳐 다시 배포할 때는 같은 조건과 출처 표시를 지켜야 합니다. 자세한 고지는 [ATTRIBUTION.md](ATTRIBUTION.md).

## 형식

JSON(UTF-8). 각 파일의 `format` 칸에 행 구조를 적었습니다.

## 만든 방법

`k1-ad-apps`(비공개) 저장소의 `scripts/db-packs.mjs`로 생성. 원자료: 국립국어원 공식 내려받기, Wiktextract/Kaikki, Openjam·WordNet, PubChem PUG REST, Wikidata SPARQL(2026-10-24 수집).
