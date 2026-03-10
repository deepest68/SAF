# Fischer-Tropsch 합성 기술 문서: e-SAF 제조를 위한 촉매·반응기 개발 역사

## 개요

e-SAF(electro-Sustainable Aviation Fuel)는 재생에너지에서 생산된 수소와 포집된 CO₂로부터 합성 가스(Syngas, CO + H₂)를 만들고, 이를 Fischer-Tropsch(FT) 합성을 통해 항공유로 전환하는 경로를 포함합니다. FT 합성은 1923년 Franz Fischer와 Hans Tropsch에 의해 개발된 이래 촉매, 반응기, 공정 구성 모두에서 지속적인 발전을 이루어 왔습니다. 본 문서는 FT 합성의 역사적 발전 과정을 촉매 시스템, 반응 조건, 반응기 유형을 중심으로 정리합니다.

---

## 1. Fischer-Tropsch 합성 반응 개요

### 1.1 기본 반응

FT 합성의 핵심 반응은 합성 가스(CO + H₂)를 탄화수소 혼합물로 전환하는 것입니다.

**주반응:**
```
nCO + (2n+1)H₂ → CₙH₂ₙ₊₂ + nH₂O   (파라핀)
nCO + 2nH₂     → CₙH₂ₙ   + nH₂O   (올레핀)
```

**수성가스 전환 반응 (Water-Gas Shift, WGS):**
```
CO + H₂O ⇌ CO₂ + H₂
```

### 1.2 Anderson-Schulz-Flory (ASF) 분포

FT 합성 생성물은 탄소 수 분포를 나타내며, 이는 ASF 모델로 설명됩니다:

```
Wₙ/n = (1-α)² · αⁿ⁻¹
```

- **α**: 연쇄 성장 확률(chain growth probability)
- α 값이 높을수록 고분자량(왁스) 생성물 비율 증가
- 항공유(C₈–C₁₆) 범위: α ≈ 0.85–0.92

---

## 2. Fischer-Tropsch 합성의 역사적 발전

### 2.1 초기 발전 단계 (1923–1945)

| 연도 | 주요 사건 |
|------|-----------|
| 1923 | Fischer & Tropsch, Kaiser Wilhelm Institute에서 최초 FT 합성 성공 (Fe, Ni, Co 촉매) |
| 1926 | 최초의 실용적 Co 및 Fe 촉매 개발 |
| 1934 | 독일 Ruhr-Chemie AG, 최초 상업 규모 공장 건설 착수 |
| 1938 | 독일 전역 9개 FT 공장 운영 (총 생산량 약 660,000 톤/년) |
| 1944 | 2차 세계대전 중 독일 FT 생산 정점 도달 |

- 초기 촉매: 코발트계(Co/ThO₂/MgO/kieselguhr) — 100°C, 1기압에서 활성
- 반응기: 고정층(fixed-bed) 반응기 사용

### 2.2 전후 기술 이전 및 남아공 Sasol 시대 (1945–1990)

| 연도 | 주요 사건 |
|------|-----------|
| 1950 | 미국 Bureau of Mines, 철 기반 촉매 연구 심화 |
| 1955 | 남아공 Sasol, Sasolburg에 최초 상업 FT 플랜트 가동 (Sasol I) |
| 1967 | Sasol, 순환 유동층(CFB) 반응기(Synthol reactor) 도입 |
| 1980 | Sasol II (Secunda), 고온 FT (HTFT) 기반 대규모 생산 |
| 1982 | Sasol III 완공; 연간 수백만 톤 생산체계 완성 |

- 이 시기 주요 기술: 철계 촉매 기반 고온 FT(HTFT, 300–350°C) + Synthol CFB 반응기

### 2.3 Shell SMDS 및 저온 FT 기술 (1990–2000)

| 연도 | 주요 사건 |
|------|-----------|
| 1993 | Shell, 말레이시아 Bintulu에 SMDS(Shell Middle Distillate Synthesis) 플랜트 가동 |
| 1993 | Co/SiO₂, Co/Al₂O₃ 계열 촉매로 저온 FT(LTFT, 200–240°C) 왁스 생산 |
| 1990s | Slurry Bubble Column Reactor(SBCR) 개발 본격화 |

