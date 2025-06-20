---
editor_options: 
  markdown: 
    wrap: 72
---

# Cytosplasmic Malate Dehydrogenase

# Uniprot number: P40925

# Variation: phosphorylationof T224 (pThr224 in structure)

## Description

Malate dehydrogenase 1 (MDH1) catalyzes the reversible oxidation of
malate to oxaloacetate (OAA) in the final step of the tricarboxylic acid
(TCA) cycle, coupling this redox reaction to the reduction of NAD⁺ to
NADH¹,². In human cells, MDH1 resides in the cytosol and cooperates with
mitochondrial MDH2 via the malate–aspartate shuttle to transfer reducing
equivalents across the inner mitochondrial membrane³,⁶. By regenerating
OAA, MDH1 maintains continuous flux through citrate synthase, thereby
sustaining ATP production and supplying biosynthetic precursors during
energy metabolism²,⁸. Structurally, MDH1 is a \~330–amino‑acid
homodimer; each monomer adopts a Rossmann‑fold motif for NAD⁺ binding
and contains a catalytic histidine (His 186) that facilitates hydride
transfer⁴. The substrate binds in a cleft between the N‑ and C‑terminal
domains, where a network of hydrogen bonds precisely orients malate for
oxidation⁴. Beyond its canonical role, MDH1 also supports cytosolic NAD⁺
regeneration under high glycolytic flux in proliferating cells⁵. Given
its central metabolic function, post‑translational modifications (PTMs)
of MDH1 likely regulate its activity, localization, or protein–protein
interactions in response to cellular signals⁷. In this study, we
investigate the structural and functional consequences of
phosphorylation at Thr 224, located on an α‑helix adjacent to the active
site, using both authentic PTM modeling and a phosphomimetic T224D
variant, and we employ AlphaFold3, Boltz-1, and molecular dynamics to
predict effects on hydrogen‑bonding, residue pKa, and protein dynamics.

1.  image of the unmodified site ![Original Project 2 - THR 224 -
    Threonine Amino
    Acid](images/Original%20Project%202%20-%20THR%20224%20-%20Threonine%20Amino%20Acid.png)

2.  image of modification site ![pThr224 vs both T224D
    mimics](images/mod%20vs%20both%20mimic%20at%20p%20224.png)

## Effect of the sequence variant and PTM on MDH dynamics

Both authentic phosphothreonine and the T224D variant eliminate the
Gly 220–Thr 224 hydrogen bond, causing local helix unwinding and
increased backbone flexibility in the 220–226 segment⁴. In T224D, the
aspartate carboxylate introduces a resonance stabilized negative charge,
whereas phosphothreonine carries two formal negative charges plus
additional hydrogen bond donors on its phosphate moiety⁷. Consequently,
T224D shows moderate helix perturbation, while pThr224 exhibits more
pronounced distortion and new phosphate mediated contacts with Gly 220
backbone amides and Lys 228 side chains⁷. Functionally, destabilization
of the helix adjacent to His 186 may alter positioning of the active
site loop, potentially decreasing NAD⁺ affinity⁴. Although neither
modification directly contacts malate binding residues, allosteric
shifts in C terminal hinge dynamics may impair catalytic closure. At the
pathway level, reduced MDH1 catalytic efficiency could slow OAA
regeneration, limiting TCA cycle flux and perturbing cytosolic NADH/NAD⁺
balance, thereby affecting downstream biosynthetic pathways and redox
homeostasis²,³.

1.  Image of aligned PDB files (no solvent) ![MDH Models
    Superimposed](images/Project%202%20-%20AlphaFold3%20Model.png)

2.  Image of the site with the aligned PDB files (no solvent) ![All
    Models Superimposed at position
    224](images/All%20Models%20Superimposed%20-%20Mirror%20Side%20of%20helix.png)

    ![](images/All%20Models%20Superimposed%20at%20Amino%20Acid%20224.png)

3.  Annotated RMSF plot showing differences between the simulations
    ![Original Boltz RMSF
    Plot](data/Original%20Project%202%20Boltz/CoLab%202%20Files/Og%20Boltz%20Outputs/rmsf_plot.png)

4.  Annotated plots of pKa for the key amino acids ![Boltz Mimic RMSF
    Plot](data/Boltz%20Mimic%20-%20T224D/CoLab%202%20Files/T224D%20-%20Outputs/rmsf_plot.png)

