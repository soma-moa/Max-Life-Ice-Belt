# Max-Life-Ice-Belt — 해양·극지·회전체 표면 희생층 관련 선행 문헌 정리

* 문서 성격: 선행 문헌 정리 문서 (신규 발명·청구 문서가 아님)
* 개정일: 2026-10-04 (현재 개정판은 버전 번호를 쓰지 않고 개정일만 표기한다)
* 작성자: 자료 정리자 deundeuni (soma-moa)
* 저장소: github.com/soma-moa/Max-Life-Ice-Belt | 도메인: somamoa.ai.kr
* 라이선스: Creative Commons Attribution 4.0 International (CC BY 4.0) 단일
* 언어: 한국어 원문이 기준본이며 영문본은 참고용이다. 해석이 충돌하면 한국어 원문을 따른다.

---

## 0. 정정·철회 고지 및 문서 성격

### 0.1 이전 공개본에 대한 정정
이전 공개본(v1.97까지, 2026-10-01 이전)에는 이 문서의 성격과 맞지 않는 서술이 있었다. 이번 개정에서 다음을 철회한다.

* "창안자", "구상자", "원천 지적재산권 보유자", "최초 구상" 등 독창성·발명자성·IP 보유를 암시하는 서술
* 선사용권, 영업비밀 분리, "4층 방어 체계" 등 권리 확보를 전제로 한 서술
* 근거를 확인하지 못한 수치와 수식 (100ms 국소 격리, 재착생 속도식, 희생층 파쇄 효율 계수 등). 이들은 문헌 근거 없이 문서 정리 과정에서 들어간 것이며 이번 판에서는 싣지 않는다.
* Apache-2.0 및 이전 비표준 라이선스 표기. 라이선스는 CC BY 4.0 단일로 정리한다.

이전 공개본은 저장소 이력에 역사적 기록으로 남기되, 현재 판의 내용으로 보지 않는다.

### 0.2 이 문서가 하는 일과 하지 않는 일
이 문서는 "갑판 스플래시·선수·선미처럼 상시 해수·유빙에 닿는 구간과 회전체 앞날이 닳는 문제를 다룬 기존 공개 문헌과 특허, 상용 제품, 규정"을 주제별로 모아 정리한 것이다. 작성자는 새로운 기술을 설계하거나 소유를 주장하지 않는다. 각 기술의 공로는 원 문헌의 저자, 발명자, 기관, 제조사에 100% 귀속된다.

작성자의 직접 경험은 금속 판재 가공과 설비 시공 분야에 한정된다. 해양·극지·항공 관련 서술은 모두 공개 문헌에 기댄 정리이며 해당 분야 전문가의 검증을 받지 않았다.

### 0.3 출발 질문
갑판 외측 해수 접촉 구간과 쇄빙선 선수·선미는 계속 깨지고 닳는데, 도장과 강판 교체만으로 대응하는 것이 최선인가. 이 질문 주변에 이미 어떤 연구와 기술이 있는지 정리하는 것이 이 문서의 출발점이다.

### 0.4 법적 지위
이 문서는 법정 선급 검사, MARPOL, IMO 협약·지침, 각국 규정을 대체·변경·면제하지 않는다. 문서 내 기술 서술은 공개 문헌의 요약이며 성능이나 적합성을 보장하지 않는다.

---

## 1. 주제별 선행 문헌 정리

> 확인 수준 표기: **[본문]** 해당 문헌의 본문·초록·특허 서지를 열람, **[요약]** 검색 결과의 요약·초록 수준만 확인, **[인용]** 다른 문헌의 인용 목록에서 확인. 모든 항목은 원문 재확인을 권한다.

### 1.1 부착 생물을 보호층으로 보는 연구 (Bioprotection)
조간대 암반과 콘크리트 구조물에서 따개비·홍합·굴 등이 풍화와 침식을 줄이거나 늦춘다는 연구가 이미 축적되어 있다.

