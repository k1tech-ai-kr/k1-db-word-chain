# 출처와 이용 조건

수집일: 2026-10-24 KST. 원본은 `raw/`, 내려받은 URL·SHA-256은 `raw/manifest.json`, `raw/extra_manifest.json`과 DB `provenance`에 보존합니다. 이 패키지 전체를 단일 MIT 라이선스로 취급하지 마세요.

## 국립국어원

- 표준국어대사전: 공식 전체 JSON 20261012, 436,587 원본 레코드. https://stdict.korean.go.kr/common/download.do?link_key=1610293
- 한국어기초사전: 공식 전체 JSON 20261019. https://krdict.korean.go.kr/dicBatchDownload?seq=220
- 저작자: 국립국어원. 텍스트 기본 조건: CC BY-SA 2.0 KR. 변환: 표제어 정규화, 명사 필터, 중복 통합, 관계형 테이블 및 분할 JSON 변환.
- 정책: https://stdict.korean.go.kr/join/copyrightPolicy.do 및 https://krdict.korean.go.kr/kor/kboardPolicy/copyRightTermsInfo
- 국립국어원 출처와 변경 사실을 표시하고 해당 파생 자료의 동일조건변경허락을 유지해야 합니다. 소프트웨어 코드와 데이터의 조건은 구분합니다.
- 출전이 있는 문학 작품 용례는 별도 권리가 있을 수 있으므로 표준국어대사전의 `example_info`는 가공 테이블/앱 패키지에 복제하지 않았습니다. 원본 ZIP은 연구·보존용으로 분리합니다. 음성·이미지 등 멀티미디어 파일은 수집·패키징하지 않았습니다.

## Wiktionary → Wiktextract / Kaikki

- 저작자: Wiktionary 기여자. 가공 제공자: Tatu Ylonen 및 Wiktextract/Kaikki.
- 원천: https://kaikki.org/dictionary/Korean/ 및 각 언어 `pos-proverb/`.
- 텍스트 조건: CC BY-SA 4.0 / GFDL. https://en.wiktionary.org/wiki/Wiktionary:Copyrights
- 변환: 명시적인 four-character idiom 라벨만 사자성어 확장에 사용, 속담 표제어와 뜻풀이 추출, 언어별 분할, 중복 표제어 통합. 각 표제어에 원문 링크를 유지합니다.
- 한 언어가 특정 국가의 독점 기원을 뜻하지 않습니다. 뜻풀이는 원본의 영어 설명을 유지하며, 미확인 한국어 번역을 생성하지 않았습니다.
- 원문에 별도 권리가 있는 인용·매체가 포함될 수 있으므로 음성·이미지·용례 인용은 앱 패키지에 포함하지 않았습니다.

## Openjam / WordNet 및 CEFR 참고 목록

- Openjam: https://github.com/amirj4m/openjam, MIT 표방. 원문 `LICENSE`, `ATTRIBUTION.md`를 raw에 보존합니다.
- 정의·품사·예문 원천은 upstream의 설명상 Princeton WordNet 3.1입니다. WordNet은 MIT와 구분되는 자체 라이선스이므로 공개 배포 시 WordNet 원문 고지를 함께 포함해야 합니다. https://wordnet.princeton.edu/license-and-commercial-use
- CEFR 참고: https://github.com/bonkey/words-cefr-dataset, upstream MIT 고지 보존. CEFR 수준 및 frequency rank는 upstream 제공값이며 이번 작업에서 언어교육 전문가 검증을 수행하지 않았습니다.
- 15단계는 기존 K1 단계 ID를 유지한 로컬 추정 배정입니다. 학년별 교육과정·TOEIC·TEPS·TOEFL의 공식 어휘/점수 인증 목록이 아닙니다. 시험 기출문제는 수집하지 않았습니다.
- 기존 K1 한국어 뜻은 그대로 보존했습니다. 역방향 한국어기초사전 연결은 검토 후보 관계이며 영어 단어의 모든 뜻에 대응하는 정답 번역이 아닙니다.

## PubChem

- 원천: 미국 NIH/NLM/NCBI PubChem PUG REST. https://pubchem.ncbi.nlm.nih.gov/docs/pug-rest-tutorial
- 수집 필드: CID, Title, MolecularFormula, MolecularWeight, SMILES, ConnectivitySMILES, InChI, InChIKey, IUPACName, 2D SDF.
- 구조 레코드와 표준화 속성만 사용했습니다. 제3자 서술형 주석·이미지·안전성 설명은 복제하지 않았습니다. PubChem 전체 내용을 일괄적으로 public domain이라 간주하지 않습니다. https://pubchem.ncbi.nlm.nih.gov/docs/copyright
- 구조 그림은 내려받은 SDF의 원자 좌표와 결합 차수를 이용해 로컬 생성한 연결성 미리보기입니다. 전하·입체화학·동위원소·암시적 수소는 SVG에서 생략되므로 정확한 구조는 SDF/SMILES/InChI를 사용하세요.

## K1 기존 자료 및 새 문항

- `raw/k1_existing.json`: E:/workspace/k1-common의 기존 학습 자료를 읽기 전용으로 추출한 스냅샷입니다. 소프트웨어 저장소는 UNLICENSED 표시이므로 외부 재배포 권한을 자동 추정하지 않습니다.
- 자체 맞춤법 문장·설명은 새로 작성한 검토용 초안입니다. 국립국어원이 감수한 문제로 표시하지 않습니다. 기준 참조: https://korean.go.kr/kornorms/main/main.do
- 사자성어 판정 후보와 맞춤법 초안, 연령 적합성 검토 전 단어, 국가가 미확정인 속담은 검토 상태를 유지합니다.