### 2.4 현대 FT 기술 혁신 (2000–현재)

| 연도 | 주요 사건 |
|------|-----------|
| 2007 | Sasol-Qatar Petroleum, Oryx GTL 플랜트 가동 (34,000 bbl/day, LTFT) |
| 2011 | Shell Pearl GTL 완공 (카타르, 140,000 bbl/day — 세계 최대) |
| 2010s | 나노 구조 촉매, 코어-셸 촉매 개발 |
| 2015~현재 | Power-to-Liquid(PtL) 개념에 FT 통합 — e-SAF 경로 부상 |
| 2020~현재 | 마이크로채널 반응기, 3D 프린팅 반응기 등 집적화 기술 개발 |

---

## 3. 대표적 촉매 시스템

### 3.1 철(Fe) 기반 촉매

**특징:**
- 저렴한 원료, 풍부한 매장량
- WGS 활성이 높아 낮은 H₂/CO 비율(~1.0)에서도 사용 가능
- 고온 및 저온 FT 모두에 사용 가능

**대표 조성:**
```
Fe/K₂O/SiO₂ (침전 촉매)
Fe/Cu/K/SiO₂ (융합 촉매, fused iron catalyst)
```

**촉진제(Promoter) 역할:**
| 촉진제 | 역할 |
|--------|------|
| K (포타슘) | 염기성 증가 → 올레핀 선택성, 고분자량 생성물 증가 |
| Cu | Fe 환원 촉진 |
| SiO₂ | 구조적 안정제, 분산도 향상 |

**활성 상(Active phase):**
- 환원 후 금속 Fe → 반응 중 Fe₅C₂(Hägg carbide), ε-Fe₂C 등 철 카바이드로 전환

**반응 조건:**
| 구분 | 조건 |
|------|------|
| 온도 | 150–350°C (HTFT: 300–350°C, LTFT: 200–260°C) |
| 압력 | 10–40 bar |
| H₂/CO 비율 | 0.5–2.5 |
| 공간 속도 | 500–2000 h⁻¹ (GHSV) |

---

### 3.2 코발트(Co) 기반 촉매

**특징:**
- 높은 선택성 — 고분자량 파라핀(왁스) 생성에 유리
- WGS 활성 낮음 → H₂/CO = 2.0 필요
- CO₂ 생성 최소화
- 내구성 우수, 탄소 침적(coking) 낮음

**대표 조성:**
```
Co/Al₂O₃
Co/SiO₂
Co/TiO₂
Co/SiO₂ (Shell SMDS, 15–30 wt% Co)
```

**촉진제(Promoter) 역할:**
| 촉진제 | 역할 |
|--------|------|
| Re (레늄) | Co 환원 촉진, 소결 억제 |
| Pt, Ru (귀금속) | 환원성 향상, 분산도 증가 |
| Zr, La | 담체 안정화, 금속-담체 상호작용 조절 |
| Mn | 올레핀 선택성 증가 |

**반응 조건:**
| 구분 | 조건 |
|------|------|
| 온도 | 190–240°C |
| 압력 | 20–35 bar |
| H₂/CO 비율 | 1.8–2.2 |
| 공간 속도 | 100–1000 h⁻¹ (GHSV) |

**비활성화 메커니즘:**
1. 소결(Sintering): Co 입자 성장 → 활성 면적 감소
2. 황 피독(S-poisoning): 1 ppm S도 치명적 영향
3. 탄소 침적
4. 산화 (Co → CoO, Co₃O₄)

---

### 3.3 루테늄(Ru) 기반 촉매

**특징:**
- 가장 높은 FT 활성 및 연쇄 성장 확률
- α 값 최대 → 초고분자량 왁스(polyethylene-like) 생성
- 희소 금속, 높은 비용 → 상업 적용 제한

**대표 조성:**
```
Ru/Al₂O₃
Ru/TiO₂
Ru/SiO₂
```

**반응 조건:**
| 구분 | 조건 |
|------|------|
| 온도 | 150–200°C |
| 압력 | 10–100 bar |
| H₂/CO 비율 | 2.0 |

---

### 3.4 촉매 시스템 비교 요약