* 고착성 석회질 생물(따개비, 석회질 관형 환형동물, 홍합, 굴)이 기질 표면에 단단하고 거친 층을 만들어 보호 역할을 한다는 총설이 있다 (콘크리트 자산의 생물 열화·생물 보호 총설, ScienceDirect Topics 요약 [요약]).
* 따개비가 암석 아표면(sub-surface)의 풍화를 줄이는 보호 역할을 하며 그 효과가 수 cm에서 수십 km 규모까지 일반화된다는 현장 실험이 있다 (Bioerosive and bioprotective role of barnacles on rocky shores, 이탈리아 북서부, *Science of the Total Environment* [요약]). 같은 연구군에서 초기 현장 실험은 따개비 피복이 간접적·중립적 또는 약한 생물침식 역할을 보였다는 결과(Pappalardo 외, 2016)도 있어 결과가 일관되지는 않다.
* 홍합 제거 실험에서 표면 경도가 5개월간 약 10% 감소했다는 보고 (Gonzalez 외, 2021, 아르헨티나 해안 *Brachidontes rodriguezii* [요약]). 청색 홍합(*Mytilus edulis*)의 유사한 보호 효과 연구도 있다 (Baxter 외, 2022 [요약]).
* 따개비가 열적 완충(Coombes 외, 2017)과 미세균열 봉합(Chlayon 외, 2018)에 기여한다는 서술이 위 문헌들에서 인용된다 [인용].
* 따개비와 박테리아 막이 콘크리트 염화물 침투 저항을 함께 높인다는 연구 (Combined protective action of barnacles and biofilm on concrete surface in intertidal areas, *Construction and Building Materials* [요약]).
* 굴의 부착 분비물은 대부분 무기질이고 산 용해에 강해 사후에도 보호 생물층으로 남을 수 있다는 서술 (Burkett 외, 2010; Tibabuzo Perdomo 외, 2018 인용 [인용]).
* 생물 부착이 구조물에 "열화"를 주는지 "보호"를 주는지는 오래 논쟁되어 온 주제이며, 이 논쟁이 구조물의 부착생물 관리 방침에 영향을 준다고 위 문헌들이 밝히고 있다 [요약].
* 굴 방파제 초(礁)가 침식을 줄였다는 현장 실험 (방글라데시 쿠투브디아 섬, 초 후면 침식 약 50% 안팎 감소 보고, *Scientific Reports* 2019 [요약]). 벨기에 Coastbusters 등 자연기반 해안 보호 프로젝트도 있다 (*Environmental Monitoring and Assessment* 2024, DOI 10.1007/s10661-024-12480-x [요약]).

정리: 부착 생물이 수동적으로 표면을 보호할 수 있다는 점은 해안생태공학에서 잘 알려진 주제다. 다만 대부분 조간대 암반·콘크리트·방파제 대상 연구이며, 쇄빙선 같은 이동 선체와 유빙 충돌 환경 대상 근거는 이번 조사에서 확인하지 못했다.

### 1.2 부착 생물을 유도하는 상용 제품·특허
* **ECOncrete**: 2012년 해양생물학자 두 명(Perkol-Finkel, Sella)이 설립. 생물 친화 콘크리트 혼화제, 거친 표면 질감, 3D 형상을 조합해 착생을 촉진하고 그 "생물 보호"로 내구성을 높인다고 제조사가 설명한다. 하이파 항 방파제 Antifer 블록 24개월 모니터링 논문 (*Ecological Engineering*, "Blue is the new green" [요약]), Coastalock 피복 블록, 생물 활성 벽 타일 등이 있다 [제조사 자료].
* **Living Ports (EU Horizon 2020, 2021.06~2024.05)**: 비고 항(Port of Vigo)에서 ECOncrete 해안 피복·안벽을 실증하고 DTU가 모니터링 (CORDIS 970972 [요약]).
* **Living Seawall (샌프란시스코만)**: 스미소니언 환경연구센터(SERC)와 샌프란시스코 항만청이 일반·생물 강화·질감 타일을 비교하는 실험 [요약].
* **특허 RE42259 "Biologically-dominated artificial reef"**: 굴·홍합·따개비 등 고착 생물의 성장을 이용해 침식을 줄이는 인공 초 구조 [요약].

정리: 해안 구조물에서 부착 생물 유도와 보호를 결합한 제품은 이미 상용화·실증 단계에 있다. 이쪽은 정박·고정 구조물 대상이다.