5.  Modification relative to redox active site ![Active site of both the
    Original and T224D mimic
    model](images/position%20of%20Thr%20-%20224%20and%20His%20-%20186%20on%20enzyme.png)

During the simulations, both T224D mimic variants maintained overall
dimer integrity but displayed distinct dynamic behaviors compared to the
original Boltz model. The original Boltz model reached an average RMSD
of 1.3221 Å, stabilizing at \~22 ns of simulation. In contrast, the two
T224D mimic variants exhibited higher average backbone deviations of
1.7238 Å, with stabilization occurring at \~25 ns. These results
indicate that the mimic variants undergo greater global structural
rearrangements before reaching equilibrium. Analysis of root mean square
fluctuations (RMSF) revealed reduced flexibility at His 186 (ΔRMSF
≈ –0.17 Å) and at position 224 (ΔRMSF ≈ –0.35 Å) in both mimic variants
relative to the original Boltz model, suggesting localized stiffening
due to the introduced negative charge on Asp 224. The mimic variants
also showed subtle increases in flexibility in adjacent loop regions
(residues 220–226), consistent with the helix perturbations observed in
static models. pKa calculations predict that Asp 224 (pKa ≈ 4.04)
remains fully deprotonated at physiological pH, generating persistent
negative electrostatic potential in the local environment. This
contrasts with Thr 224’s hydroxyl in the organic model. Notably,
Histidine-186’s pKa shifted from \~5.43 in the original Boltz model to
\~6.41 in the Boltz derived mimic and \~5.99 in the AlphaFold3 derived
mimic, indicating enhanced propensity for histidine protonation. Such
shifts may modulate the proton‐transfer step during catalysis. Overall,
the two T224D mimic variants demonstrate both global destabilization (as
evidenced by increased RMSD) and local stabilization around key
catalytic residues (lower RMSF), reflecting the dual structural impact
of introducing a charged side chain.

## Comparison of the mimic and the authentic PTM

Structurally, both T224D and pThr224 introduce negative charges at
position 224 and orient their oxygens similarly; however, the phosphate
ester’s tetrahedral geometry (109.5°) differs from the planar
carboxylate, resulting in subtle backbone shifts⁷. Phosphothreonine can
adopt multiple protonation states (pKa₂ ≈ 6–7), acting as a reversible
pH‑sensitive switch, whereas T224D remains locked in the deprotonated
form⁷. Thus, while T224D effectively mimics the electrostatic effect of
phosphorylation for steady‑state structural studies, it underestimates
the dynamic protonation range and hydrogen‑bonding versatility of
authentic PTM. For investigations of regulatory phosphorylation
dynamics, alternative mimics such as histidine substitutions may better
recapitulate reversible behavior.

![alt
text](images/Original%20Boltz%20Dimer%20superimposed%20w%20Modified%20AlphaFold3%20-%20His%20186%20active%20site%20-%20loss%20of%20hydrogen%20bonding%20on%20Asp%20130%20.png)

## Authors

Contributors names: John Kestyn

## Deposition Date: May 5th, 2025

## License