| 특성 | Fe | Co | Ru |
|------|----|----|-----|
| 비용 | 낮음 | 중간 | 매우 높음 |
| WGS 활성 | 높음 | 낮음 | 낮음 |
| H₂/CO 요구 비율 | 0.5–1.7 | ~2.0 | ~2.0 |
| 최적 온도 (°C) | 200–350 | 190–240 | 150–200 |
| α (연쇄 성장) | 0.65–0.95 | 0.70–0.95 | 0.85–1.00 |
| 주요 생성물 | 올레핀, 옥시게네이트 | 왁스, 파라핀 | 왁스 |
| 황 내성 | 중간 | 낮음 | 낮음 |
| 상업 적용 | Sasol (HTFT/LTFT) | Sasol Oryx, Shell SMDS | 연구 단계 |

---

## 4. 반응기 유형 및 발전 역사

### 4.1 고정층 반응기 (Fixed-Bed Reactor, FBR)

**원리:** 촉매를 관형 반응기 내에 충진하고 syngas를 통과시키는 방식

**유형:**
- **Multi-tubular Fixed-Bed Reactor (MTFBR)**: 수백~수천 개의 소관을 가진 쉘-앤-튜브 구조
  - 냉각수가 쉘 측 유동, 반응이 튜브 측에서 진행
  - Shell ARGE 반응기(1955~), SMDS 반응기
  
**특징:**
| 항목 | 내용 |
|------|------|
| 장점 | 촉매 분리 용이, 조작 단순 |
| 단점 | 열 제거 어려움, 핫스팟(hot spot) 형성, 촉매 교체 시 장기 정지 |
| 운전 조건 | LTFT: 220–250°C, 25–45 bar |
| 규모 | 중소규모 적합 |

```
[구조 개략도]
합성가스 →  ┌──────────┐
             │  촉매 충진 │ ← 냉각수
합성물 ←    └──────────┘
```

---

### 4.2 유동층 반응기 (Fluidized-Bed Reactor, FBR)

**4.2.1 순환 유동층 반응기 (Circulating Fluidized-Bed, CFB)**
- Sasol의 Synthol 반응기 (1955년 도입)
- 고온 FT (HTFT): 320–350°C, 20–25 bar
- 주로 가솔린, 올레핀, 화학원료 생산

**4.2.2 고정 유동층 반응기 (Fixed Fluidized-Bed, FFB)**
- Sasol Advanced Synthol (SAS) 반응기 (1989년 도입)
- Synthol CFB 대비 압력 강하 감소, 스케일업 용이
- 현재 Sasol Secunda 플랜트 운영 중

**특징:**
| 항목 | 내용 |
|------|------|
| 장점 | 우수한 열 제거, 균일 온도 분포, 촉매 연속 교체 가능 |
| 단점 | 촉매 마모, 가스-액체 분리 필요, Fe 촉매만 적용 |
| 운전 조건 | HTFT: 300–350°C, 20–40 bar |

---

### 4.3 슬러리 버블 컬럼 반응기 (Slurry Bubble Column Reactor, SBCR)

**원리:** 액체 왁스에 촉매 입자를 현탁시키고, 하부에서 합성 가스를 기포 형태로 공급

**역사:**
- 1950년대 독일에서 개념 개발
- 1990년대 Sasol과 Exxon이 본격 상업화
- 1993년 Sasol SSBR(Sasol Slurry Bed Process) 개발
- 2007년 Oryx GTL(카타르) 상업 가동 — Co/Al₂O₃, SBCR

**특징:**
| 항목 | 내용 |
|------|------|
| 장점 | 우수한 열 전달, 저압력 강하, 촉매 연속 교체, 스케일업 용이 |
| 단점 | 촉매-왁스 분리 어려움, 역혼합(backmixing) |
| 운전 조건 | LTFT: 200–240°C, 20–30 bar |
| 적용 촉매 | Fe, Co (입경 20–200 μm) |

```
[구조 개략도]
                ↑ 생성물 가스+왁스
┌─────────────────────┐
│   슬러리 (왁스+촉매) │ ← 냉각코일
│  ○ ○ ○ ○ ○ ○ ○    │
│ ○ ○ ○ ○ ○ ○ ○ ○   │
└─────────────────────┘
            ↑
        합성가스 (버블)
```

---

### 4.4 마이크로채널 반응기 (Microchannel Reactor)