### 1.3 희생·어블레이티브 층
**선박 방오도료 (자기연마형, Self-Polishing Copolymer)**
* 해수에서 폴리머가 가수분해되며 표면이 서서히 마모·갱신되는 방식의 방오도료가 오래 쓰였다. 초기 주석(TBT) 계열은 IMO AFS 협약(2001 채택, 2003 신규 도장 금지, 2008 선체 사용 금지)으로 금지되었고, 이후 실릴 에스테르 아크릴 계열 무주석 SPC가 주류다 (특허 US8575231 서술, Kiil 외 모델 논문, *Tin-free self-polishing marine antifouling coatings* [요약]).
* 폴리싱 속도는 유속·온도·화학 조성에 따라 달라지며 월 수 µm 수준의 실측·모델 보고가 있다 [요약].
* 이들은 살생물질 방출이 전제인 경우가 많아 이 문서가 다루는 구조적 희생층과 목적이 다르다. 쇄빙선용으로는 제조사가 방오·오염 방출 도료가 얼음 접촉 선체에 적합하지 않다고 설명하는 자료도 있다 (Ecospeed 제조사 자료 [제조사 자료]).

**회전익·프로펠러 앞날 침식 보호 (교체형 희생 부품)**
* US5542820 "Engineered ceramic components for the leading edge of a helicopter rotor blade" (1996): 니켈 앞날 캡이 정비창에서 교체되고, 모래 침식을 줄이려 탄성 희생 테이프를 쓰는 것이 선행 관행으로 서술되며, 교체형 팁 세그먼트에 세라믹 부품을 접합 [본문].
* US8858184B2 "Rotor blade erosion protection system" (2011 출원): 마모되면 제거·교체하는 금속 희생 침식 스트립이 일반적이라고 서술하고 서멧 코팅 방식의 보수 가능한 보호 시스템을 제시 [본문].
* US9429025B2 / US20130101432A1 / EP2585370A2 "Erosion resistant helicopter blade": 앞날 실드에 충격 저항층과 침식 저항층을 겹치는 구조 [본문].
* US20100008788A1 "Protector for a leading edge of an airfoil": 바깥 침식 저항 부재와 그 아래 에너지 흡수 부재를 겹친 앞날 보호구 [본문].
* US5782607 "Replaceable ceramic blade insert": 프로펠러 블레이드 앞날 보호 시스에 침식이 가장 큰 바깥쪽에 교체형 세라믹 인서트를 넣는 구조 [본문].
* US20050169763A1 "Helicopter rotor and method of repairing same": 폴리우레탄 앞날 스트립으로 보수 [본문].
* 인용 목록에서 확인한 관련 문헌: US7246998B2 "Mission replaceable rotor blade tip section", US5885059A "Composite tip cap assembly for a helicopter main rotor blade", EP3275783B1 "Rotor blade erosion protection systems" [인용].

정리: "닳도록 설계한 교체형 앞날 보호재"는 회전익·프로펠러 분야에 특허가 많은 성숙한 영역이다.

### 1.4 쇄빙선 아이스벨트: 선형·재료·코팅
**선형·기하 (곡면과 경사로 얼음을 굽힘 파괴시키는 접근)**
* US4715305 "Ship's hull" (Wärtsilä, 1984 우선, 1987 등록): 쇄빙 선체 형상 [본문: 서지 및 인용 관계].
* US5176092 "Icebreaker bow and hull form" (Newport News Shipbuilding, 1993): V자형 선수와 S자형 선수재, 하부 쐐기 [본문].
* US4436046 "Ice-breaking hull": 선수 양측의 경사 융기로 얼음 조각을 선체 아래에서 벗어나게 하는 편향 구조 [요약].
* US5325803 "Icebreaking ship" (독일 DE4101034 우선권): 발코니형 측면 플랭크와 난간을 가진 선체 [본문]. ※ 이전 개정판은 이 특허를 "곡면·경사로 굽힘·전단 파괴를 유도하는 선형"으로 묶어 인용했으나, 이번에 확인한 서술은 측면 플랭크 구조 중심이다. 인용 취지를 원문으로 다시 확인해야 한다.
* CA1311393C "Icebreaker": 선체 열원으로 외판을 데워 얼음 마찰·점착을 줄이는 구조 [본문].
* US5660131 "Icebreaker attachment" (Marinette Marine, 1997): 모선에 선택적으로 결합·분리하는 쇄빙 부가 구조. 선체 규모의 착탈 모듈이라는 점에서 이 문서의 주제와 가까운 선행 사례다 [본문].
* ※ 이전 개정판이 인용한 US4351255는 이번 조사에서 확인하지 못했다. 확인 전까지 인용하지 않는다.

