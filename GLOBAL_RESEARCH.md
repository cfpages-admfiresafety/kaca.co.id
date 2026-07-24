# Global Research — kaca.co.id

Status: **pilot evidence foundation, ready for outline drafting with the gates below**

Last verified: **2026-07-25 (Asia/Jakarta)**

Catalog covered: **16 topic families / 128 planned articles** in [`ARTICLE_CATALOG.md`](ARTICLE_CATALOG.md)

Authority boundary: [`TOPICAL_AUTHORITY.md`](TOPICAL_AUTHORITY.md)

## Purpose

This file is the shared research layer for the complete kaca.co.id article catalog. It collects reusable ground truth once, maps it to every topic family, and prevents separate writers from repeatedly researching the same definitions, standards, risks, and evidence boundaries.

This is not an article, a substitute for a licensed standard, an engineering calculation, or permission to make a safety-critical claim. Article writers must cite the original source links, not this file.

## How writers must use this file

1. Start with the coverage row for the relevant `GLA-xx` family.
2. Open the cited primary source before using a technical or legal claim.
3. Treat a catalog or abstract as proof of a document's identity, status, and scope only. Obtain the full standard before quoting requirements, test values, tolerances, classifications, or pass/fail criteria.
4. Distinguish glass-product performance from whole-system performance. Frames, seals, hardware, support, installation, and interfaces can change the result.
5. Distinguish Indonesian requirements from foreign reference methods. A US or international source is not automatically Indonesian law.
6. Use conditional language where the answer depends on dimensions, support, load, exposure, substrate, tested assembly, or manufacturer instructions.
7. Preserve every stop condition and professional-review gate in the eventual outline and writing brief.
8. Recheck all standards, laws, product data, and links when an outline is drafted more than six months after the verification date above.

## Evidence scale

| Grade | Meaning | Permitted use |
| --- | --- | --- |
| A | Current Indonesian law, official Indonesian standards catalog, or public primary-source document | Establish document status, jurisdiction, defined scope, and publicly visible facts |
| B | Current official ISO/standards-body abstract or official public test-method scope | Establish terminology and the existence/scope of a method; full text is required for exact requirements |
| C | Government technical guidance or recognized industry guidance | Explain concepts and operating practices with attribution and stated limits |
| D | Manufacturer technical guidance | Explain product- or system-specific practice; never generalize beyond the stated product/system without corroboration |
| Gate | Evidence is incomplete, paid, project-specific, or requires professional judgment/testing | Do not publish a definitive number, selection, compliance claim, or procedure until resolved |

## Reusable article-shape mapping

Every topic family uses the same eight intent shapes. Research should be reused by intent as well as by subject.

| Article suffix | Intended use of the research |
| --- | --- |
| `-01` foundation | Definitions, system boundaries, mechanisms, and terms that are commonly confused |
| `-02` selection | Decision inputs, trade-offs, failure consequences, and questions to ask |
| `-03` specification | Required inputs, units, evidence documents, verified standards, assumptions, and approval gates |
| `-04` design | Interfaces, load paths, support, movement, drainage, compatibility, access, and maintainability |
| `-05` execution | Sequencing, protection, safe access, hold points, QC records, and stop conditions |
| `-06` diagnosis | Observable symptoms, possible causes, safe checks, escalation thresholds, and evidence still needed |
| `-07` maintenance | Cleaning/inspection method, exposure-specific frequency logic, warning signs, and records |
| `-08` procurement | Comparable scope, submittals, samples, test evidence, exclusions, warranties, and handover records |

## Research register

### KR-01 — Project corpus and article boundary

- **Sources:** [`TOPICAL_AUTHORITY.md`](TOPICAL_AUTHORITY.md), [`ARTICLE_CATALOG.md`](ARTICLE_CATALOG.md), [`sitemap-complete.xml`](sitemap-complete.xml)
- **Grade:** A for project scope; not independent technical evidence.
- **Purpose:** Keep the research aligned to the role assigned to kaca.co.id and prevent new research from silently changing article ownership.
- **Summary:** The project is an Indonesian reference and decision-support hub for architectural and functional flat glass. Its catalog deliberately spans product fundamentals, safety, performance, fabrication, systems, applications, procurement, installation, defects, maintenance, and specialist glazing.
- **Grounded facts:** The catalog contains 16 parent topics and 128 planned briefs. Each family has eight distinct intent shapes. Existing pages are evidence/migration candidates, not automatically authoritative sources.
- **Incorporation:** Use the family IDs and suffix mapping in this file to build outlines. Do not add city pages, invented commercial claims, or a second article for an intent already owned by the catalog.
- **Limits/recheck:** Repository content describes editorial intent, not real-world compliance or product performance.

### KR-02 — Indonesian building-governance baseline