**원리:** 수백 μm 채널 내에서 반응 수행 — 열·질량 전달 대폭 향상

**역사:**
- Velocys(구 BattellePNL), Compact GTL 등이 2000년대부터 개발
- 2014년 Velocys, 첫 상업 데모 플랜트 가동
- e-SAF PtL 경로에서 분산형·소규모 FT 공정으로 주목

**특징:**
| 항목 | 내용 |
|------|------|
| 채널 폭 | 0.1–5 mm |
| 장점 | 핫스팟 제거, 빠른 열 제거, 소형화, 고선택성 |
| 단점 | 제작 비용, 촉매 교체 어려움, 스케일업(넘버링업) 복잡 |
| 운전 조건 | LTFT: 200–240°C, 20–30 bar |

---

### 4.5 반응기 유형 비교 요약

| 반응기 | 온도 범위 | 압력 | 촉매 | 열 제거 | 상업 적용 |
|--------|-----------|------|------|---------|-----------|
| 고정층(MTFBR) | 220–250°C | 25–45 bar | Co, Fe | 보통 | Shell ARGE, SMDS |
| 유동층 CFB | 320–350°C | 20–25 bar | Fe | 우수 | Sasol Synthol |
| 유동층 SAS | 320–350°C | 20–40 bar | Fe | 우수 | Sasol Secunda |
| 슬러리 SBCR | 200–240°C | 20–30 bar | Co, Fe | 매우 우수 | Sasol Oryx, Shell Pearl |
| 마이크로채널 | 200–240°C | 20–30 bar | Co | 최우수 | Velocys, CompactGTL |

---

## 5. e-SAF를 위한 FT 공정 구성요소

### 5.1 전체 공정 흐름

```
재생전력 → 전기분해(Electrolyzer) → H₂
CO₂ 포집 → 역수성가스전환(rWGS) → CO
                                      ↓
                               Syngas (H₂+CO)
                                      ↓
                        Fischer-Tropsch 합성 반응기
                                      ↓
                          FT 왁스/나프타/경유 혼합물
                                      ↓
                    수소화 처리(Hydrocracking/Hydroisomerization)
                                      ↓
                            e-SAF (항공유) + 나프타
```

### 5.2 핵심 공정 구성요소

#### (1) Syngas 생산

| 기술 | 설명 | H₂/CO 비율 |
|------|------|-------------|
| 역수성가스전환 (rWGS) | CO₂ + H₂ → CO + H₂O | 조절 가능 |
| 공동 전기분해 (Co-SOEC) | H₂O + CO₂ → H₂ + CO | ~2:1 |
| 자열개질 (ATR) | CH₄ + O₂ + H₂O → CO + H₂ | ~2:1 |
| 바이오매스 가스화 | 바이오매스 → CO + H₂ | 0.5–1.5 |

#### (2) 합성 가스 정제

- **황 제거 (Desulfurization)**: ZnO 흡착제, 수소화 탈황(HDS) — Co/Fe 촉매의 황 피독 방지
- **CO₂ 제거**: 아민 흡수, MDEA 공정
- **H₂/CO 비율 조절**: WGS 반응기, 수소 첨가

#### (3) Fischer-Tropsch 반응기

- 위 4장 참조
- e-SAF 경로: **LTFT (Co 촉매, SBCR 또는 MTFBR)**가 주류
  - 높은 왁스 수율 → 항공유 범위로 수소화 분해

#### (4) 생성물 분리

- **분리증류**: C1–C4(가스), C5–C11(나프타), C12–C18(항공유), C19+(왁스)
- **저온 분리(Cold separator)**: 왁스–가스 분리

#### (5) 수소화 처리 (Upgrading)

| 공정 | 설명 | 촉매 |
|------|------|------|
| 수소화 분해 (Hydrocracking) | 왁스(C19+) → 항공유(C8–C16) | Pt/zeolite, NiMo/Al₂O₃ |
| 수소화 이성화 (Hydroisomerization) | n-paraffin → iso-paraffin (동결점 개선) | Pt/SAPO-11, Pd/zeolite |
| 수소화 탈황/탈질 | 잔여 황·질소 제거 | CoMo/Al₂O₃ |

#### (6) 유틸리티 및 열통합

