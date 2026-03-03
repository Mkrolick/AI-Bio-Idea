# Literature Review - Direct Protein Synthesis

## Solid-Phase Peptide Synthesis (SPPS) — Current State
- Practical limit: **30-50 residues** standard; error accumulation is exponential (99% coupling → 36% crude at 100 residues)
- Cost: $2-4.50/residue commercially
- Key problem: chain aggregation (beta-sheet formation on resin)
- Solutions: pseudoprolines, Hmb/Dmb backbone protection, SynTag (Jardine et al., JACS 2024)

## Automated Flow SPPS — Pentelute Lab (MIT)
- **Hartrampf et al. (2020).** *Science* 368:980-987. "Synthesis of proteins by automated flow chemistry."
  - 7 seconds/coupling, ~40 sec total cycle. **164 AA sortase A in 6.5 hours.**
  - 90°C reaction prevents aggregation by minimizing idle time.
- **2024 ACS Central Science**: FKBP51 with intramolecular lactam bridges via flow SPPS.
- **2024 Nature Communications**: 12 D-proteins in single synthesis runs for mirror-image phage display.

## Native Chemical Ligation (NCL) for Full-Length Proteins
- Dawson et al. (1994). *Science* 266:776-779. Foundational NCL paper.
- Requires N-terminal Cys at each junction (limits junction choices).
- Enhanced NCL in TFA (2024, Science Advances): dissolves all peptides, enables membrane proteins.
- Beta-lactone NCL (2024, Org. Lett.): epimerization-free at Thr junctions.
- Record: **271 AA D-Fast-PETase** (Zou et al., Chem. Eur. J. 2025) — 7 fragments, enzyme-cleavable tags.

## Chemo-Enzymatic Hybrid Approaches
- **Peptiligase**: subtilisin-derived, 98% yield in <1 hour. Used for aviptadil (28-mer).
- **Butelase 1**: fastest known peptide ligase (kcat/KM 1,340,000 L/mol/s). Butelase AY variant (2024).
- **Chemputer (Cronin lab, 2025)**: Nature Comms 16:7322. Programmable SPPS + click chemistry + NCL in single automated workflow. 1635 unit operations over 85 hours.

## "Protein Printer" Startups/Products
- **Nuclera**: NOT chemical synthesis — cell-free TX-TL on digital microfluidics cartridge. DNA→protein. $75M raised. ~48 hours.
- **CEM (Liberty Blue/PRIME)**: Commercial SPPS instruments. UE-SPPS (2025): 95% waste reduction, up to 100 residues.
- **Amide Technologies** (Pentelute spinoff): commercializing flow SPPS.

## Cell-Free Protein Synthesis (CFPS) as Alternative
- PURE system: 100-200 µg/mL batch, up to 1.16 mg/mL CECF. Terminates within 2 hours (batch).
- Ribosome speed: **10-15 AA/sec** at 37°C vs. flow SPPS ~1.5 AA/min → ribosome is **600-900x faster**.
- Extended PURE: >30 hours by dialysis; 12.5 consecutive days with feeding.

## ORIGINALITY ASSESSMENT: MODERATE (5-6/10)
The "protein printer" concept is not new (Nuclera, CEM, Pentelute flow SPPS all exist). The genuinely open gaps are:
1. **Automated end-to-end pipeline**: SPPS fragments → automated NCL → automated refolding. No integrated system exists.
2. **Folding after chemical synthesis**: many chemically assembled proteins fail to fold. No systematic solution.
3. **Cost reduction**: reagents dominate cost at $2-4/residue. No transformative cost approach proposed.
4. **Scale**: milligrams are fast; grams of a 100+ AA protein cleanly is unsolved.

The strongest angle: propose a specific automated pipeline that integrates flow SPPS + enzymatic ligation (peptiligase/butelase) + chaperone-assisted refolding in a single instrument. This specific combination is not published.
