# Max-Life-Ice-Belt — A Literature Review on Sacrificial Surface Layers for Marine, Polar and Rotating-Machinery Applications

* Document type: Prior-art literature review (not an invention or claim document)
* Revision date: 2026-10-04 (the current revision carries no version number, only a revision date)
* Compiled by: deundeuni (soma-moa), as a collector and organizer of existing materials
* Repository: github.com/soma-moa/Max-Life-Ice-Belt | Domain: somamoa.ai.kr
* License: Creative Commons Attribution 4.0 International (CC BY 4.0) only
* Language note: The Korean text is the authoritative original. This English version is a reference translation. If the two conflict, the Korean text prevails.

---

## 0. Correction, Retraction and Nature of This Document

### 0.1 Corrections to earlier publications
Earlier publications of this document (up to v1.97, 2026-10-01 and before) contained statements that did not fit its actual nature. This revision retracts the following.

* Statements implying originality, inventorship or IP ownership: "inventor," "conceiver," "original IP holder," "first conceived."
* Statements presupposing the securing of rights: prior-use rights, trade-secret separation, the "quadruple defense architecture."
* Figures and equations for which no source was verified (100 ms local isolation, a re-colonization growth equation, a crushing-efficiency coefficient for the sacrificial layer, and similar). These entered the text during document drafting without literature support and are not included in this revision.
* The Apache-2.0 notice and the earlier non-standard license notice. The license is now CC BY 4.0 only.

The earlier publications remain in the repository history as historical records and should not be read as the content of the current revision.

### 0.2 What this document does and does not do
This document collects and organizes, by topic, existing public literature, patents, commercial products and regulations that address wear on surfaces in constant contact with seawater and ice (deck splash zones, icebreaker bows and sterns) and on rotating-machinery leading edges. The compiler does not design new technology and does not claim ownership of anything. Credit for each technology belongs 100% to the authors, inventors, institutions and manufacturers of the original sources.

The compiler's direct experience is limited to sheet-metal fabrication and plant/equipment construction work. All statements about marine, polar and aviation topics are organizations of public literature and have not been verified by domain experts.

### 0.3 Starting question
The outer seawater-contact zones of decks and the bows and sterns of icebreakers keep cracking and wearing. Is repainting and replacing steel plate the best that can be done? This document starts from that question and surveys what research and technology already exist around it.

### 0.4 Legal status
This document does not replace, modify or exempt anything from statutory classification surveys, MARPOL, IMO conventions and guidelines, or national regulations. Technical statements herein are summaries of public literature and guarantee neither performance nor suitability.

---

## 1. Prior Literature by Topic

> Verification level markers: **[Full text]** the document, abstract or patent bibliographic record was read; **[Summary]** only a search-result summary or abstract was checked; **[Cited]** confirmed only from another document's citation list. Re-checking against original sources is recommended for every item.

### 1.1 Studies treating attached organisms as protective layers (bioprotection)
A body of research already exists showing that barnacles, mussels and oysters on intertidal rock and concrete structures can reduce or slow weathering and erosion.