**아이스벨트 재료·코팅 (상용 기술)**
* 선급(Lloyd's Register, DNV, 러시아 선급 등)은 얼음 마모에 대비해 아이스벨트 강판 두께를 증가시키도록 규정하고, 일부는 인증된 내마모 코팅의 효과를 인정한다 (Intershield 163 / Inerta 160, AkzoNobel 제품 자료 [제조사 자료]).
* PPG SIGMASHIELD 1200은 쇄빙선 네 척에 적용되어 잠수 검사에서 수직 측면 손상이 없었다고 보고되었다 (BIC Magazine [제조사 사례]).
* Ecospeed (Subsea Industries)는 아이스벨트 판 두께를 최대 1 mm 줄일 수 있다고 주장한다 [제조사 자료].
* 러시아 원자력 쇄빙선 Leader(프로젝트 10510)는 약 50 mm 강판에 5 mm 스테인리스를 입힌 클래드강 아이스벨트를 적용하는 것으로 보도되었고, Arktika급(22220)은 클래드 대신 Inerta 계열 에폭시 코팅을 사용한다 (Nuclear Engineering International [요약]). 폭발 용접 스테인리스 아이스벨트(Botnica 사례)는 2차 자료에서 확인했다 [2차 자료].
* US10774396 "Seawater-resistant stainless clad steel": 스테인리스 클래드강의 마모·공식 저항을 다루며, 따개비가 붙은 틈에서의 부식 저항 문제를 언급한다 [본문].
* US4968538, US4789567 "Abrasion resistant coating and method of application": 세라믹 입자를 내식 수지에 분산한 내마모 코팅 [요약].

**빙하중·빙저항 모델**
* Lindqvist (1989), "A straightforward method for calculation of ice resistance of ships", *Proc. 10th POAC*, Luleå, vol. 2, pp. 722–735: 빙저항을 압괴(crushing), 굽힘(bending), 침하(submersion) 성분으로 나누는 모델. 이후 Riska 등(1997)이 수정 [요약].
* 압력-면적 관계: Sanderson (1988)의 자료 편집, Masterson & Frederking (1993)의 국부 빙압 편집. 접촉 면적이 커질수록 국부 빙압이 줄어드는 면적 효과를 정리했고, 설계 코드(API RP 2N, CSA S471)에는 p = 8.1·a^-0.5 (p: MPa, a: m²) 형태의 관계식이 쓰인다고 후속 논문이 인용한다 (*Cold Regions Science and Technology* [요약]). Palmer & Sanderson (1991)은 프랙탈과 선형 탄성 파괴역학으로 이 효과를 설명했다 [인용]. 면적 효과의 정의와 적용에는 논쟁이 있다 [요약].

정리: 곡면·경사 선형, 내마모 코팅, 클래드강, 빙저항 모델은 모두 이미 공개된 선행 영역이다. 아이스벨트 위에 "교체형·마모형 희생 모듈"을 얹는 접근에 직접 해당하는 문헌은 이번 조사에서 확인하지 못했다 (없다는 뜻은 아니다. 5장 참조).

### 1.5 용접 없이 클램프로 부착하는 해양 구조물
* CN104314061A "Detachable ice-resistant device applicable to offshore nuclear power platform": 반원통 구조로 파일 다리를 클램프하고 자체 잠금으로 결합·분리하며, 반복 설치·철거와 굽힘 파괴 유도 콘으로 빙하중을 줄이는 구조 [본문]. 이 문서가 다루는 "무용접 클램프 부착 + 얼음 굽힘 파괴 유도"에 가장 가까운 선행 사례다.
* EP2275677A2 "Device for reducing ice loads on a pile foundation for an offshore wind turbine": 파도·바람 하중을 늘리지 않도록 투과형 버팀 구조로 만든 아이스콘 [본문].
* US20110006538A1 / EP2185816A1 / WO2009026933A1 "Monopile foundation for offshore wind turbine": 2차 구조물을 파일 둘레에 클램프로 조여 고정하고, 볼트 대신 클램프를 쓰면 충격에도 덜 파손된다고 서술 [본문].
* US5079805 "Fastener for protective sleeves": 부두 파일을 부식·부패·해양 생물 부착으로부터 보호하는 슬리브를 감싸고 고정하는 체결구 [본문].
* WO2016095052A9 "Composite sleeve for piles": 동결 부착(adfreeze) 상승 하중을 줄이는 복합 슬리브, 상단 잠금에 볼트·용접 칼라·클램프 사용 [본문].

정리: 파일·각주 둘레 클램프형 보호 슬리브, 착탈식 아이스콘은 선행 사례가 다수 있다. 선체 외판 위 클램프형 모듈의 직접 사례는 US5660131(선체 규모 부가 구조) 외에는 이번에 확인하지 못했다.

### 1.6 구조적 희생 사상의 일반 배경
* Béla Barényi (1951), 자동차 수동안전(크럼플존) 개념. 충격 에너지를 구조 변형으로 소산시키는 사상의 고전적 배경으로 인용한다.

---

## 2. 부착 생물을 쓸 때의 환경·생물안전 논점 (선행 문헌 요약)

부착 생물을 보호층으로 쓰는 접근은 선박에서는 외래종 이동 문제와 직접 충돌한다. 아래는 이전 판에서 정리한 문헌을 유지·요약한 것이며, 주장이 아니라 알려진 한계의 기록이다.

* **국제 지침**: IMO는 2011년 결의 MEPC.207(62)로 선박 부착생물의 통제·관리 지침을 채택했고, 선체 부착생물을 외래 수생생물 이동의 중요한 경로로 서술한다.
* **기항국 규정**: 뉴질랜드 1차산업부(MPI)의 Craft Risk Management Standard가 2018년부터 입항 선박 선체에 부착생물이 없을 것(대부분 점액층 정도만 허용)을 요구하는 것으로 알려져 있고, 미국 캘리포니아주는 선체 부착생물 관리 규정(California Code of Regulations, title 2, section 2298.1 et seq.)을 둔다. 세부 요건은 개정될 수 있어 실제 적용 전 확인이 필요하다.
* **미생물 이동**: 선체 부착생물층에는 생물막이 함께 형성되며, 이매패는 여과 섭식으로 세균·바이러스를 축적할 수 있다는 문헌이 있다. 상선 외부 선체 부착생물에서 병원성 *Vibrio parahaemolyticus*가 검출되었다는 보고가 있다 (Revilla-Castellanos 외, 2015). 바이러스는 외부 선체 착생층을 직접 조사한 연구를 찾지 못했고 문헌 대부분이 밸러스트 탱크 내부나 오염된 연안·양식 조개류 대상이다. 존재와 병원성은 별개다.
* **군집 단위 탈락**: 충격으로 부착 생물 군집 조각이 한꺼번에 떨어져 다른 해역에서 생존·착생할 수 있는지는 확인된 문헌이 없다.
* **수중 세척**: 수중 세척이 생존 개체와 미생물 방출을 늘릴 수 있다는 정책 브리프와 NIWA 연구(Woods 외, 2012)가 있다.
* **방식별 영향**: 살생물 방오도료는 비표적 생물에 화학적 영향을, 생물 착생 방식은 외래종·미생물 이동 가능성을, 비생물 어블레이티브 방식도 탈락 물질의 해양 환경 영향 평가를 각각 요구한다. 어느 쪽이 더 낫다고 단정하지 않는다.
* **규제 준수**: 항로 전체(경유·기항 해역, 극지 특별 해역 포함)에 적용되는 협약·지침·국가 규정·선급 규칙을 확인해야 하며, 더 엄격한 요건을 우선 검토하는 것이 합리적이다 (AFS 협약 제1조(3)은 국제법에 부합하는 범위에서 국가가 더 엄격한 조치를 취하는 것을 막지 않는다).

---

## 3. 확인 상태와 이전 판과의 차이

| 항목 | 이번 조사 결과 |
|---|---|
| US4715305 | 서지·인용 관계 확인. Wärtsilä "Ship's hull" |
| US5325803 | "Icebreaking ship"(발코니형 측면 플랭크). 이전 판의 "굽힘·전단 유도 선형" 설명과 취지가 다를 수 있어 재확인 필요 |
| US4351255 | 확인하지 못함. 인용 보류 |
| Lindqvist (1989) | 서지 확인 (POAC 1989, pp. 722–735). 수식 원문은 미열람 |
| 압력-면적 관계식 | 후속 논문 인용 수준에서 형태 확인. 원문 미열람 |
| 빙하중 압력-면적을 반영한 얼음 파괴 흡수 에너지 수식 | 이번 판에서 자체 수식을 삭제. 필요하면 위 문헌에서 직접 인용해야 함 |

---

## 4. 해석상의 메모 (정리자의 관찰, 주장 아님)

* 요소 하나하나(생물 보호, 희생·교체형 보호재, 곡면 선형, 내마모 코팅, 클램프 부착)는 모두 별도의 선행 영역이 있다.
* 이들을 "아이스벨트 위의 마모형·교체형 모듈 + 선택적 생물 착생층"으로 묶은 직접 일치 문헌은 이번 조사 범위에서 찾지 못했다. 이것은 "새롭다"는 뜻이 아니라 "이번에 못 찾았다"는 뜻이다.
* 항공 회전체의 대칭 박리나 무공구 퀵릴리즈 카트리지와 직접 일치하는 문헌도 이번에 찾지 못했다. 다만 회전익 앞날 교체형 보호재(1.3절)는 이미 풍부하다.
* 생물 착생 방식은 정박·고정 구조물에서는 선행 연구가 풍부하지만, 다해역 항해 선박에서는 2장의 규제와 충돌 소지가 있다. 이 점은 문헌이 보여주는 사실이다.

---

## 5. 조사 한계 및 미조사 항목

* 이번 조사는 영문 위주의 검색 한 라운드이며, 중소업체·개인 출원과 한·중·러·일 문헌을 포함한 확장 검색 라운드는 수행하지 않았다. 앞으로는 동의어·업계 용어 변주로 추가 검증한다.
* 이번에 검색하지 않은 항목: 광물 집적(Biorock 계열), 목선 시절 희생 외판(sheathing), 합성 탄산칼슘 모사체, 경도 구배 희생층·사전 분할 셀 구조, 곡면 스캐폴드 위 착생 포켓, 회전체 불균형 완화 관련 문헌, 해상 구조물 센서 모니터링.
* 많은 항목이 요약·초록·제조사 자료 수준 확인이며 원문을 모두 읽지 않았다.
* 구조 충돌 해석, 수조 시험, 클램프 피로·동결 시험 등은 수행하지 않았고 수행 계획도 없다.
* 제조사 자료의 성능 수치는 해당 제조사 주장이다.

---

## 6. 참고 문헌 및 자료

### 6.1 규격·협약·지침
ISO 8501; IMO AFS 협약 (2001 채택, 2008 발효, 제1조(3)); EU 해양전략 프레임워크 지침(MSFD); 각국 선급(KR, DNV, ABS, Lloyd's Register) Ice Class 규칙; IMO Resolution MEPC.207(62) (2011); 뉴질랜드 MPI Craft Risk Management Standard; California Code of Regulations, title 2, section 2298.1 et seq.; API RP 2N; CSA S471.

### 6.2 특허 (이번에 서지 확인)
US4715305; US5325803; US5176092; US4436046; CA1311393C; US5660131; US5542820; US8858184B2; US9429025B2; US20130101432A1; EP2585370A2; US20100008788A1; US5782607; US20050169763A1; US7246998B2 [인용]; US5885059A [인용]; EP3275783B1 [인용]; US10774396; US4968538; US4789567; US8575231; US5472993; US4914141; CN104314061A; EP2275677A2; US20110006538A1; EP2185816A1; WO2009026933A1; US5079805; WO2016095052A9; RE42259.

### 6.3 논문·총설
* Lindqvist G (1989) A straightforward method for calculation of ice resistance of ships. *Proc. 10th POAC*, Luleå, 722–735.
* Sanderson TJO (1988) *Ice Mechanics: Risks to Offshore Structures*; Masterson DM, Frederking RMW (1993) Local contact pressures in ship/ice and structure/ice interactions. *Cold Regions Science and Technology*; Palmer AC, Sanderson TJO (1991).
* Bioerosive and bioprotective role of barnacles on rocky shores. *Science of the Total Environment*.
* Combined protective action of barnacles and biofilm on concrete surface in intertidal areas. *Construction and Building Materials*.
* The bioprotective properties of the blue mussel (*Mytilus edulis*) on intertidal rocky shore platforms.
* Oyster breakwater reefs promote adjacent mudflat stability and salt marsh growth in a monsoon dominated subtropical coast. *Scientific Reports* (2019).
* Nature-based solutions for coastal protection in sheltered and exposed coastal waters. *Environmental Monitoring and Assessment* (2024), DOI 10.1007/s10661-024-12480-x.
* Perkol-Finkel S, Sella I, "Blue is the new green: Ecological enhancement of concrete based coastal and marine infrastructure". *Ecological Engineering*.
* Kiil S 외, 자기연마 방오도료 동적 시뮬레이션 (*JCT Coatings Tech*); Tin-free self-polishing marine antifouling coatings (총설).

### 6.4 부착생물·생물안전 관련 (이전 판 유지, 초록 기준, 원문 확인 필요)
Drake LA 외 (2005) *Biological Invasions* 7:969-982; Drake LA, Doblin MA, Dobbs FC (2007) *Marine Pollution Bulletin* 55:333-341, DOI 10.1016/j.marpolbul.2006.11.007; Martinez-Albores A 외 (2020) *Foods* 9(2):129; McLeod C 외 (2017) *Comprehensive Reviews in Food Science and Food Safety* 16(4):692-706; Revilla-Castellanos VJ 외 (2015) *Biofouling* 31(3):275-282, DOI 10.1080/08927014.2015.1038526; Georgiades E, Scianni C, Tamburri MN (2023) *Frontiers in Marine Science* 10:1197366; Scianni C 외 (2023) *Frontiers in Marine Science* 10:1239723; Tamburri MN 외 (2021) *Frontiers in Marine Science* 8:804766, DOI 10.3389/fmars.2021.804766; Woods CMC, Floerl O, Jones L (2012) *Marine Pollution Bulletin* 64:1392-1401, DOI 10.1016/j.marpolbul.2012.04.019; Floerl O 외 (2005) MPI Technical Paper No. 08/12.
방오도료 환경 영향: Thomas KV, Brooks S (2010) *Biofouling* 26(1):73-88, DOI 10.1080/08927010903216564; Konstantinou IK, Albanis TA (2004) *Environment International* 30:235-248, DOI 10.1016/S0160-4120(03)00176-4; Alzieu C (2000) *Science of the Total Environment* 258:99-102; Soroldoni S 외 (2018) 방오도료 입자 (서지 확인 필요); *Marine Pollution Bulletin* 169:112529 (2021, 저자 확인 필요).

### 6.5 상용 제품·제조사 자료 (제조사 주장)
AkzoNobel International Intershield 163 Inerta 160; PPG SIGMASHIELD 1200; Subsea Industries Ecospeed; ECOncrete 사례 자료; CORDIS Living Ports (프로젝트 970972); Port of San Francisco / SERC Living Seawall.

### 6.6 공지기술 원용
Béla Barényi (1951), 자동차 수동안전 개념(크럼플존).

---

## 7. 귀속·라이선스·작성 방식

* 이 문서의 모든 기술적 내용의 공로는 위 문헌의 저자·발명자·기관·제조사에 있다. 작성자는 자료를 모아 정리했을 뿐이다.
* 텍스트는 CC BY 4.0으로 공개한다. 인용·재사용 시 이 저장소와 원 문헌을 함께 밝히기를 권한다.
* 작성 과정에서 범용 생성형 AI 도구를 텍스트 정리와 서지 검색에 사용했으며, 검수 의견을 반영해 작성자가 정리했다. 오류와 누락의 책임은 작성자에게 있다.
* 이 문서의 서지·특허번호·수치에 오류가 있으면 알려주길 바란다. 확인되는 대로 정정한다.

### CITATION.cff
```yaml
cff-version: 1.2.0
message: "If you use or reference this literature review, please cite it as below."
authors:
  - alias: "deundeuni"
    name: "soma-moa"
title: "Max-Life-Ice-Belt: A Literature Review on Sacrificial Surface Layers for Marine, Polar and Rotating-Machinery Applications"
date-released: 2026-10-04
license: CC-BY-4.0
url: "https://github.com/soma-moa/Max-Life-Ice-Belt"
keywords:
  - "Literature Review"
  - "Prior Art"
  - "Ice Belt"
  - "Bioprotection"
  - "Sacrificial Layer"
  - "Rotor Leading Edge Erosion"
  - "Clamp-on Marine Structures"
```