- **열 회수**: FT 반응열(−165 kJ/mol CO) → 증기 생산, 예열
- **물 관리**: FT 반응 부산물 H₂O 처리
- **미전환 syngas 재순환**: 전환율 향상 (재순환 비율 0.5–2.5)

### 5.3 e-SAF FT 공정의 주요 운전 파라미터

| 파라미터 | 조건 | 비고 |
|----------|------|------|
| FT 반응 온도 | 200–240°C | LTFT, Co 촉매 |
| FT 반응 압력 | 20–30 bar | SBCR 기준 |
| H₂/CO 비율 (feed) | 2.0–2.1 | Co 촉매 최적 |
| CO 전환율 | 60–80% (1pass) | 재순환 포함 시 >95% |
| α 값 | 0.88–0.92 | 항공유 범위 최적화 |
| 공간속도 (GHSV) | 100–500 h⁻¹ | SBCR 기준 |
| 에너지 효율 | 60–70% (HHV) | 전기→SAF |

---

## 6. 최신 연구 동향 (2015~현재)

### 6.1 촉매 분야

- **나노 코발트 촉매**: 입경 6–8 nm에서 최적 활성·안정성 (Bezemer et al., 2006)
- **코어-셸 구조**: Co@SiO₂, Co@C — 소결 억제, 황 내성 향상
- **bimetallic 촉매**: Co-Fe, Co-Ni — 선택성 및 비용 균형
- **구조화 촉매 (Structured catalyst)**: 3D 프린팅, 모노리스 구조
- **DFT 계산 기반 촉매 설계**: 활성 위치 최적화

### 6.2 반응기 분야

- **마이크로채널 반응기 상업화**: Velocys, CompactGTL (e-SAF 경로 특화)
- **3D 프린팅 반응기**: 맞춤형 유동 채널 설계
- **분산형 소규모 FT**: PtL e-SAF 위한 모듈식 공정 (< 1,000 bbl/day)

### 6.3 공정 통합 분야

- **공동 전기분해 + FT**: SOEC–FT 통합 시스템
- **CO₂ 직접 FT**: CO₂ + H₂ → 탄화수소 (Na–Fe₃O₄/HZSM-5 촉매)
- **바이오매스 + PtL 하이브리드**: 원료 다각화

---

## 7. 주요 상업 공정 사례

### 7.1 Sasol Secunda (남아공)

- **규모**: ~160,000 bbl/day (세계 최대 FT 생산)
- **촉매**: 철계 융합 촉매 (fused Fe/K)
- **반응기**: SAS (Fixed Fluidized-Bed)
- **운전 조건**: HTFT, 340°C, 25 bar
- **원료**: 석탄 가스화 → syngas

### 7.2 Shell SMDS / Pearl GTL (카타르)

- **규모 (Pearl)**: 140,000 bbl/day
- **촉매**: Co/SiO₂ (15–30 wt%)
- **반응기**: Multi-tubular Fixed-Bed
- **운전 조건**: LTFT, 220–240°C, 30–40 bar
- **원료**: 천연가스 개질 → syngas

### 7.3 Sasol Oryx GTL (카타르)

- **규모**: 34,000 bbl/day
- **촉매**: Co/Al₂O₃
- **반응기**: SBCR (Slurry Bubble Column)
- **운전 조건**: LTFT, 230°C, 25 bar
- **원료**: 천연가스

### 7.4 Velocys Bayou Fuels / e-SAF 데모

- **규모**: ~1,000 bbl/day 급 소규모 모듈형
- **촉매**: Co 기반 마이크로채널용 촉매
- **반응기**: Microchannel Reactor
- **원료**: 폐기물 가스화 또는 PtL syngas

---

## 8. 참고문헌 (References)

### 교과서 및 리뷰 논문

1. **Fischer, F. and Tropsch, H.** (1923). Über die Herstellung synthetischer Ölgemische (Synthol) durch Aufbau aus Kohlenoxyd und Wasserstoff. *Brennstoff-Chemie*, 4, 276–285.

2. **Anderson, R.B.** (1984). *The Fischer-Tropsch Synthesis*. Academic Press, New York.

3. **Dry, M.E.** (2002). The Fischer-Tropsch process: 1950–2000. *Catalysis Today*, 71(3–4), 227–241. https://doi.org/10.1016/S0920-5861(01)00453-9