* A review reports that sessile calcareous organisms (barnacles, calcareous tube-building worms, mussels, oysters) form a hard, rough layer on the substrate surface and play a protective role (review on biodeterioration and bioprotection of concrete assets in the coastal environment, ScienceDirect Topics summary [Summary]).
* A field experiment reports that barnacles protect rock at the sub-surface level and that the effect holds from a few centimeters to tens of kilometers (Bioerosive and bioprotective role of barnacles on rocky shores, NW Italy, *Science of the Total Environment* [Summary]). The same research line also contains earlier field results in which barnacle cover showed a moderate, mostly indirect bioerosive or neutral role (Pappalardo et al., 2016), so results are not uniform.
* Removal of mussels reduced surface hardness by about 10% over five months (Gonzalez et al., 2021, Argentine coast, *Brachidontes rodriguezii* [Summary]). Similar protective effects of blue mussels (*Mytilus edulis*) have been studied (Baxter et al., 2022 [Summary]).
* Barnacle contributions to thermal buffering (Coombes et al., 2017) and to sealing microcracks (Chlayon et al., 2018) are cited in the above literature [Cited].
* Barnacles and bacterial films together improve chloride-penetration resistance of concrete (Combined protective action of barnacles and biofilm on concrete surface in intertidal areas, *Construction and Building Materials* [Summary]).
* Oyster attachment secretions are largely inorganic and resistant to acid dissolution, so they may persist as a protective biogenic layer after the organism dies (Burkett et al., 2010; Tibabuzo Perdomo et al., 2018, as cited [Cited]).
* Whether fouling causes "deterioration" or "protection" has long been debated, and this debate affects how fouling on structures is managed, as the sources above state [Summary].
* Oyster breakwater reefs reduced erosion in a field experiment (Kutubdia Island, Bangladesh; erosion reduced by roughly 50% in the lee of the reefs, *Scientific Reports* 2019 [Summary]). Nature-based coastal protection projects such as Belgium's Coastbusters also exist (*Environmental Monitoring and Assessment* 2024, DOI 10.1007/s10661-024-12480-x [Summary]).

Takeaway: Passive surface protection by attached organisms is a well-known topic in coastal ecological engineering. However, most studies concern intertidal rock, concrete and breakwaters. Evidence for moving hulls such as icebreakers under ice-impact conditions was not found in this survey.

### 1.2 Commercial products and patents that induce colonization
* **ECOncrete**: Founded in 2012 by two marine biologists (Perkol-Finkel and Sella). The manufacturer describes combining a bio-enhancing concrete admixture, rough surface texture and 3D shapes to promote colonization, with "bioprotection" improving durability. Examples include a 24-month monitoring paper on Antifer breakwater units in Haifa (*Ecological Engineering*, "Blue is the new green" [Summary]), Coastalock armor units and bio-active wall tiles [Manufacturer material].
* **Living Ports (EU Horizon 2020, June 2021 – May 2024)**: ECOncrete coastal armoring and quay wall demonstrated at the Port of Vigo, with DTU monitoring (CORDIS project 970972 [Summary]).
* **Living Seawall (San Francisco Bay)**: An experiment by the Smithsonian Environmental Research Center (SERC) and the Port of San Francisco comparing standard, bio-enhanced and textured tiles [Summary].
* **Patent RE42259 "Biologically-dominated artificial reef"**: An artificial reef structure that uses the growth of sessile organisms such as oysters, mussels and barnacles to reduce erosion [Summary].

Takeaway: Products combining colonization induction and bioprotection on coastal structures are already at commercial or demonstration stage. These target stationary or fixed structures.

### 1.3 Sacrificial and ablative layers
**Ship antifouling paints (self-polishing copolymer, SPC)**
* Antifouling paints whose polymer hydrolyzes in seawater so that the surface gradually wears away and renews have long been used. Early tin-based (TBT) types were banned under the IMO AFS Convention (adopted 2001; new application prohibited from 2003; prohibited on hulls from 2008), and tin-free silyl-ester acrylic SPCs are now the mainstream (patent US8575231 description, Kiil et al. modeling papers, *Tin-free self-polishing marine antifouling coatings* [Summary]).
* Polishing rate depends on flow speed, temperature and chemistry, with measurements and models reporting a few µm per month [Summary].
* Many of these presuppose biocide release, so their purpose differs from the structural sacrificial layers covered here. For ice-going ships, at least one manufacturer states that antifouling and foul-release coatings are unsuitable for ice-contact hulls (Ecospeed manufacturer material [Manufacturer material]).

