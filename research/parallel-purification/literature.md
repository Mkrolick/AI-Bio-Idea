# Literature Review - Acoustic Parallel Purification

## CRITICAL: Acoustic Radiation Force Cannot Manipulate Proteins Directly
ARF scales with particle volume. Proteins (~5-10 nm) are too small for meaningful displacement.
All acoustic protein work uses carrier particles (beads) as the acoustic handle.

## Fastest Existing Purification
- **VFD + IMAC (Luo et al., 2024, Current Protocols)**: 4 minutes from crude lysate. Vortex fluidic device accelerates mass transfer.
- **Capturem Spin Columns (Takara Bio)**: 5 minutes, commercial, room temperature.
- **Magnetic beads (Dynabeads, NEBExpress)**: 5-15 minutes. Commercially mature. Automated via KingFisher.

## Acoustofluidic Protein Separation (Limited)
- **Aptamer-bead TSAW separation (2021, ACS Anal. Chem.)**: ONLY published paper on acoustofluidic protein separation. Analytical scale. Aptamer-coated beads of different sizes sorted by traveling SAW. Simultaneous 3-protein separation.
- No preparative-scale acoustofluidic protein purification exists.
- 2024 Analytical Chemistry review confirms: nanoparticle-scale acoustic separation requires new approaches.

## Microfluidic Purification
- **µNANEX chip (2024, Lab on a Chip)**: Nanobody exchange chromatography on chip. Minutes for protein complexes. Most exciting 2024 development.
- **CFPS + IMAC on-chip (2018, PMC6136919)**: Single chip integrates cell-free synthesis + purification.
- **3D-printed chromatography modules (2022, Lab on a Chip)**: Performance comparable to bench-scale.

## Single-Step / Ultra-Rapid Approaches
- **SIRP (split intein)**: ~50% cleavage in 30 seconds. Tagless product. gp41-1 variant (2023).
- **SpyTag003/SpyCatcher003**: 400x faster than original. Spy&Go purification. SpySwitch for reversible capture.

## ORIGINALITY ASSESSMENT: LOW (3-4/10)
His-tag purification is already a 4-5 minute process (VFD-IMAC, Capturem). The acoustic purification idea faces a **fundamental physics barrier** — proteins are too small for direct ARF manipulation. The bead-conjugation workaround makes it functionally similar to magnetic bead purification, which is already fast, cheap, and commercial.

**RECOMMENDATION: PRUNE this path.** The problem (slow purification) is largely solved, and the proposed mechanism (acoustics) has a fundamental limitation. The remaining gaps (labile protein purification, integrated CFPS+purification) are better addressed by other approaches.