- **Sources:** [PP No. 16 Tahun 2021 — BPK](https://peraturan.bpk.go.id/Details/161846/pp-no-16-tahun-2021), [official PUPR JDIH record](https://jdih.pu.go.id/detail-dokumen/PP-nomor-16-Tahun-2021-tahun-2021-Peraturan-Pelaksanaan-Undang-Undang-Nomor-28-Tahun-2002-Tentang-Bangunan-Gedung)
- **Grade:** A.
- **Purpose:** Anchor Indonesian building articles in the current national building-governance framework.
- **Summary:** PP 16/2021 is the implementing regulation for the Building Law framework. It governs building implementation at a high level and relies on further regulations, national standards, and regional rules for detailed execution.
- **Grounded facts:** The regulation took effect on 2 February 2021 and replaced PP 36/2005. A project can therefore require national rules, SNI/technical standards, and location-specific regulations together.
- **Incorporation:** In `GLA-04`, `07`, `10`, `11`, `12`, and `13`, explain that a glass detail cannot be declared compliant from product type alone. The applicable building function, project approvals, technical standards, and local rules must be checked.
- **Limits/recheck:** Do not convert this high-level regulation into glass thicknesses, safety locations, or test pressures. Those need the applicable detailed rule and project design.

### KR-03 — Accessibility and ease of building use

- **Source:** [Permen PUPR No. 14/PRT/M/2017 — BPK](https://peraturan.bpk.go.id/Details/104477/permen-pupr-no-14prtm2017-tahun-2017)
- **Grade:** A.
- **Purpose:** Prevent doors, partitions, openings, manifestations, circulation, and hardware articles from treating glass as an isolated material.
- **Summary:** The regulation establishes ease-of-use requirements for buildings and remains listed as in force.
- **Grounded facts:** Accessibility and circulation requirements belong to the building system and can affect opening dimensions, operation, visibility, approach, and safe use.
- **Incorporation:** Use as a legal-context prompt in `GLA-07`, `08`, `09`, `11`, and `13`: the outline must ask about users, circulation, visibility/manifestation, operation, reach, and local approval. It must not invent dimensions from memory.
- **Limits/recheck:** Open the full regulation and current local rules before stating a dimension or prescriptive requirement.

### KR-04 — Work at height and the 2026 amendment

- **Sources:** [Permenaker No. 9 Tahun 2016 — official Kemnaker JDIH](https://jdih.kemnaker.go.id/peraturan/detail/1210/peraturan-menteri-nomor-9-tahun-2016), [Permenaker No. 11 Tahun 2026 status and amendment record — BPK](https://peraturan.bpk.go.id/Search?jenis=105&p=1)
- **Grade:** A.
- **Purpose:** Ground installation, façade access, cleaning, inspection, and replacement articles in current Indonesian worker-safety context.
- **Summary:** Permenaker 9/2016 remains in force for work at height, but Permenaker 11/2026, effective 3 July 2026, partially removed or changed provisions including Article 1 point 14 and Article 29(3).
- **Grounded facts:** A writer must not rely on an old copy of the 2016 rule alone. Work-at-height content needs a current consolidated legal check, competent planning, safe access, and task-specific controls.
- **Incorporation:** `GLA-10`, `11`, `13`, `14`, and `15` must include a stop condition: no improvised access and no procedural DIY guidance for elevated glazing. Outlines should request the current work-at-height plan, competent personnel, rescue provisions, and site controls.
- **Limits/recheck:** This research does not interpret the amended clauses or create a method statement. Legal/HSE review is required before prescriptive publication.

### KR-05 — Base flat glass and current Indonesian product references

- **Sources:** [SNI 47:2018 Konfirmasi 2026 — BSN](https://pesta.bsn.go.id/produk/detail/4720182026-sni47%3A2018konfirmasi2026), [SNI 6353:2024 listing — BSN](https://pesta.bsn.go.id/produk/by_ics/4?ics_no=81&key=), [ISO 16293-2:2025 official abstract](https://www.iso.org/standard/85237.html)
- **Grade:** A for BSN status/scope; B for ISO abstract.
- **Purpose:** Establish current terminology and quality-reference starting points for ordinary float/flat and heat-strengthened glass.
- **Summary:** BSN lists SNI 47:2018, reconfirmed in April 2026, as the in-force flat-glass standard and SNI 6353:2024 as the in-force heat-strengthened-glass standard. ISO 16293-2:2025 addresses dimensional and minimum optical/visual quality requirements for building float glass.
- **Grounded facts:** “Flat glass,” “heat-strengthened glass,” and “fully tempered safety glass” are not interchangeable labels. A base-glass quality standard does not by itself prove safety suitability, structural adequacy, or whole-system performance.
- **Incorporation:** Primary foundation for `GLA-01`, `04`, and `05`; supporting evidence for all specification/procurement articles. Request the declared product, processing, applicable standard, dimensions, edgework, markings, and traceability rather than using a generic “kaca X mm” description.
- **Limits/recheck:** Full standards are required for tolerances, defect limits, tests, and acceptance criteria.

### KR-06 — Indonesian tempered and laminated safety glass

- **Sources:** [SNI 9144-1:2022 laminated safety glass — BSN](https://pesta.bsn.go.id/produk/detail/14416-sni9144-12022), [SNI 9144-2:2022 tempered safety glass — BSN](https://pesta.bsn.go.id/produk/detail/14417-sni9144-22022), [SNI ISO 12540:2017 listing — BSN](https://pesta.bsn.go.id/produk/index/530)
- **Grade:** A for catalog status and scope.
- **Purpose:** Keep safety-glass decisions tied to verified Indonesian product references.
- **Summary:** BSN lists separate in-force references for laminated safety glass and tempered safety glass for buildings/panels. The separation matters because breakage behavior and post-breakage retention are different design questions.
- **Grounded facts:** A product being stronger before breakage is not the same as retaining fragments or carrying load after breakage. “Safety glass” suitability depends on the application and the complete tested/design context.
- **Incorporation:** Core evidence for all `GLA-02-*`; required cross-reference in `GLA-07`, `08`, `09`, `10`, `11`, and `16`. Selection and specification outlines must separately ask about human impact, fallout/fall-through, retention, support, edges/holes, and evidence of conformity.
- **Limits/recheck:** Do not publish impact classes, fragmentation counts, minimum thicknesses, or application mandates from the catalog page. Obtain the standards and the applicable building rule.

### KR-07 — Laminated-glass vocabulary, performance, and durability

- **Sources:** [SNI ISO 12543-1:2011 — BSN](https://pesta.bsn.go.id/produk/detail/8964-sniiso12543-12011), [SNI ISO 12543-2:2011 — BSN](https://pesta.bsn.go.id/produk/detail/8965-sniiso12543-22011), [SNI ISO 12543-3:2011 — BSN](https://pesta.bsn.go.id/produk/detail/8966-sniiso12543-32011), [ISO 12543-1:2021 official abstract](https://www.iso.org/standard/72871.html)
- **Grade:** A for Indonesian catalog status; B for current international vocabulary.
- **Purpose:** Prevent articles from reducing laminated glass to “two panes with plastic” or assuming every laminate has the same safety/security/post-breakage performance.
- **Summary:** The standards family separates vocabulary/component description, laminated safety glass, laminated glass, and durability testing. The international vocabulary edition has advanced to 2021 while BSN still lists the 2011 adoptions as in force.
- **Grounded facts:** Ply makeup, glass treatment, interlayer type/thickness, edge exposure, support, temperature, load duration, and intended threat/performance all matter. “Laminated” alone is not a performance class.
- **Incorporation:** `GLA-02`, `05`, `10`, `14`, and `16` must record the complete makeup and requested performance, not only total thickness. Procurement articles should request product identity, test/certification evidence, fabrication records, edge condition, and application-specific approval.
- **Limits/recheck:** Do not silently substitute the newer ISO edition for the Indonesian SNI. State which document governs a project and obtain full text for requirements.

### KR-08 — Mirrors, coatings, color, and visual-quality evidence

- **Sources:** [SNI 4756:2021 aluminium-coated sheet mirror — BSN](https://pesta.bsn.go.id/produk/detail/13726-47562021), [SNI ISO 25537:2011 silver-coated mirror — BSN](https://pesta.bsn.go.id/produk/detail/8784-sniiso255372011), [SNI 9237:2023 coated glass — BSN](https://pesta.bsn.go.id/produk/detail/14858-sni92372023), [SNI ISO 11479-1:2014 physical defects — BSN](https://pesta.bsn.go.id/produk/detail/10042-sniiso11479-12014)
- **Grade:** A for catalog status/scope.
- **Purpose:** Ground mirror, coated-glass, façade color, inspection, defect, and procurement content.
- **Summary:** BSN maintains distinct references for aluminium-backed mirrors, silver-backed mirrors, coated building glass, and coating physical defects. Product identity and viewing/acceptance conditions therefore matter.
- **Grounded facts:** A generic “mirror” or “coated glass” label omits backing/coating system, exposed surface, edge protection, visual criteria, and compatibility concerns. Aesthetic acceptance and functional performance are separate.
- **Incorporation:** Core for `GLA-03`, `05`, `09`, `11`, `14`, and `16`. Require samples/mockups where appearance matters, record coating surface/orientation, avoid universal defect claims, and separate visual review from safety/structural review.
- **Limits/recheck:** Full standards and manufacturer documents are required for viewing conditions, defect limits, processing restrictions, and cleaning compatibility.

### KR-09 — Insulating glass units and Indonesian mandatory SNI context

- **Sources:** [Permenperin No. 12 Tahun 2024 — BPK](https://peraturan.bpk.go.id/Details/294700), [SNI ISO 20492-1:2014 edge-seal climate durability — BSN](https://pesta.bsn.go.id/produk/detail/10045-sniiso20492-12014), [SNI ISO 20492-2:2014 fogging test — BSN](https://pesta.bsn.go.id/produk/detail/20492220142020-sniiso20492-2%3A2014konfirmasi2020), [BSN listing for Parts 1–4](https://pesta.bsn.go.id/produk/by_ics/2?ics_no=81&key=)
- **Grade:** A.
- **Purpose:** Ground double/insulating-glass, internal fogging, gas, edge seal, procurement, and replacement articles in Indonesian requirements.
- **Summary:** Permenperin 12/2024 made SNI for insulating glass mandatory from 10 December 2024. BSN's ISO 20492 series covers edge-seal climate durability, chemical fogging, gas concentration/leakage, and physical properties of edge seals.
- **Grounded facts:** An insulating glass unit is a fabricated sealed product, not simply two independent panes. Internal fogging, gas retention, seal durability, edge construction, glazing compatibility, and structural-glazing suitability are distinct issues.
- **Incorporation:** Central to `GLA-03`, `06`, `11`, and `14`; supporting `GLA-12` and `13`. Articles should request the unit makeup, declared SNI/conformity evidence, spacer/seal system, coating positions, gas declaration if any, manufacturing date/traceability, glazing constraints, and warranty terms.
- **Limits/recheck:** Verify the regulation's exact product scope, exceptions, certification route, and transition provisions from the full text before stating that a particular unit must bear a specific mark.

### KR-10 — Optical, solar, thermal, and acoustic performance

- **Sources:** [ISO 9050:2003 official abstract](https://www.iso.org/standard/35062.html), [ISO 10292:2026 official abstract](https://www.iso.org/standard/89851.html), [ISO 22897:2023 official abstract](https://www.iso.org/standard/84945.html)
- **Grade:** B.
- **Purpose:** Define the correct measurement domains for light/solar properties, center-of-glass thermal transmittance, and airborne sound insulation.
- **Summary:** ISO 9050 provides methods for optical/solar properties. ISO 10292:2026, published in July 2026, calculates center-of-glazing U-value and explicitly excludes spacer/frame edge effects and solar transfer. ISO 22897 addresses glass-product acoustic performance and warns that frames, mounting, and air tightness can change complete-window performance.
- **Grounded facts:** Center-of-glass values are not whole-window values. Light transmission, solar heat gain, U-value, privacy, and acoustic insulation are different metrics. A pane result cannot automatically be claimed for an installed partition/window/façade.
- **Incorporation:** Core for all `GLA-03-*`, plus `GLA-07`, `08`, and `11`. Every performance claim should name the metric, unit, test/calculation method, exact makeup, whether it is center-of-glass or whole product, and the evidence source.
- **Limits/recheck:** ISO 9050 was current but under revision at verification. Recheck its edition before outline approval. Full standards/test reports are required for numbers.

### KR-11 — Energy-rating concepts and hot-climate decision logic

- **Sources:** [NFRC rating definitions](https://nfrc.org/), [US Department of Energy purchasing guidance](https://www.energy.gov/cmei/femp/purchasing-energy-efficient-residential-windows-doors-and-skylights), [Berkeley Lab WINDOW capabilities](https://windows.lbl.gov/window-software-downloads)
- **Grade:** C; US-context, not Indonesian compliance.
- **Purpose:** Give writers a clear conceptual vocabulary for U-factor, solar heat gain coefficient, visible transmittance, air leakage, and condensation without turning it into an Indonesian product endorsement.
- **Summary:** NFRC separates whole-product energy metrics. DOE guidance explains that warm-climate decisions usually prioritize limiting unwanted solar gain while considering daylight, insulation, frames, coatings, panes, gas fills, and leakage. Berkeley Lab tools distinguish center-of-glass and whole-system calculations.
- **Grounded facts:** Lower U-factor means less heat flow under the stated rating method; lower SHGC means less admitted solar heat; higher visible transmittance means more visible light. These values are not interchangeable, and the best combination depends on climate, orientation, shading, space use, and whole-system design.
- **Incorporation:** Use for explanatory diagrams and decision inputs in `GLA-03-01/02/03` and `GLA-07/11`. Indonesian articles must say these are concepts/reference methods and must seek locally applicable project criteria and verified product reports.
- **Limits/recheck:** Do not import US climate-zone thresholds, label ranges, or ENERGY STAR purchasing rules as Indonesian requirements.

### KR-12 — Glass sizing, support, load, and excluded applications

- **Sources:** [ASTM E1300-24 official scope page](https://store.astm.org/e1300-24.html), [ASTM glass-use committee current standards list](https://www.astm.org/membership-participation/technical-committees/committee-e06/subcommittee-e06/jurisdiction-e0652)
- **Grade:** B for public scope; Gate for calculations.
- **Purpose:** Stop writers from presenting thickness tables or rules of thumb as structural design.
- **Summary:** ASTM E1300 is a load-resistance method with defined glass types, support conditions, load types, and exclusions. The current scope excludes or separately treats applications such as balustrades, floors, aquariums, structural members, shelves, patterned/surface-treated glass, and other specialist conditions.
- **Grounded facts:** Thickness selection depends on dimensions, aspect ratio, edge support, glass type, load magnitude/duration, edge condition, holes/notches, deflection, probability basis, post-breakage consequences, and system behavior. One thickness is not universally safe for one application label.
- **Incorporation:** Core gate for `GLA-04`; mandatory warning in `GLA-09`, `10`, `11`, and `16`. `-03` outlines must gather inputs and route calculations to a qualified designer rather than include a universal lookup table.
- **Limits/recheck:** No calculation, chart, coefficient, or acceptance number may be reproduced from an abstract. Use a licensed current standard and qualified engineer.

### KR-13 — Fabrication sequence and product-specific processing

- **Sources:** [ASTM C1036-25 official scope](https://store.astm.org/c1036-25.html), [ASTM C1048-25 official scope](https://store.astm.org/c1048-25.html), [ASTM C1172-24e1 official record](https://store.astm.org/c1172-24e01.html), [NGA heat-treated glass guidance](https://www.glass.org/sites/default/files/2023-10/FB02-02_2023_Heat-Treated_Glass_Surfaces_Different.pdf)
- **Grade:** B for standards scope; C for industry guidance.
- **Purpose:** Establish safe, non-numeric fabrication facts and the need for fabrication-before-heat-treatment planning.
- **Summary:** Current standards distinguish base flat glass, heat-strengthened/fully tempered glass, and laminated architectural glass. Heat-treated-glass guidance explains that cutting, edging, holes, notches, and other fabrication are planned before heat treatment and that heat treatment changes break/strength behavior while introducing surface/optical considerations.
- **Grounded facts:** A late hole, cutout, or size change can require remanufacture rather than field modification. Processing history, edgework, cleanliness, roller-wave/anisotropy expectations, bow/warp, marking, and traceability belong in the fabrication brief.
- **Incorporation:** Core for all `GLA-05-*`; supporting `GLA-02`, `04`, `12`, and `14`. Use a process-flow diagram and hold points, not machinery operating instructions.
- **Limits/recheck:** Exact processing limits and acceptance criteria are product/fabricator/standard specific. The ASTM public pages are not substitutes for licensed documents.

### KR-14 — Sealants, gaskets, blocks, compatibility, and structural silicone

- **Sources:** [Dow Asia Structural Sealant Glazing Manual](https://www.dow.com/documents/63/63-6132-01-structural-sealant-glazing-manual-asia.pdf), [ASTM C24 current sealant standards list](https://www.astm.org/membership-participation/technical-committees/committee-c24/subcommittee-c24/jurisdiction-c2410), [ASTM C24 adhesion standards list](https://www.astm.org/membership-participation/technical-committees/committee-c24/subcommittee-c24/jurisdiction-c2430)
- **Grade:** D for Dow product-system guidance; B for standards identity/scope.
- **Purpose:** Prevent “use silicone” from replacing joint design, compatibility, adhesion, cure, movement, and QC.
- **Summary:** Dow's Asia manual calls for project-specific structural joint review, substrate adhesion testing, and compatibility testing of contacting accessories such as spacers, gaskets, and setting blocks. ASTM maintains distinct specifications/guides for structural silicone, joint sealants, joint design, insulating-glass secondary seals, and installed adhesion evaluation.
- **Grounded facts:** Sealant product name alone does not prove suitability. Substrate finish, cleaning/primer, joint geometry, movement, bite, cure conditions, contact materials, drainage, workmanship, and documented adhesion/QC are separate controls.
- **Incorporation:** Core for `GLA-06` and `11`; supporting `GLA-07`, `09`, `13`, and `14`. Include a compatibility/adhesion evidence register and field-QC hold points in outlines.
- **Limits/recheck:** Never transfer Dow's product-specific dimensions or warranty process to another manufacturer. Structural silicone design requires the selected manufacturer's written project review and qualified design responsibility.

### KR-15 — Façade, window, and insulating-unit performance testing

- **Sources:** [ASTM E331-00(2023) official scope](https://store.astm.org/standards/e331), [ASTM E2190-19 official scope](https://store.astm.org/standards/e2190), [ASTM E06.51 current window/façade standards list](https://www.astm.org/membership-participation/technical-committees/committee-e06/subcommittee-e06/jurisdiction-e0651)
- **Grade:** B for public scope; Gate for project test criteria.
- **Purpose:** Separate material claims from manufactured-assembly and installed-system verification.
- **Summary:** ASTM E331 addresses water penetration of exterior windows, curtain walls, skylights, and doors under a specified static pressure difference. ASTM E2190 evaluates insulating-glass durability through defined specimen testing. Neither proves every aspect of installed façade performance.
- **Grounded facts:** Test pressure, specimen size/configuration, laboratory versus field setup, interfaces, drainage, supporting construction, installation, aging, and failure definition must be stated. Passing one test does not prove unrelated performance.
- **Incorporation:** Core for `GLA-07`, `11`, and `13`; supporting `GLA-03` and `14`. Specify the question a test answers, the assembly tested, acceptance authority, witness/report, and unresolved interfaces.
- **Limits/recheck:** Project specifications and local requirements control test selection and pressure. Do not invent a “standard” pressure.

### KR-16 — Cleaning, construction protection, and coated/heat-treated surfaces

- **Sources:** [NGA Proper Procedures for Cleaning Architectural Glass Products (2023)](https://www.glass.org/sites/default/files/2023-12/FB01-00_2023_Proper_Procedures_Cleaning_Architectural_Glass_Products.pdf), [NGA Heat-Treated Glass Surfaces Are Different (2023)](https://www.glass.org/sites/default/files/2023-10/FB02-02_2023_Heat-Treated_Glass_Surfaces_Different.pdf), [NGA glass technical resources](https://www.glass.org/architect)
- **Grade:** C.
- **Purpose:** Ground maintenance and defect-prevention content without universal chemical recipes.
- **Summary:** NGA advises identifying the glass/coating before cleaning, using non-abrasive methods, protecting glass during construction, treating blades/scrapers as a high-risk last resort, and following the fabricator/manufacturer's specific instructions. Heat-treated and exposed coated surfaces need additional care.
- **Grounded facts:** Incorrect cleaning can permanently scratch, stain, remove/damage a coating, or harm laminated edges. Cleaning frequency should respond to site exposure rather than a universal calendar.
- **Incorporation:** Core for `GLA-14` and `15`; supporting `GLA-03`, `05`, `09`, and `13`. Outlines should include glass identification, a small-area test, compatible materials, construction contaminants, access controls, stop conditions, and maintenance records.
- **Limits/recheck:** Do not publish a chemical as universally safe. Confirm the exact glass, coating, film, interlayer edge, sealants, hardware, and manufacturer instructions.

### KR-17 — Spontaneous breakage, heat soak, and diagnosis boundaries

- **Source:** [NGA Heat Soaking Testing of Tempered Glass](https://members.glass.org/cvweb/cgi-bin/msascartdll.dll/ProductInfo?productcd=HEATSOAKING)
- **Grade:** C.
- **Purpose:** Give tempered-glass breakage articles a defensible distinction between risk reduction, diagnosis, and guarantees.
- **Summary:** NGA states that fully tempered glass can break spontaneously for multiple reasons; nickel-sulfide inclusions are one possible cause. Heat-soak testing is intended to reduce, not eliminate, the risk by encouraging susceptible panes to break during testing.
- **Grounded facts:** A broken pane cannot be confidently diagnosed as nickel-sulfide inclusion from a casual photo or from “spontaneous” timing alone. Heat soaking does not create a zero-breakage guarantee.
- **Incorporation:** `GLA-02-06`, `GLA-05-06`, and all `GLA-14-*` diagnosis/decision content. Preserve evidence, isolate the hazard, document fracture origin/edges/support/context if safe, and use qualified investigation.
- **Limits/recheck:** Do not state a universal incidence rate or claim certainty without laboratory/forensic evidence and the relevant fabrication/testing records.

### KR-18 — Railings, walk-on glass, skylights, and overhead glazing

- **Sources:** [ASTM E06.56 current railing/floor standards list](https://www.astm.org/membership-participation/technical-committees/committee-e06/subcommittee-e06/jurisdiction-e0656), [NGA Skylights and Sloped Glazing Are Not Walking Surfaces](https://www.glass.org/sites/default/files/2023-03/FB10-06_2023_Skylights_and_Sloped_Glazing_are_Not_Walking_Surfaces.pdf)
- **Grade:** B for standards identity; C for industry safety guidance.
- **Purpose:** Create a strong safety boundary around `GLA-10`.
- **Summary:** ASTM maintains separate performance standards for glazing in railings/guards/balustrades and laminated glass walkways. NGA warns that ordinary skylights and sloped glazing are generally not designed as walking surfaces even when they appear strong.
- **Grounded facts:** Barrier, overhead, and walk-on applications have different hazards: fall-through, fallout, post-breakage retention, concentrated/live load, slip, redundancy, edge/support failure, drainage, and safe maintenance access.
- **Incorporation:** Every `GLA-10-*` outline must identify the application class and failure consequence before product selection. Add engineer approval, tested-system evidence, post-breakage behavior, access plan, and inspection/replacement criteria.
- **Limits/recheck:** Do not combine railing, canopy, skylight, roof, and floor glass into one thickness recommendation. Project-specific structural design is mandatory.

### KR-19 — Fire-rated glazing is a listed/tested assembly question

- **Source:** [UL Doors, Windows and Related Hardware Application Guide](https://www.ul.com/thecodeauthority/knowledge/ul-fire-rated-doors-guide)
- **Grade:** C/B for UL certification-category explanation; foreign jurisdiction.
- **Purpose:** Prevent “fireproof glass” language and glass-only fire claims.
- **Summary:** UL distinguishes fire-resistance-rated glazing used as part of a tested wall assembly from fire-protection-rated glazing used in opening protectives. Ratings and permitted configurations belong to the certified assembly, including framing, dimensions, installation, and marking.
- **Grounded facts:** Fire resistance, fire protection, temperature-rise performance, hose-stream performance, impact safety, and door/window assembly use are separate claims. One label does not prove all of them.
- **Incorporation:** `GLA-08`, `11`, and all `GLA-16-*`. Outlines must request the applicable Indonesian fire/building requirement, complete tested/listed assembly, rating/classification, maximum sizes, frame and fixing details, safety-glazing evidence, and current certification.
- **Limits/recheck:** UL is not Indonesian law. Do not recommend an assembly until the Indonesian approval basis and exact current listing/test evidence are verified.

### KR-20 — Ballistic, forced-entry, blast, and ordinary safety glass are different

- **Sources:** [UL explanation of UL 752 bullet-resisting equipment](https://www.ul.com/news/what-does-it-take-stop-speeding-bullet), [NIJ active standards list](https://nij.ojp.gov/topics/equipment-and-technology/active-nij-standards-and-comparative-test-methods), [ISO glass-in-building standards catalog](https://www.iso.org/ics/81.040.20/x/)
- **Grade:** B/C; foreign/international reference context.
- **Purpose:** Prevent “anti peluru,” “security,” “blast resistant,” and “safety laminated” from being used as synonyms.
- **Summary:** UL 752 classifies tested bullet-resisting equipment/assemblies against defined threats. NIJ separately defines ballistic protective-material and threat standards. ISO lists separate standards for forced-entry and explosion-resistant security glazing.
- **Grounded facts:** Security performance is threat-, test-, construction-, size-, support-, framing-, and edition-specific. Ordinary tempered or laminated safety glass is not automatically bullet-, blast-, or forced-entry-resistant.
- **Incorporation:** All `GLA-16-*`, especially selection/specification/procurement. Require a defined threat model, governing standard edition/classification, tested size and assembly, multi-hit/edge/frame assumptions where applicable, current report/listing, and specialist review.
- **Limits/recheck:** Never use “bulletproof.” Do not publish threat equivalencies or construction recipes from summaries.

### KR-21 — Smart/dynamic and decorative glazing

- **Sources:** [ISO 18543:2021 electrochromic glazing](https://www.iso.org/standard/75536.html), [NGA Dynamic Glazing for High Performance Buildings](https://www.glass.org/sites/default/files/2021-07/FB32-11_2018_Dynamic_Glazing_for_High_Performance_Buildings_0521.pdf), [NGA Decorative Glass handling/cleaning record (2025)](https://members.glass.org/cvweb/cgi-bin/msascartdll.dll/ProductInfo?productcd=HANDLINGANDCLEAN), [NGA decorative durability guidance](https://www.glass.org/sites/default/files/2022-09/FB44-14_2019_Assessing_Durability_of_Decorative_Glass_0521.pdf)
- **Grade:** B for ISO scope; C for industry guidance.
- **Purpose:** Distinguish privacy switching, solar/visible modulation, decorative appearance, and durability.
- **Summary:** ISO 18543 addresses accelerated ageing of electrically switched electrochromic glazing. NGA distinguishes dynamic technologies and notes that privacy-oriented PDLC behavior is not the same as solar/energy modulation. Decorative products need exposure- and process-specific handling, cleaning, and durability evidence.
- **Grounded facts:** “Smart glass” is not one mechanism. Power-off state, switching method, optical state range, controls, wiring, heat, edge seals, UV/moisture exposure, cycle/ageing evidence, replacement, and cleaning can all matter.
- **Incorporation:** Core for `GLA-16`; supporting `GLA-03`, `08`, `09`, and `15`. Require a technology-specific functional brief, sample/mockup, power/control/fail-state definition, verified performance reports, environmental durability, maintenance, and warranty.
- **Limits/recheck:** Manufacturer claims are product-specific. Do not infer energy savings, sound/privacy performance, service life, or safety class from the technology name.

### KR-22 — Procurement, glazing practice, handover, and traceability

- **Source:** [NGA/GANA Glazing Manual, IYOG edition](https://www.glass.org/sites/default/files/2023-01/GANA_Glazing_Manual_2022_pw.pdf)
- **Grade:** C.
- **Purpose:** Turn research into auditable RFQ, submittal, installation, inspection, and handover inputs rather than descriptive prose only.
- **Summary:** The manual covers practical glazing considerations across receiving, storage, handling, edge condition, setting, labels, post-glazing protection, cleaning, and application-specific cautions.
- **Grounded facts:** Durable quality depends on preserving product identity and condition from fabrication through handover. Labels, delivery inspection, storage orientation/support, edge protection, setting materials, cleaning, photographs, nonconformance records, test reports, and as-built information are evidence.
- **Incorporation:** Core for all `GLA-12-*` and `GLA-13-*`; reusable in every `-05` and `-08` article. Build checklists that compare evidence and scope, not unsupported vendor rankings.
- **Limits/recheck:** It is an industry manual, not a project specification or Indonesian law. Manufacturer instructions and project documents take precedence where more specific.

## Topic-family coverage matrix

| Topic family | Main evidence records | What the eventual eight-article set must be grounded in | Remaining gate before definitive drafting |
| --- | --- | --- | --- |
| `GLA-01` fundamentals | KR-05, KR-10, KR-13 | Product taxonomy; difference between material, processed product, and installed system; basic optical/thermal/load concepts | Licensed standards for any numeric tolerance or acceptance criterion |
| `GLA-02` tempered/laminated/heat-strengthened safety | KR-06, KR-07, KR-13, KR-17 | Distinct breakage and retention behavior; fabrication sequence; safety evidence; heat-soak limits | Full applicable SNI, application rule, and expert review |
| `GLA-03` thermal/solar/light/privacy/acoustic | KR-08, KR-09, KR-10, KR-11, KR-21 | Separate metrics and test methods; center-of-glass versus whole system; climate/orientation inputs | Verified product/system reports and locally applicable project criteria |
| `GLA-04` specification/size/load/tolerance | KR-02, KR-05, KR-12, KR-13 | Complete design inputs, support/load boundaries, fabrication effects, no universal thickness table | Qualified engineer and licensed calculation standard |
| `GLA-05` fabrication | KR-05, KR-07, KR-08, KR-13 | Process order, edge/hole planning, traceability, product-specific reject evidence | Fabricator capabilities, current standards, and approved shop data |
| `GLA-06` frame/gasket/sealant/fittings | KR-09, KR-14, KR-15, KR-22 | Compatibility, adhesion, movement, drainage, support, corrosion, and QC evidence | Selected system/manufacturer review and project-specific tests |
| `GLA-07` windows/doors/openings | KR-02, KR-03, KR-06, KR-11, KR-15 | User safety/access, operation, air/water/energy as whole-product performance | Applicable local rules, tested assembly, and hardware/use-cycle data |
| `GLA-08` partitions/interiors | KR-03, KR-06, KR-10, KR-19, KR-21 | Human impact, visibility, acoustics as a system, fire boundary, privacy technology | Occupancy/use requirements and complete tested systems |
| `GLA-09` shower/mirror/furniture | KR-06, KR-08, KR-12, KR-14, KR-16 | Wet-area impact, exposed edges, mirror type/backing, hardware/support, cleaning | Application-specific safety rule, hardware data, and design review |
| `GLA-10` railings/canopies/skylights/roofs/floors | KR-04, KR-06, KR-07, KR-12, KR-18 | Failure consequence, post-breakage retention, overhead/fall-through/live-load/access risks | Mandatory structural engineer and applicable system standards/tests |
| `GLA-11` façades/curtain wall/storefront/spider | KR-02, KR-09, KR-12, KR-14, KR-15, KR-19 | Load path, anchors, silicone, movement, air/water, IGU, fire interfaces, testing | Project specification, engineer, manufacturer review, mockup/testing |
| `GLA-12` survey/quotes/procurement/evidence/warranty | KR-02, KR-05–KR-09, KR-22 | Comparable makeup/scope, standards evidence, samples, exclusions, logistics, warranties | Current supplier evidence and a project-specific comparison sheet |
| `GLA-13` installation/QC/handover | KR-04, KR-14, KR-15, KR-16, KR-22 | Safe access, receiving/storage, setting/sealing, protection, hold points, records | Site method statement, ITP, competent personnel, approved materials |
| `GLA-14` defects/fogging/leaks/breakage/replacement | KR-09, KR-14–KR-17, KR-22 | Safe isolation, symptom versus cause, evidence preservation, IGU/seal/edge clues | Site inspection and specialist/forensic review for consequential failures |
| `GLA-15` cleaning/inspection/maintenance in Indonesia | KR-04, KR-14, KR-16, KR-18, KR-22 | Glass/coating identification, compatible method, exposure-based frequency, safe access, records | Exact manufacturer instructions and current HSE/access plan |
| `GLA-16` smart/decorative/privacy/security/fire/specialist | KR-08, KR-19, KR-20, KR-21 | Technology/threat/rating-specific evidence; complete tested assembly; durability and fail state | Specialist review, applicable Indonesian approval basis, current test/listing |

Coverage result: **16/16 topic families mapped; 0 families without a starting evidence set.** This means outline work can begin, but it does not mean every article is cleared for definitive numeric or compliance claims.

## Cross-catalog fact bank

These are reusable propositions supported by the register. Writers should still cite the underlying source.

1. Glass product type, processed makeup, and installed-system performance are three different layers.
2. Tempered, heat-strengthened, and laminated glass solve different pre-breakage and post-breakage questions.
3. “Laminated,” “tempered,” “double,” “smart,” “fire-rated,” and “security” are not complete specifications.
4. Center-of-glass performance cannot automatically be claimed for the complete window, partition, door, or façade.
5. Thickness cannot be selected safely from application name alone.
6. Holes, notches, edges, dimensions, coatings, and decoration must be coordinated before heat treatment where applicable.
7. Sealant suitability requires joint design plus substrate adhesion and material compatibility evidence.
8. Internal IGU fogging and external surface condensation are different symptoms.
9. Cleaning method depends on glass, coating, film, interlayer edge, contaminants, and manufacturer guidance.
10. Heat-soak testing reduces a specific tempered-glass breakage risk; it does not guarantee zero breakage.
11. Skylights and sloped glazing are not walking surfaces unless specifically engineered as such.
12. Fire, ballistic, blast, forced-entry, impact safety, acoustic, privacy, and solar-control claims each need their own evidence.
13. A test result belongs to the tested method, specimen, configuration, conditions, and acceptance basis.
14. Procurement quality improves when evidence, inclusions, exclusions, interfaces, samples, QC, and handover documents are made comparable.
15. Current legal and standards status must be rechecked; changes discovered in 2026 show why old article memory is unsafe.

## Evidence gaps and publication gates

| Gate | Affected families | Resolution required |
| --- | --- | --- |
| `GATE-01` Licensed SNI text | All, especially `02–06`, `09–11` | Obtain/read the applicable current SNI before exact requirements, tolerances, classes, or tests enter an outline |
| `GATE-02` Indonesian application rules | `02`, `07–11`, `16` | Identify applicable national/local building, fire, accessibility, and project rules for the actual application |
| `GATE-03` Structural design | `04`, `09–11`, `16` | Qualified engineer verifies loads, support, makeup, deflection, post-breakage consequences, and interfaces |
| `GATE-04` Product/system reports | `03`, `06–11`, `16` | Obtain current datasheets, test reports, certification/listing, limitations, and exact configuration |
| `GATE-05` Manufacturer compatibility | `06`, `09`, `11`, `13–15` | Written adhesion/compatibility, cleaning, processing, and installation guidance for selected materials |
| `GATE-06` Site facts | `07`, `10–15` | Survey dimensions, exposure, substrate/frame condition, access, drainage, existing defects, and user risk |
| `GATE-07` HSE/legal consolidation | `10`, `11`, `13–15` | Review current Permenaker provisions including the 2026 amendment; approve task-specific safe method |
| `GATE-08` Specialist threat/rating definition | `16` | Define fire/security/ballistic/blast/privacy/smart-glass objective and governing evidence before selection |

## Source-refresh triggers

Recheck a record immediately when any of these occurs:

- BSN confirms, revises, replaces, or withdraws a listed SNI.
- A ministry regulation is amended, partially revoked, or replaced.
- ISO/ASTM/UL publishes a new edition used by the article.
- A manufacturer changes formulation, substrate approval, warranty, or installation guidance.
- An article introduces a number, rating, test class, compliance statement, service-life claim, price, or safety procedure.
- The real project configuration falls outside the public source's stated scope.

## Next authorized stage

The next content stage is to use this research to produce article outlines and detailed lower-model writing instructions. That stage should begin with the 12 P0/Wave 1 briefs, validate one complete outline/writing-instruction package, and only then scale the pattern.

Article drafting, Markdown article creation, HTML hydration, publication dating, sitemap generation, deployment, and Google Search Console submission are intentionally **not performed in this research stage**.