**Replaceable sacrificial leading-edge protection for rotors and propellers**
* US5542820 "Engineered ceramic components for the leading edge of a helicopter rotor blade" (1996): describes nickel leading-edge caps replaced at depot facilities and elastomeric sacrificial tape as prior practice for sand erosion, and bonds ceramic components to a replaceable tip segment [Full text].
* US8858184B2 "Rotor blade erosion protection system" (filed 2011): describes metal sacrificial erosion strips that are removed and replaced as they wear, and presents a repairable protection system using a cermet coating [Full text].
* US9429025B2 / US20130101432A1 / EP2585370A2 "Erosion resistant helicopter blade": layers an impact-resistant layer and an erosion-resistant layer on the leading-edge shield [Full text].
* US20100008788A1 "Protector for a leading edge of an airfoil": a leading-edge protector with an outer erosion-resistant member and an energy-absorbing member beneath it [Full text].
* US5782607 "Replaceable ceramic blade insert": places a replaceable ceramic insert in a propeller leading-edge sheath at the outboard end where erosion is highest [Full text].
* US20050169763A1 "Helicopter rotor and method of repairing same": repair with a polyurethane leading-edge strip [Full text].
* Related documents seen in citation lists: US7246998B2 "Mission replaceable rotor blade tip section," US5885059A "Composite tip cap assembly for a helicopter main rotor blade," EP3275783B1 "Rotor blade erosion protection systems" [Cited].

Takeaway: Replaceable leading-edge protection designed to wear away is a mature, patent-dense area in rotor and propeller engineering.

### 1.4 Icebreaker ice belts: hull form, materials, coatings
**Hull form and geometry (approaches that make ice fail in bending via curved and sloped surfaces)**
* US4715305 "Ship's hull" (Wärtsilä; priority 1984, issued 1987): icebreaking hull form [Full text: bibliographic data and citation relations].
* US5176092 "Icebreaker bow and hull form" (Newport News Shipbuilding, 1993): V-shaped bow and S-shaped stem with a lower wedge [Full text].
* US4436046 "Ice-breaking hull": sloping ridges on both sides of the bow deflect floes away from beneath the hull [Summary].
* US5325803 "Icebreaking ship" (German priority DE4101034): a hull with balcony-like side flanks and a parapet [Full text]. *Note: the previous revision grouped this patent as a "hull form inducing bending and shear failure via curved and sloped surfaces." The description confirmed this time centers on the side-flank structure. The basis for that citation must be rechecked against the original.*
* CA1311393C "Icebreaker": heats outer plating using heat sources in the hull to reduce ice friction and adhesion [Full text].
* US5660131 "Icebreaker attachment" (Marinette Marine, 1997): an icebreaking attachment that selectively connects to and detaches from a parent vessel. As a hull-scale detachable module it is a relatively close prior example to this document's topic [Full text].
* *Note: US4351255, cited in the previous revision, could not be verified in this survey. It is not cited until confirmed.*

