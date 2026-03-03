# Literature Review - Ultrafast PCR

## Speed Records
- **Wittwer et al. (2015).** *Clinical Chemistry* 61:145-153. **Extreme PCR: 35 cycles in 14.7 seconds.** Glass capillaries in water baths. 10-20x elevated primer/polymerase concentrations.
- **Millington & Wittwer (2019).** *Biomol. Detection & Quantification* 17:100083. Kinetic requirements: denaturation 200-500 ms, annealing 300-1000 ms, extension of <100 bp needs zero hold.
- **Trauba & Wittwer (2017).** *J. Biomed. Sci. Eng.* 10:219-231. Microfluidic Extreme PCR: <1 min in thin-film polycarbonate.

## Photonic PCR (WELL-ESTABLISHED FIELD)
- **Sung et al. (2015).** *Light: Sci. & Appl.* 4:e280. **Original photonic PCR.** Gold nanofilm + 3.5W LED. 30 cycles in 5 min.
- **Lee et al. (2017).** *JACS* 139:8054-8057. Gold bipyramid nanoparticles + IR LEDs. Ultrafast real-time PCR.
- **Son et al. (2020).** *Nature Biomed. Eng.* 4:1159-1167. Magneto-plasmonic NPs. COVID RT-PCR in 17 min total.
- **Noh et al. (2021).** *ACS Nano* 15:9750-9760. Glass nanopillar + Au nanoislands. PCR in ~8 min.
- **Park et al. (2022).** *ACS Nano* 16:20533-20544. rGO hydrogel microparticles. **qPCR in 5 min.** 22°C/s heating, 23.5°C/s cooling.
- **Han et al. (2024).** *Nano Letters.* POWER-PCR: 3D plasmonic optical wells. **30 cycles in 4 min 24 s.**
- **Seo et al. (2024).** *Advanced Functional Materials.* Solid-phase photonic PCR for respiratory pathogen discrimination.
- **Yu et al. (2023).** *ACS Nano.* Plastic-on-metal cartridge. 6x faster than benchtop qPCR.

## Reviews (2025)
- *Research* (AAAS/SPJ) 2025. PMC12355009. Comprehensive: planar vs. volumetric photothermal approaches.
- *Critical Reviews in Biotechnology* 2025. All thermal cycling methods for rapid PCR.
- *Talanta* 2025. Photothermal media for ultrafast photonic PCR.
- *Microsystems & Nanoengineering* 2025. Nanomaterials in PCR.

## Commercial Rapid PCR
| System | Speed | Technology |
|--------|-------|-----------|
| NextGenPCR | **2 min** (30 cycles) | Three-zone stationary heating |
| BioFire FilmArray | 45-60 min | Nested PCR, Peltier |
| Cepheid GeneXpert | 25-45 min | Cartridge Peltier |
| Abbott ID NOW | 5-13 min | NEAR isothermal (not PCR) |

## Fundamental Speed Limits
| Step | Minimum Time |
|------|-------------|
| Denaturation | 200-500 ms |
| Annealing | 300-1000 ms |
| Extension (<200 bp) | ~0 ms (during ramp) |
| Thermal transitions (nanoliter) | <250 ms |
| **Theoretical minimum (35 cycles, short target)** | **~17-35 seconds** |

## ORIGINALITY ASSESSMENT: LOW
Sub-5-minute photonic PCR is well-published (multiple groups, 2015-2024). The field is mature with 4+ review papers in 2025 alone. Remaining gaps:
1. **Sensitivity at ultralow copy number** with rapid cycling (flagged in 2025 reviews)
2. **Multiplexed rapid photonic PCR** (most systems detect 1 target)
3. **Commercially viable disposable cartridges** (no commercial photonic PCR product exists)
4. **Active cooling integration** (cooling is bottleneck: 7-13°C/s vs. 22°C/s heating)
