# Literature Review - Rapid Gene Cloning

## Existing Cell-Free Cloning/Assembly Systems

### HyperXpress (2022) - Most Direct Predecessor
- **Zibulski, Schlichting, and Kabisch (2022).** "HyperXpress: Rapid Single Vessel DNA Assembly and Protein Production in Microliterscale." *Frontiers in Bioengineering and Biotechnology* 10:832176.
- Single-vessel LCR → RCA (phi29) → CFPS, all in 384-well. ~10-hour turnaround.
- Limitations: only 35.3% LCR success; no sequence verification step; RCA produces concatamers.

### One-Pot Golden Gate + TX-TL (2025) - Most Recent
- **bioRxiv 2025.08.28.672974** (PMC12407826). "One-pot cloning and protein expression platform for genetic engineering."
- Golden Gate assembly + cell-free TX-TL in single vessel. Eliminates transformation entirely.
- Validated: fluorescent proteins, luciferase, violacein pathway. 8-hour TX-TL expression.
- Limitation: functional verification only, no sequence confirmation.

### Phi29 RCA Cell-Free Cloning
- **Dean et al. (2001).** *Genome Research* 11:1095-9. Foundational phi29 RCA for cell-free plasmid amplification.
- **Fujii et al. (2009).** *BioTechniques* 47:749-51. Single molecule → >10^12-fold amplification without transformation.
- **PNAS 2005** (doi:10.1073/pnas.0508809102). Single-molecule RCA cloning via phi29.
- NEB now sells phi29-XT with improved thermostability.

## Cell-Free TX-TL Systems
- **Shin & Noireaux (2012).** *ACS Synth. Biol.* 1:29-41. Linear DNA in E. coli TX-TL with GamS protection; 4-component genetic switch in <8 hours.
- **Garamella et al. (2016).** *ACS Synth. Biol.* 5:344-55. TXTL Toolbox 2.0: 0.75 mg/mL protein, 98% cost reduction vs. commercial.
- **Garenne et al. (2021).** *Synthetic Biology* 6:ysab017. TXTL 3.0: up to 4 mg/mL eGFP batch, >6 mg/mL semi-continuous.
- **Akaby (Nozawa et al., 2022).** *PLOS One* 17:e0266272. RecB-knockout extract for linear DNA without GamS.
- **Hunt, Jewett et al. (2024).** *Chemical Reviews* 125:91-149. Comprehensive review.

## Construct Verification
- **DuBA.flow (Heymann et al., 2024).** *ACS Synth. Biol.* 13:457-465. Nanopore validation <€0.10/sample. Separate step from assembly.
- **Biofoundry-Scale Validation (2024).** *ACS Synth. Biol.* PMC10877595. High-throughput Nanopore for assembly validation.

## Commercial Products
- **Elegen (ENFINIA DNA):** Cell-free cloning technology, up to 7 kb, 20x accuracy. Launched 2023.
- **Ansa Biotechnologies:** Enzymatic DNA synthesis (TdT-dNTP conjugates), up to 7.5 kb clonal genes. Launched 2024.
- Neither offers an end-user single-pot assemble-and-verify kit.

## THE GAP: Integrated Sequence Verification
**No published system integrates assembly + functional expression + sequence confirmation in a single workflow.** All current systems use functional readout (fluorescence, activity) but still require a separate sequencing step. Coupling inline nanopore QC with cell-free assembly is the unexplored angle.