4. **Schulz, H.** (1999). Short history and present trends of Fischer-Tropsch synthesis. *Applied Catalysis A: General*, 186(1–2), 3–12. https://doi.org/10.1016/S0926-860X(99)00160-X

5. **van der Laan, G.P. and Beenackers, A.A.C.M.** (1999). Kinetics and Selectivity of the Fischer-Tropsch Synthesis: A Literature Review. *Catalysis Reviews*, 41(3–4), 255–318.

6. **Davis, B.H.** (2003). Fischer-Tropsch synthesis: relationship between iron catalyst composition and process variables. *Catalysis Today*, 84(1–2), 83–98.

7. **Khodakov, A.Y., Chu, W., and Fongarland, P.** (2007). Advances in the Development of Novel Cobalt Fischer-Tropsch Catalysts for Synthesis of Long-Chain Hydrocarbons and Clean Fuels. *Chemical Reviews*, 107(5), 1692–1744. https://doi.org/10.1021/cr050972v

8. **de Klerk, A.** (2011). *Fischer-Tropsch Refining*. Wiley-VCH, Weinheim.

9. **Steynberg, A. and Dry, M. (Eds.)** (2004). *Fischer-Tropsch Technology* (Studies in Surface Science and Catalysis, Vol. 152). Elsevier.

10. **Ail, S.S. and Dasappa, S.** (2016). Biomass to liquid transportation fuel via Fischer Tropsch synthesis – Technology review and current scenario. *Renewable and Sustainable Energy Reviews*, 58, 267–286.

### 촉매 관련 논문

11. **Bezemer, G.L. et al.** (2006). Cobalt Particle Size Effects in the Fischer-Tropsch Reaction Studied with Carbon Nanofiber Supported Catalysts. *Journal of the American Chemical Society*, 128(12), 3956–3964. https://doi.org/10.1021/ja058282w

12. **Iglesia, E.** (1997). Design, synthesis, and use of cobalt-based Fischer-Tropsch synthesis catalysts. *Applied Catalysis A: General*, 161(1–2), 59–78.

13. **Tsakoumis, N.E. et al.** (2010). Deactivation of cobalt based Fischer-Tropsch catalysts: A review. *Catalysis Today*, 154(3–4), 162–182.

14. **Torres Galvis, H.M. and de Jong, K.P.** (2013). Catalysts for Production of Lower Olefins from Synthesis Gas: A Critical Review. *ACS Catalysis*, 3(9), 2130–2149.

15. **Jahangiri, H. et al.** (2014). A review of advanced catalyst development for Fischer-Tropsch synthesis of hydrocarbons from biomass derived syn-gas. *Catalysis Science & Technology*, 4, 2210–2229.

16. **Cheng, K. et al.** (2016). Direct and Highly Selective Conversion of Synthesis Gas into Lower Olefins: Design of a Bifunctional Catalyst Combining Methanol Synthesis and Carbon–Carbon Coupling. *Angewandte Chemie International Edition*, 55(15), 4725–4728.

17. **Jiao, F. et al.** (2016). Selective conversion of syngas to light olefins. *Science*, 351(6277), 1065–1068.

### 반응기 관련 논문

18. **Krishna, R. and Sie, S.T.** (2000). Design and scale-up of the Fischer-Tropsch bubble column slurry reactor. *Fuel Processing Technology*, 64(1–3), 73–105.

19. **Sie, S.T. and Krishna, R.** (1999). Fundamentals and selection of advanced Fischer-Tropsch reactors. *Applied Catalysis A: General*, 186(1–2), 55–70.

20. **Tonkovich, A.L. et al.** (2004). Microchannel technology scale-up to commercial capacity. *Chemical Engineering Research and Design*, 83(6), 634–639.

21. **Guettel, R., Kunz, U., and Turek, T.** (2008). Reactors for Fischer-Tropsch Synthesis. *Chemical Engineering & Technology*, 31(5), 746–754.

22. **Myrstad, R. et al.** (2009). Fischer-Tropsch synthesis in a microstructured reactor. *Chemical Engineering Journal*, 149(1–3), 236–241.

### e-SAF / Power-to-Liquid 관련 논문

