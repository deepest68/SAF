# SAF Technical Issues — Compilation

A structured compilation of key technical issues, challenges, and open research questions
related to Sustainable Aviation Fuel (SAF).

---

## Table of Contents

1. [Production Pathway Limitations](#1-production-pathway-limitations)
2. [Feedstock Availability and Sustainability](#2-feedstock-availability-and-sustainability)
3. [Fuel Properties and Aircraft Compatibility](#3-fuel-properties-and-aircraft-compatibility)
4. [Certification and Standards](#4-certification-and-standards)
5. [Infrastructure and Supply Chain](#5-infrastructure-and-supply-chain)
6. [Cost and Scale-Up Challenges](#6-cost-and-scale-up-challenges)
7. [Sustainability Verification and Life-Cycle Assessment](#7-sustainability-verification-and-life-cycle-assessment)
8. [Non-CO₂ Climate Effects](#8-non-co₂-climate-effects)
9. [Future Outlook and R&D Priorities](#9-future-outlook-and-rd-priorities)
10. [References](#10-references)

---

## 1. Production Pathway Limitations

### 1.1 Hydroprocessed Esters and Fatty Acids (HEFA-SPK)
- Currently the **dominant commercial pathway**, accounting for the majority of global SAF production.
- Relies on lipid feedstocks (used cooking oil, animal fats, vegetable oils) that face supply
  constraints and competing uses (e.g., biodiesel, food).
- Conversion efficiency is high (~75–80 wt%), but feedstock scarcity limits long-term scalability.
- Maximum certified blend ratio: **50%** (ASTM D7566 Annex A2).

### 1.2 Fischer-Tropsch Synthesized Paraffinic Kerosene (FT-SPK)
- Converts syngas (from biomass, coal, or natural gas) via the Fischer-Tropsch process.
- High capital expenditure for gasification and FT reactor systems.
- Carbon efficiency of the gasification step is typically 40–60%, meaning a significant fraction
  of feedstock carbon is lost as CO₂ or unconverted char.
- Biomass-to-liquid (BtL) variants face challenges with consistent syngas quality from
  heterogeneous agricultural or forestry residues.
- Maximum certified blend ratio: **50%** (ASTM D7566 Annex A1 and A4).

### 1.3 Alcohol-to-Jet (ATJ-SPK)
- Converts ethanol or isobutanol (from fermentation of sugars or cellulosic biomass) to jet fuel
  via dehydration, oligomerization, and hydrogenation.
- Multi-step process results in relatively low overall carbon efficiency (~30–40% from biomass to
  jet fuel).
- Ethanol feedstock competes directly with fuel-ethanol markets and human food supply chains.
- Maximum certified blend ratio: **50%** (ASTM D7566 Annex A5).

### 1.4 Synthesized Iso-Paraffins (SIP) from Fermented Sugars
- Uses direct microbial fermentation of sugars to produce isomerized paraffins.
- Very low blend ratio ceiling (**10%**, ASTM D7566 Annex A3) due to high iso-paraffin content
  affecting aromatic levels and seal swell characteristics.
- Current production volumes are negligible at commercial scale.

### 1.5 Power-to-Liquid (PtL) / Electrofuels
- Combines green hydrogen (from electrolysis) with captured CO₂ to synthesize Fischer-Tropsch
  or methanol-to-jet fuels.
- Technically promising for near-zero lifecycle GHG, but energy-intensive: overall efficiency
  from renewable electricity to jet fuel is approximately 40–50%.
- Still in demonstration/early commercial phases; no commercial-scale PtL SAF facility was
  operational as of 2025.
- Dependent on abundant low-cost renewable electricity and affordable direct air capture (DAC)
  or point-source CO₂.

### 1.6 Catalytic Hydrothermolysis Jet (CHJ)
- Converts lipid feedstocks via hot water and catalytic cracking to produce a fuller hydrocarbon
  spectrum including cycloalkanes.
- Generates aromatics naturally, potentially addressing the seal-swell issue.
- Maximum certified blend ratio: **50%** (ASTM D7566 Annex A6).
- Limited commercial deployment; higher process complexity than HEFA.

### 1.7 Co-processing in Conventional Refineries
- Co-feeds bio-based oils into existing petroleum refinery hydrotreaters.
- Maximum permissible co-processing fraction: **5%** bio-based feed (ASTM D1655 Annex A1).
- Potential to leverage existing infrastructure, but raises questions about attribution of
  renewable content across product slates.

---

## 2. Feedstock Availability and Sustainability

### 2.1 Lipid Feedstock Constraints
- Global availability of used cooking oil (UCO), animal fats, and dedicated energy crops is
  insufficient to meet long-term aviation fuel demand.
- Estimates suggest HEFA feedstock could realistically supply only 5–15% of jet fuel demand.
- Risk of indirect land-use change (ILUC) when virgin vegetable oils or dedicated energy crops
  are used.

### 2.2 Lignocellulosic Biomass
- Agricultural and forestry residues represent the largest sustainable feedstock category but
  require complex pre-treatment and conversion technologies (gasification, enzymatic hydrolysis).
- Seasonal availability, variable composition (moisture, ash, cellulose/lignin ratio), and
  logistics for low-density biomass add technical complexity.
- Competing demand from pulp/paper, animal bedding, and soil carbon sequestration.

### 2.3 Municipal Solid Waste (MSW)
- MSW gasification can produce syngas for FT-SAF, but contamination (plastics, metals, chlorine)
  requires robust feed pre-processing.
- Regulatory classification of waste-derived SAF varies across jurisdictions, creating
  certification uncertainty.

### 2.4 Algae
- Microalgae can accumulate high-lipid oils suitable for HC-HEFA-SPK (Annex A7, max blend 10%).
- Cultivation is still energy- and water-intensive; production costs remain an order of magnitude
  higher than conventional jet fuel.
- Pond and photobioreactor systems have not yet achieved commercial scale for aviation fuel.

### 2.5 CO₂ as Feedstock (PtL)
- Direct Air Capture (DAC) is technically viable but energy-intensive (~2,000 kWh/tonne CO₂)
  and expensive (USD 400–1,000/tonne CO₂ as of 2025).
- Point-source carbon capture from industrial flue gas is cheaper but geographically constrained.

---

## 3. Fuel Properties and Aircraft Compatibility

### 3.1 Aromatic Content and Seal Swell
- SAF production pathways (especially HEFA, FT, ATJ) yield predominantly paraffinic blends that
  are aromatic-deficient.
- Aviation fuel system seals (O-rings, gaskets) designed for Jet A/A-1 rely on aromatic
  hydrocarbons for dimensional stability ("seal swell").
- Very low aromatic content in neat SAF causes seals to shrink, leading to potential fuel leaks.
- Current ASTM D7566 specifications require a minimum of 8% aromatics in the finished blended
  fuel, necessitating blending with conventional fuel (which contains ~18–25% aromatics).
- This is a key technical barrier to achieving **100% SAF** (neat) operation.

### 3.2 Lubricity
- SAF blends can exhibit lower lubricity than conventional jet fuel.
- ASTM D7566 mandates a lubricity specification (BOCLE wear scar ≤ 0.85 mm), but additive
  packages may be required for some pathways.

### 3.3 Energy Density
- SAF blends generally have a slightly lower volumetric energy density (~1–2% below Jet A)
  due to higher paraffin-to-aromatic ratio.
- Reduced energy density marginally increases fuel burn and payload penalties, which partially
  offsets the carbon benefit on a per-flight basis.

### 3.4 Thermal Stability and Deposits
- Some SAF pathways (e.g., CHJ, PtL) may form different deposit profiles in fuel system heat
  exchangers and injector nozzles under high-temperature conditions.
- Long-term testing in operational conditions is needed to validate maintenance interval impacts.

### 3.5 Cold Flow and Freeze Point
- Paraffinic SAF blends can have higher freeze points than Jet A-1 (limit: −47 °C), depending
  on chain-length distribution.
- Neat HEFA-SPK may have freeze points above −60 °C if dominated by C16–C18 n-paraffins;
  isomerization during processing is required.

### 3.6 Materials Compatibility
- Extended exposure of polymeric fuel-system components to high-SAF blends has not been
  comprehensively tested for all airframe/engine types.
- SAF-specific storage elastomers and composite tank laminates require qualification testing.

---

## 4. Certification and Standards

### 4.1 ASTM D7566 Pathway Approval Process
- Each new production pathway must pass a rigorous multi-phase qualification:
  1. Research report and property database
  2. Fit-for-purpose testing (OEM engine component tests)
  3. Full turbine engine testing
  4. Fleet test with an airline
- The approval timeline typically spans **3–7 years** and costs several million USD per pathway.
- As of 2025, approximately 11 pathways have received ASTM D7566 approval; several more
  (e.g., HDCJ — Hydrothermal Liquefaction, DSHC — Direct Sugar to Hydrocarbons) are in review.

### 4.2 100% SAF Certification (ASTM D4054 / D7566 Neat)
- Commercial use of 100% neat SAF (without blending with fossil jet) requires overcoming the
  8% aromatic specification floor.
- ASTM and OEMs are progressing a "FAST-SAF" (Fit for Purpose Analytical methods for
  100% SAF) initiative, targeting approval for certain platforms by 2030.
- Engine OEM and airframe qualification programs are underway (e.g., Rolls-Royce, CFM, GE,
  Pratt & Whitney, Airbus, Boeing).

### 4.3 Co-processing Recognition
- CORSIA and EU ReFuelEU initially excluded co-processed SAF from eligible supplies due to
  attribution difficulties.
- ICAO is developing co-processing methodologies; EU ReFuelEU allows limited co-processed
  volumes from 2030 with traceability requirements.

### 4.4 Regulatory Fragmentation
- Multiple overlapping schemes govern SAF accounting and sustainability:
  - **CORSIA (ICAO)** — international emissions offset/credit scheme for international aviation.
  - **EU ReFuelEU** — blending mandates: 2% in 2025, rising to 70% by 2050.
  - **US SAF Grand Challenge / Blenders' Tax Credit (BTC 40B/45Z)** — incentive-based.
  - **UK Jet Zero SAF mandate** — blending mandate introduced 2025.
  - **ASTM D7566 / D1655** — technical fuel quality standards (global).
- Differing sustainability criteria across jurisdictions create compliance complexity and
  potential "SAF credit" arbitrage.

### 4.5 Sustainability Certification Bodies
- Major certification schemes: RSB (Roundtable on Sustainable Biomaterials), ISCC PLUS,
  RedCert², SBP (Sustainable Biomass Program).
- Airlines operating across multiple jurisdictions must maintain concurrent certifications.
- Chain-of-custody documentation from feedstock origin to aircraft wing is complex and
  auditing-intensive.

---

## 5. Infrastructure and Supply Chain

### 5.1 Airport Hydrant and Tankage Systems
- Most major airports operate commingled fuel infrastructure (no segregation of SAF from
  conventional jet fuel).
- Physical uplift of SAF is concentrated at a small number of hub airports; point-to-point
  SAF delivery is logistically challenging.
- Retrofitting airports for dedicated SAF storage is capital-intensive; business models for
  shared infrastructure have not been standardized.

### 5.2 Book-and-Claim Accounting
- Because SAF is typically blended at origin and cannot be physically tracked to a specific
  aircraft, "book-and-claim" (B&C) accounting systems allow airlines to purchase SAF
  certificates separately from the physical fuel.
- Lack of a universally accepted B&C standard creates reputational and regulatory risks.
- Multiple competing B&C registries (RSB, ACT, CORSIA) with differing scopes and rules.

### 5.3 Blending Location Constraints
- ASTM D7566 requires that SAF be blended with conventional jet fuel before distribution through
  the common fuel system.
- Blending must occur at a certified facility; not all pipeline terminal operators are equipped
  or incentivized to do so.

### 5.4 Global Distribution
- SAF production is geographically concentrated (principally USA, Europe, and parts of Asia),
  while demand is global.
- Long-haul transport of SAF (e.g., transoceanic shipping) increases cost and lifecycle GHG.
- Regional feedstock availability mismatches with refinery locations limit localized production.

### 5.5 Pipeline Co-mingling
- Long-distance pipelines routinely commingle fuels, which makes physical batch tracking of
  SAF impractical without dedicated lines.
- Pipeline operators face certification and insurance issues for co-mingled flows.

---

## 6. Cost and Scale-Up Challenges

### 6.1 Production Cost Premium
- SAF currently trades at a significant premium to Jet A:
  - HEFA-SAF: ~2–3× the price of fossil jet fuel.
  - FT-SAF: ~3–5× the price of fossil jet fuel.
  - PtL-SAF: ~5–10× the price of fossil jet fuel, depending on electricity cost.
- EU average SAF price in 2024: approximately €2,085/tonne vs. ~€734/tonne for Jet A.
- High costs primarily driven by feedstock, capital recovery, green hydrogen (for PtL), and
  small production volumes.

### 6.2 Capital Investment Barriers
- Large-scale biorefineries and PtL plants require capital investments of USD 500 million–
  several billion dollars each.
- Lenders and investors face revenue risk due to volatile SAF offtake prices, uncertain policy
  continuity, and first-of-a-kind technology risk.
- Long financing tenors (15–20 years) are difficult to match with policy certainty horizons.

### 6.3 Scaling from Demonstration to Commercial
- Many advanced pathways (gasification + FT, PtL, HTL) are at TRL 6–8; bridging to commercial
  TRL 9 requires demonstration plants at 10–100× current scale.
- Scale-up introduces engineering unknowns: reactor scaling laws, catalyst deactivation, heat
  integration losses.

### 6.4 Competing Carbon-Reduction Pathways
- Airlines may prioritize other near-term abatement options (fleet renewal, operations optimization,
  carbon offsets) over expensive SAF procurement.
- Hydrogen-powered and battery-electric aircraft (longer-term) may alter the investment calculus
  for SAF infrastructure.

### 6.5 Fossil Fuel Subsidy Distortions
- Fossil jet fuel remains partially or fully exempt from energy/excise taxes in many jurisdictions.
- Continued direct and indirect subsidies for conventional fuel raise the relative cost hurdle
  for SAF.

---

## 7. Sustainability Verification and Life-Cycle Assessment

### 7.1 Lifecycle GHG Methodologies
- Different LCA frameworks yield different SAF GHG reduction estimates:
  - **CORSIA methodology** (ICAO Annex 16 Vol. IV): uses core LCA with default values.
  - **EU RED III** lifecycle approach: applies ILUC factors and prescriptive default emission
    values.
  - **US EPA / DOE GREET model**: uses a different system boundary and co-product allocation.
- The same feedstock/pathway can yield GHG reduction factors ranging from 40% to 90%+ depending
  on the methodology, creating regulatory arbitrage risk.

### 7.2 Indirect Land Use Change (ILUC)
- ILUC arises when crop-based feedstocks displace food/feed crops, leading to deforestation or
  grassland conversion elsewhere.
- ILUC values are model-dependent and highly uncertain; they can substantially erode or negate
  GHG benefits.
- EU RED III includes ILUC penalties; US frameworks have not yet incorporated ILUC penalties
  into SAF incentive calculations.

### 7.3 Carbon Intensity of Co-products
- SAF production generates valuable co-products (e.g., bio-naphtha, bio-LPG, bio-diesel).
- System-expansion vs. allocation approaches to co-products yield significantly different
  jet fuel carbon intensities.
- No internationally harmonized co-product allocation methodology exists.

### 7.4 Sustainability of Waste Feedstocks
- Used Cooking Oil (UCO) fraud/adulteration risk: imported UCO can be difficult to verify as
  genuinely waste-derived, especially when sourced from regions with less robust supply chain
  oversight.
- Mass balance and physical segregation schemes for UCO and animal fats require enhanced
  third-party auditing.

### 7.5 Water Use and Land Footprint
- Energy crop cultivation for SAF can have significant water demands, particularly in
  water-scarce regions.
- Microalgae cultivation requires large land footprints or controlled-environment capital.
- Soil carbon impacts of residue removal (preventing return to fields) need accounting.

---

## 8. Non-CO₂ Climate Effects

### 8.1 Contrail Formation and Persistent Contrail Cirrus
- Aviation contrails and contrail cirrus are estimated to have a net warming effect comparable
  to or exceeding the total cumulative CO₂ warming from aviation.
- SAF's lower aromatic and sulfur content may reduce soot particle emissions, potentially
  suppressing persistent contrail formation.
- Research is ongoing; the magnitude of contrail reduction benefit from SAF varies by atmospheric
  condition and flight trajectory.

### 8.2 Nitrogen Oxides (NOₓ)
- NOₓ emissions from aircraft engines contribute to ozone formation (warming) and methane
  destruction (cooling), with net effect dependent on altitude, latitude, and season.
- SAF combustion NOₓ characteristics can differ slightly from Jet A due to fuel composition,
  potentially affecting the NOₓ/climate trade-off.

### 8.3 Particulate Matter and Soot
- SAF combustion generally produces fewer non-volatile particulate matter (nvPM) emissions
  than conventional jet fuel, reducing soot-induced contrail nucleation.
- Reduced soot may also have direct local air quality and health benefits near airports.

### 8.4 Integrated Climate Metrics
- Standard CO₂-equivalent metrics (GWP100) do not fully capture short-lived climate forcers
  (SLCFs) from aviation.
- The scientific community is developing Effective Radiative Forcing (ERF) and Global Warming
  Potential (GWP*) metrics for a more complete assessment of SAF climate benefits beyond CO₂.

---

## 9. Future Outlook and R&D Priorities

### 9.1 Enabling 100% SAF Operation
- Priority: develop aromatic or cycloalkane-containing SAF pathways (FT-SKA, CHJ, ATJ-SKA)
  to meet minimum aromatic specifications without fossil blending.
- Alternatively, qualify new synthetic aromatic compounds as seal-swell additives.

### 9.2 Advanced Feedstock Development
- Scale up cellulosic biomass conversion (gasification, pyrolysis, enzymatic routes).
- Develop algae cultivation at commercially viable costs.
- Accelerate DAC + green hydrogen pathways with declining renewable electricity prices.

### 9.3 Process Efficiency Improvements
- Improve gasification and FT reactor carbon efficiency.
- Optimize ATJ process yield and reduce purification energy requirements.
- Develop integrated biorefineries that co-produce SAF with other high-value chemicals.

### 9.4 Harmonized Global Standards
- Establish a single, internationally recognized LCA methodology for SAF GHG accounting.
- Harmonize book-and-claim registries to enable global SAF certificate trading.
- Streamline multi-jurisdiction sustainability certifications for feedstock and finished fuel.

### 9.5 Cost Reduction Pathway
- Target: achieve cost parity with conventional jet fuel in the mid-2030s through:
  - Scaling (>10 Mt/yr global production by 2030).
  - Technology learning curves (especially PtL and gasification + FT).
  - Carbon pricing that internalizes the cost of fossil fuel emissions.
  - Blended finance instruments (guarantees, concessional loans) to de-risk first plants.

### 9.6 Infrastructure Build-Out
- Develop dedicated SAF production clusters near airports or connected via pipelines.
- Standardize blending, quality control, and traceability protocols across fuel supply chains.
- Expand airport segregated SAF tankage and hydrant connections at major hubs.

---

## 10. References

| # | Source | URL |
|---|--------|-----|
| 1 | ASTM D7566, *Standard Specification for Aviation Turbine Fuel Containing Synthesized Hydrocarbons*, ASTM International | https://www.astm.org/d7566-23.html |
| 2 | ICAO, *SAF Conversion Processes*, ICAO Environment | https://www.icao.int/SAF/saf-conversion-processes |
| 3 | IATA, *SAF Technical Certifications*, 2024 | https://www.iata.org/contentassets/d13875e9ed784f75bac90f000760e998/saf-technical-certifications.pdf |
| 4 | EASA, *First Annual ReFuelEU Aviation Technical Report*, 2024 | https://www.easa.europa.eu/en/newsroom-and-events/press-releases/easa-publishes-report-sustainable-aviation-fuel-scale-progress |
| 5 | NREL, *Sustainable Aviation Fuel (SAF) State-of-Industry Report*, 2024 | https://docs.nrel.gov/docs/fy24osti/87802.pdf |
| 6 | IATA, *Disappointingly Slow Growth in SAF Production*, December 2024 | https://www.iata.org/en/pressroom/2024-releases/2024-12-10-03/ |
| 7 | ICCT, *Industry Perspectives on Advanced Sustainable Aviation Fuel*, 2025 | https://theicct.org/publication/saf-what-barriers-remain-for-these-technologies-to-scale-jul25/ |
| 8 | WEF, *Scaling Up Sustainable Aviation Fuel Supply*, 2024 | https://www3.weforum.org/docs/WEF_Scaling_Sustainable_Aviation_Fuel_Supply_2024.pdf |
| 9 | ISCC, *Flying on Certified SAF: Challenges and Developments from the Airlines Perspectives*, 2024 | https://www.iscc-system.org/wp-content/uploads/2024/09/Flying-on-Certified-SAF-Challenges-and-Developments-from-the-Global-Airlines-Perspectives_12092024_ISCCSAFTC.pdf |
| 10 | US DOE/AFDC, *Sustainable Aviation Fuel*, Alternative Fuels Data Center | https://afdc.energy.gov/fuels/sustainable-aviation-fuel |

---

*Last updated: March 2026*
