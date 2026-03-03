# Technical Feasibility Analysis - Direct Protein Synthesis

## Approach Details
REFINED: Automated pipeline integrating flow SPPS → enzymatic ligation (peptiligase/butelase) → chaperone-assisted refolding. One instrument, DNA sequence in, folded protein out.

## Feasibility Assessment
- Flow SPPS: proven for up to 164 AA (Pentelute 2020) ✓
- Enzymatic ligation: butelase is fastest known (kcat/KM 1.34M), peptiligase 98% yield in <1h ✓
- Chaperone-assisted refolding: well-studied but protein-specific ✗ (unpredictable)
- Integration: Chemputer (Cronin 2025) shows programmable multi-step chemical synthesis is feasible ✓

## Key Risks
1. **Folding**: the #1 unsolved problem. Most chemically synthesized proteins need case-by-case refolding optimization.
2. **Fragment purification**: HPLC between each fragment adds time and manual intervention.
3. **Competition**: Amide Technologies (Pentelute spinoff) and CEM are already commercializing flow SPPS.
4. **CFPS is often simpler**: for most use cases, cell-free expression from DNA is faster and cheaper.

## Where This Wins Over CFPS
- D-proteins, mirror-image proteins (not encodable by DNA)
- Non-canonical amino acid incorporation at any position
- Proteins toxic to cells
- Modified backbones (depsipeptides, stapled peptides)

## Originality Score: 5/10 (concept exists; specific integration is novel)
## Tractability Score: 6/10 (components exist but folding is unsolved)

## RECOMMENDATION: KEEP but narrow focus to D-protein/non-canonical applications where CFPS can't compete