23. **Schmidt, P. et al.** (2016). *Power-to-Liquids: Potentials and Perspectives for the Future Supply of Renewable Aviation Fuel*. German Environment Agency (Umweltbundesamt), UBA-Texte 09/2016.

24. **Fasihi, M., Bogdanov, D., and Breyer, C.** (2017). Techno-Economic Assessment of Power-to-Liquids (PtL) Fuels Production and Global Trading Based on Hybrid PV-Wind Power Plants. *Energy Procedia*, 99, 243–268. https://doi.org/10.1016/j.egypro.2016.10.115

25. **Neuling, U. and Kaltschmitt, M.** (2018). Techno-economic and environmental analysis of aviation biofuels. *Fuel Processing Technology*, 171, 54–69.

26. **Panzone, C. et al.** (2020). Power-to-Liquid Catalytic CO2 Valorization into Fuels and Chemicals: Focus on the Fischer-Tropsch Route. *Journal of CO2 Utilization*, 38, 314–347.

27. **König, D.H. et al.** (2015). Simulation and evaluation of a process concept for the generation of synthetic fuel from CO₂ and H₂. *Energy*, 91, 833–841.

28. **Vásquez, F.V. et al.** (2018). Power-to-X technology using renewable electricity and carbon dioxide from ambient air: SOLETAIR proof-of-concept and improved process concept. *Energy Technology*, 6(10), 2017–2026.

29. **Hannula, I. and Kurkela, E.** (2012). A parametric modelling study for pressurised steam/O₂-blown fluidised-bed gasification of wood with catalytic reforming. *Bioresource Technology*, 123, 289–298.

30. **Adelung, S. et al.** (2021). Impact of the reverse water-gas shift operating conditions on the Power-to-Liquid fuel production cost. *Fuel Processing Technology*, 223, 106982.

### 산업 보고서 및 표준

31. **IATA** (2022). *SAF Roadmap*. International Air Transport Association.

32. **ICAO** (2022). *CORSIA Eligible Fuels – Life Cycle Assessment Methodology*. International Civil Aviation Organization.

33. **IEA** (2021). *Net Zero by 2050: A Roadmap for the Global Energy Sector*. International Energy Agency.

34. **ASTM International** (2022). *ASTM D7566: Standard Specification for Aviation Turbine Fuel Containing Synthesized Hydrocarbons*. West Conshohocken, PA.

35. **Dry, M.E.** (1990). The Sasol route to chemicals and fuels. In: *Methane Conversion*, Studies in Surface Science and Catalysis, Elsevier.

---

## 부록: 주요 용어 정리

| 약어 | 전체 명칭 | 설명 |
|------|-----------|------|
| FT | Fischer-Tropsch | CO+H₂로부터 탄화수소 합성 |
| LTFT | Low-Temperature FT | 200–260°C, 주로 왁스·디젤 생산 |
| HTFT | High-Temperature FT | 300–350°C, 주로 가솔린·올레핀 생산 |
| SBCR | Slurry Bubble Column Reactor | 슬러리 버블 컬럼 반응기 |
| MTFBR | Multi-Tubular Fixed-Bed Reactor | 다관식 고정층 반응기 |
| CFB | Circulating Fluidized-Bed | 순환 유동층 |
| SAS | Sasol Advanced Synthol | Sasol 고정 유동층 반응기 |
| WGS | Water-Gas Shift | 수성가스 전환 반응 |
| rWGS | Reverse WGS | 역수성가스 전환 반응 (CO₂→CO) |
| ASF | Anderson-Schulz-Flory | FT 생성물 분포 모델 |
| GTL | Gas-to-Liquid | 가스로부터 액체연료 생산 |
| PtL | Power-to-Liquid | 재생전력 기반 액체연료 생산 |
| e-SAF | electro-SAF | 전기 기반 지속가능 항공유 |
| SAF | Sustainable Aviation Fuel | 지속가능 항공유 |
| SOEC | Solid Oxide Electrolysis Cell | 고체산화물 전기분해 셀 |

---

*본 문서는 e-SAF 제조를 위한 Fischer-Tropsch 합성 공정의 촉매·반응기 개발 역사 및 핵심 기술 요소를 정리한 기술 참고 문서입니다.*

*작성일: 2026년 3월*