Shield: [![CC BY-NC
4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

This work is licensed under a [Creative Commons
Attribution-NonCommercial 4.0 International
License](https://creativecommons.org/licenses/by-nc/4.0/).

[![CC BY-NC
4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)

## References

1.  UniProt Consortium. UniProt: the universal protein knowledgebase
    in 2023. Nucleic Acids Res. 2023, 51 (D1),
    D523–D531.![10.1093/nar/gkac1052](https://doi.org/10.1093/nar/gkac1052)

2.  Berman, H. M.; Westbrook, J.; Feng, Z.; Gilliland, G.; Bhat, T. N.;
    Weissig, H.; Shindyalov, I. N.; Bourne, P. E. The Protein Data Bank.
    Nucleic Acids Res. 2000, 28 (1),
    235–242.![10.1093/nar/28.1.235](https://doi.org/10.1093/nar/28.1.235)

3.  Wang, L.; Wang, Y.; Du, J.; Kong, X.; Li, H.; Wei, X.; Zhao, F.;
    Guo, X. The malate–aspartate shuttle: how it started and where it
    stands. Biol. Rev. 2020, 95 (4),
    990–1006.![10.1002/iub.2367](https://doi.org/10.1002/iub.2367)

4.  Humphrey, W.; Dalke, A.; Schulten, K. VMD—Visual Molecular
    Dynamics. J. Mol. Graph. 1996, 14 (1),
    33–38.![10.1016/0263-7855(96)00018-5](https://doi.org/10.1016/0263-7855(96)00018-5)

5.  Onufriev, A.; Bashford, D.; Case, D. A. Exploring protein native
    states and large scale conformational changes with a modified
    generalized Born model. Proteins 2004, 55 (2),
    383–394.![10.1002/prot.20033](https://doi.org/10.1002/prot.20033)

6.  Lin, R.; Singh, A.; Traughber, B.; Chen, X.; Ye, B.; Wang, Y.; Zhou,
    X.; Gao, Q.; Xu, Y.; Lei, Q. Y. Malate dehydrogenase–mediated NADH
    regeneration supports glycolytic flux in proliferating cells. Cell
    Metab. 2016, 23 (3), 537–547.![DOI](DOI%20link)

7.  Portland Press. Phosphorylation of mammalian cytosolic and
    mitochondrial malate dehydrogenases. Essays Biochem. 2023, 67,
    505–515.![10.1042/EBC20230079](https://doi.org/10.1042/EBC20230079)

8.  Yan, Q.; Kurisu, G.; Yamazaki, T.; Yabuta, N.; Fukuda, K.; Kawasaki,
    Y.; Kimura, H.; Hori, J.; Tamura, T.; Ito, K. Structural
    characterization of human cytosolic malate dehydrogenase reveals the
    basis of ligand specificity. ACS Omega 2021, 6 (18),
    11843–11851.![10.1021/acsomega.1c04385](https://doi.org/10.1021/acsomega.1c04385)

9.  Dolinsky, T. J.; Czodrowski, P.; Li, H.; Nielsen, J. E.; Jensen, J.
    H.; Klebe, G.; Baker, N. A. PDB2PQR: an automated pipeline for the
    setup of Poisson–Boltzmann electrostatics calculations. Nucleic
    Acids Res. 2007, 35 (Web Server issue),
    W522–W525.![10.1093/nar/gkm276](https://doi.org/10.1093/nar/gkm276)

10. Ensembl Genome Browser. GRCh38: Ensembl release 89: ENSG00000014641.
    Ensembl. May 2017. <https://ensembl.org>
    (accessed Apr 2025).![DOI](DOI%20link)

11. Ensembl Genome Browser. GRCm38: Ensembl release 89:
    ENSMUSG00000020321. Ensembl. May 2017. <https://ensembl.org>
    (accessed Apr 2025).![DOI](DOI%20link)

12. National Center for Biotechnology Information. PubMed. U.S. National
    Library of Medicine. <https://pubmed.ncbi.nlm.nih.gov>
    (accessed Apr 2025).![DOI](DOI%20link)

13. National Center for Biotechnology Information. PubMed: Mouse. U.S.
    National Library of Medicine. <https://pubmed.ncbi.nlm.nih.gov>
    (accessed Apr 2025).![DOI](DOI%20link)

14. National Center for Biotechnology Information. Entrez Gene: Malate
    dehydrogenase 1, NAD (soluble). <https://www.ncbi.nlm.nih.gov/gene>
    (accessed Apr 2025).![DOI](DOI%20link)

15. Kim, E. Y.; Kim, W. K.; Kang, H. J.; Kim, J. H.; Chung, S. J.;
    Seo, Y. S.; Park, S. G.; Lee, S. C.; Bae, K. H. Acetylation of
    malate dehydrogenase 1 promotes adipogenic differentiation via
    activating its enzymatic activity. J. Lipid Res. 2012, 53 (9),
    1864–1876.![10.1194/jlr.M026567](https://doi.org/10.1194/jlr.M026567)

16. Wang, Y. P.; Zhou, W.; Wang, J.; Huang, X.; Zuo, Y.; Wang, T. S.;
    Gao, X.; Xu, Y. Y.; Zou, S. W.; Liu, Y. B.; Cheng, J. K.; Lei, Q. Y.
    Arginine methylation of MDH1 by CARM1 inhibits glutamine metabolism
    and suppresses pancreatic cancer. Mol. Cell 2016, 64 (4),
    673–687.![10.1016/j.molcel.2016.09.028](https://doi.org/10.1016/j.molcel.2016.09.028)