**Ice-belt materials and coatings (commercial technology)**
* Classification societies (Lloyd's Register, DNV, the Russian Maritime Register and others) require increased ice-belt plate thickness against ice abrasion, and some recognize the benefit of certified abrasion-resistant coatings (Intershield 163 / Inerta 160, AkzoNobel product material [Manufacturer material]).
* PPG SIGMASHIELD 1200 was applied to four icebreakers, and a diving survey reported no damage on coated vertical sides (BIC Magazine [Manufacturer case]).
* Ecospeed (Subsea Industries) claims ice-belt plate thickness can be reduced by up to 1 mm [Manufacturer material].
* The Russian nuclear icebreaker Leader (Project 10510) was reported to use a clad-steel ice belt of roughly 50 mm steel with 5 mm stainless cladding, while the Arktika class (22220) uses an Inerta-type epoxy coating instead of cladding (Nuclear Engineering International [Summary]). An explosion-welded stainless ice belt (the Botnica example) was confirmed only from a secondary source [Secondary source].
* US10774396 "Seawater-resistant stainless clad steel": addresses abrasion and pitting resistance of stainless clad steel and mentions corrosion resistance in crevices formed by attached barnacles [Full text].
* US4968538 and US4789567 "Abrasion resistant coating and method of application": abrasion-resistant coatings with ceramic particles dispersed in a corrosion-resistant resin [Summary].

**Ice loads and ice resistance models**
* Lindqvist (1989), "A straightforward method for calculation of ice resistance of ships," *Proc. 10th POAC*, Luleå, vol. 2, pp. 722–735: a model dividing ice resistance into crushing, bending and submersion components. Later modified by Riska et al. (1997) [Summary].
* Pressure–area relationship: Sanderson (1988) compiled pressure–area data, and Masterson & Frederking (1993) compiled local ice pressures, both showing the area effect in which local ice pressure falls as contact area grows. Later papers cite a relation of the form p = 8.1·a^-0.5 (p in MPa, a in m²) used in design codes (API RP 2N, CSA S471) (*Cold Regions Science and Technology* [Summary]). Palmer & Sanderson (1991) explained the effect with fractals and linear elastic fracture mechanics [Cited]. The definition and application of the area effect remain debated [Summary].

Takeaway: Curved and sloped hull forms, abrasion-resistant coatings, clad steel and ice-resistance models are all already-public prior areas. No document directly addressing a replaceable or progressively wearing sacrificial module mounted on an ice belt was found in this survey (this does not mean none exists; see Section 5).

### 1.5 Weld-free, clamp-attached marine structures
* CN104314061A "Detachable ice-resistant device applicable to offshore nuclear power platform": semicircular cylinder halves clamp the pile leg, self-locking joins and releases them, and it allows repeated installation and removal, with a bending-failure cone that reduces ice load [Full text]. This is the closest prior example to "weld-free clamp attachment plus inducing bending failure of ice."
* EP2275677A2 "Device for reducing ice loads on a pile foundation for an offshore wind turbine": an ice cone built as a permeable strut structure so that wave and wind loads are not increased [Full text].
* US20110006538A1 / EP2185816A1 / WO2009026933A1 "Monopile foundation for offshore wind turbine": a secondary structure is clamped around the pile, and clamps are described as less prone to damage from impact than bolts [Full text].
* US5079805 "Fastener for protective sleeves": a fastener for wrapped sleeves that protect pier piles from corrosion, decay and marine-organism attachment [Full text].
* WO2016095052A9 "Composite sleeve for piles": a composite sleeve reducing adfreeze uplift loads, with a top lock using a bolt, welded collar or clamp [Full text].

Takeaway: Clamp-type protective sleeves around piles and legs, and detachable ice cones, have many prior examples. Beyond US5660131 (a hull-scale attachment), no direct example of clamp-type modules on a ship hull shell plate was found in this survey.

### 1.6 General background for structural sacrifice
* Béla Barényi (1951), automotive passive safety (crumple-zone) concept. Cited as the classic background for dissipating impact energy through structural deformation.

---

## 2. Environmental and Biosecurity Issues When Using Attached Organisms (Summary of Prior Literature)

Using attached organisms as protective layers collides directly with invasive-species transfer on ships. The following retains and condenses literature organized in earlier revisions. It records known limits and is not an assertion.

* **International guidelines**: In 2011 the IMO adopted Resolution MEPC.207(62), guidelines for the control and management of ships' biofouling, which describes hull biofouling as an important pathway for transfer of invasive aquatic species.
* **Port-state rules**: New Zealand's Ministry for Primary Industries (MPI) Craft Risk Management Standard is known to have required, since 2018, that hulls of arriving vessels be free of fouling (mostly allowing only a slime layer), and California has biofouling management regulations (California Code of Regulations, title 2, section 2298.1 et seq.). Detailed requirements may be revised and must be checked before any real application.
* **Microbial transfer**: Hull fouling includes biofilms, and literature exists showing that bivalves can accumulate bacteria and viruses through filter feeding. Pathogenic *Vibrio parahaemolyticus* has been reported in biofouling on the outer hulls of commercial vessels (Revilla-Castellanos et al., 2015). No study directly examining viruses in the outer-hull fouling layer was found; most virus literature concerns ballast-tank interiors or shellfish in contaminated coastal and aquaculture settings. Presence and pathogenicity are separate matters.
* **Colony-scale detachment**: No confirmed literature was found on whether fragments of fouling communities released en masse by impact can survive and settle in other waters.
* **In-water cleaning**: Policy briefs and NIWA research (Woods et al., 2012) indicate that in-water cleaning can increase the release of living organisms and microbes.
* **Impact by approach**: Biocidal antifouling paints can chemically affect non-target organisms, colonization-based approaches can mediate transfer of invasive species and microbes, and non-biological ablative approaches also require environmental assessment of the shed material. No approach is declared better than another here.
* **Regulatory compliance**: Conventions, guidelines, national rules and classification rules applying to the entire route (transit and port-call waters, including special polar areas) must be checked, and it is reasonable to consider the stricter requirement first (Article 1(3) of the AFS Convention does not prevent states from taking stricter measures consistent with international law).

---

## 3. Verification Status and Differences from the Earlier Revision

| Item | Result of this survey |
|---|---|
| US4715305 | Bibliographic data and citation relations confirmed. Wärtsilä "Ship's hull" |
| US5325803 | "Icebreaking ship" (balcony-like side flanks). Its purpose may differ from the earlier "bending/shear-inducing hull form" description; recheck needed |
| US4351255 | Could not be verified. Citation withheld |
| Lindqvist (1989) | Bibliography confirmed (POAC 1989, pp. 722–735). Equations not read in the original |
| Pressure–area relation | Form confirmed only at the level of citing papers. Original not read |
| Energy-absorption equation for ice failure reflecting the pressure–area relation | The in-house equation was deleted from this revision. If needed, it should be cited directly from the literature above |

---

## 4. Interpretive Notes (Compiler's Observations, Not Claims)

* Each individual element (bioprotection, replaceable sacrificial protection, curved hull forms, abrasion-resistant coatings, clamp attachment) has its own separate prior area.
* No document was found in this survey scope that directly combines them as "a progressively wearing, replaceable module on an ice belt plus an optional bio-colonization layer." This means "not found this time," not "new."
* No document was found that directly matches symmetric ablation of rotating machinery or tool-free quick-release cartridges. However, replaceable leading-edge protection for rotor blades (Section 1.3) is already abundant.
* Colonization-based approaches have rich prior research on stationary and fixed structures, but on ships that sail across multiple sea areas they may conflict with the regulations in Section 2. This is a fact the literature shows.

---

## 5. Survey Limitations and Items Not Yet Surveyed

* This survey was a single round of mainly English-language searching. An extended round including small-company and individual filings and Korean, Chinese, Russian and Japanese literature was not carried out. Further verification using synonyms and industry terminology will follow.
* Items not searched this time: mineral accretion (Biorock family), historical sacrificial sheathing on wooden ships, synthetic calcium carbonate analogues, hardness-gradient sacrificial layers and pre-segmented cell structures, colonization pockets on curved scaffolds, literature on mitigating rotor unbalance, and sensor monitoring of marine structures.
* Many items were checked only at the level of summaries, abstracts or manufacturer material. Not all originals were read.
* Structural impact analysis, tank tests, and clamp fatigue and freezing tests have not been performed, and there is no plan to perform them.
* Performance figures in manufacturer materials are the manufacturers' own claims.

---

## 6. References and Sources

### 6.1 Standards, conventions, guidelines
ISO 8501; IMO AFS Convention (adopted 2001, in force 2008, Article 1(3)); EU Marine Strategy Framework Directive (MSFD); classification-society Ice Class rules (KR, DNV, ABS, Lloyd's Register); IMO Resolution MEPC.207(62) (2011); New Zealand MPI Craft Risk Management Standard; California Code of Regulations, title 2, section 2298.1 et seq.; API RP 2N; CSA S471.

### 6.2 Patents (bibliographic data checked this time)
US4715305; US5325803; US5176092; US4436046; CA1311393C; US5660131; US5542820; US8858184B2; US9429025B2; US20130101432A1; EP2585370A2; US20100008788A1; US5782607; US20050169763A1; US7246998B2 [Cited]; US5885059A [Cited]; EP3275783B1 [Cited]; US10774396; US4968538; US4789567; US8575231; US5472993; US4914141; CN104314061A; EP2275677A2; US20110006538A1; EP2185816A1; WO2009026933A1; US5079805; WO2016095052A9; RE42259.

### 6.3 Papers and reviews
* Lindqvist G (1989) A straightforward method for calculation of ice resistance of ships. *Proc. 10th POAC*, Luleå, 722–735.
* Sanderson TJO (1988) *Ice Mechanics: Risks to Offshore Structures*; Masterson DM, Frederking RMW (1993) Local contact pressures in ship/ice and structure/ice interactions. *Cold Regions Science and Technology*; Palmer AC, Sanderson TJO (1991).
* Bioerosive and bioprotective role of barnacles on rocky shores. *Science of the Total Environment*.
* Combined protective action of barnacles and biofilm on concrete surface in intertidal areas. *Construction and Building Materials*.
* The bioprotective properties of the blue mussel (*Mytilus edulis*) on intertidal rocky shore platforms.
* Oyster breakwater reefs promote adjacent mudflat stability and salt marsh growth in a monsoon dominated subtropical coast. *Scientific Reports* (2019).
* Nature-based solutions for coastal protection in sheltered and exposed coastal waters. *Environmental Monitoring and Assessment* (2024), DOI 10.1007/s10661-024-12480-x.
* Perkol-Finkel S, Sella I, "Blue is the new green: Ecological enhancement of concrete based coastal and marine infrastructure." *Ecological Engineering*.
* Kiil S et al., dynamic simulations of a self-polishing antifouling paint (*JCT Coatings Tech*); Tin-free self-polishing marine antifouling coatings (review).

### 6.4 Biofouling and biosecurity (retained from earlier revisions; abstract-level; originals need checking)
Drake LA et al. (2005) *Biological Invasions* 7:969-982; Drake LA, Doblin MA, Dobbs FC (2007) *Marine Pollution Bulletin* 55:333-341, DOI 10.1016/j.marpolbul.2006.11.007; Martinez-Albores A et al. (2020) *Foods* 9(2):129; McLeod C et al. (2017) *Comprehensive Reviews in Food Science and Food Safety* 16(4):692-706; Revilla-Castellanos VJ et al. (2015) *Biofouling* 31(3):275-282, DOI 10.1080/08927014.2015.1038526; Georgiades E, Scianni C, Tamburri MN (2023) *Frontiers in Marine Science* 10:1197366; Scianni C et al. (2023) *Frontiers in Marine Science* 10:1239723; Tamburri MN et al. (2021) *Frontiers in Marine Science* 8:804766, DOI 10.3389/fmars.2021.804766; Woods CMC, Floerl O, Jones L (2012) *Marine Pollution Bulletin* 64:1392-1401, DOI 10.1016/j.marpolbul.2012.04.019; Floerl O et al. (2005) MPI Technical Paper No. 08/12.
Environmental effects of antifouling paints: Thomas KV, Brooks S (2010) *Biofouling* 26(1):73-88, DOI 10.1080/08927010903216564; Konstantinou IK, Albanis TA (2004) *Environment International* 30:235-248, DOI 10.1016/S0160-4120(03)00176-4; Alzieu C (2000) *Science of the Total Environment* 258:99-102; Soroldoni S et al. (2018) on antifouling paint particles (bibliography needs checking); *Marine Pollution Bulletin* 169:112529 (2021, authors need checking).

### 6.5 Commercial products and manufacturer material (manufacturers' own claims)
AkzoNobel International Intershield 163 Inerta 160; PPG SIGMASHIELD 1200; Subsea Industries Ecospeed; ECOncrete case-study material; CORDIS Living Ports (project 970972); Port of San Francisco / SERC Living Seawall.

### 6.6 Prior art invoked
Béla Barényi (1951), automotive passive safety concept (crumple zone).

---

## 7. Attribution, License and How This Was Written

* Credit for all technical content in this document belongs to the authors, inventors, institutions and manufacturers of the sources above. The compiler only collected and organized the material.
* The text is released under CC BY 4.0. Anyone quoting or reusing it is encouraged to credit both this repository and the original sources.
* General-purpose generative AI tools were used for text organization and bibliographic searching, and the compiler organized the document reflecting review comments. Responsibility for errors and omissions rests with the compiler.
* If you find errors in the bibliography, patent numbers or figures in this document, please let us know. They will be corrected as they are confirmed.

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
