---
editor_options: 
  markdown: 
    wrap: 72
---

# Human malate dehydrogenase 1

# Uniprot ID:P40925

# Variation: phosphorylation of S277

## Description

The modification that was assigned to describe the effects was made on amino acid serine 277 to have a phosphorylated (p) modification and a mimic substitution from serine 277 (S) to aspartic acid (D). There has not been research describing this modification to this day, however there are some notable changes made. The phosphorylated modification and mimic variant occur on a flexible surface loop of MDH1, approximately 55 Å from the oxaloacetate binding site and 61 Å from the catalytic residue His187, placing it far from the active site and dimer interface. Despite similar positioning in space, the phosphorylated (pS277) and mimic variant (S277D) differ slightly in orientation, with the phosphorylated residue protruding further from the surface of the protein. In terms of weak interactions, the modified and mimic both maintain a hydrogen bond between Tyr278 and Asn276. The unmodified (Ser277) structure shows hydrogen bonding between Tyr277 and Asn275, and Ser276 with Glu300, which are not preserved in the modified or mimic forms. These changes reflect that while overall structure is preserved, local sets of interactions are altered slightly, which can impact protein dynamics or surface.

1.  Alignment of MDH1(teal), MDH1 with pS277 (purple), and S277D (green)
    ![Overall image of all three sequences super together in Mol\*;
    including the original, mimic, and modified sequence. RMSD value of
    AlphaFold3 original model with mimic: 0.41, RMSD value of AlphaFold3
    original model original with modified: 0.32. Both values are
    suitable since they are closer to zero, meaning they are similar to
    the original sequence. However, the modified model is more similar
    than the mimic.](images/superposed_models.png)

2.  Modification site alignment within MDH1 ![Highlighted in green, it
    includes all three models of the modifications that were made,
    located on a loop. The unmodified, modified, and mimic variant all
    are oriented in different directions. They all make hydrogen bonds
    with Tyr278-Asn276, however lack a hydrogen bond between Ser277 and
    Glu301 that is found in the original
    MDH1.](images/modified_site.png)

## Effect of the sequence variant and PTM on MDH dynamics

The structural comparison of unmodified MDH1 to its phosphorylated (PTM)
and mimic (S277D) variants shows minimal global differences but reveals
notable local changes that may impact protein function. These changes
occur at Ser277, a surface-exposed residue situated on a flexible loop
opposite the active site. Phosphorylation at Ser277 introduces a bulky,
negatively charged phosphate group, which alters local interactions and
geometry. The added negative charge and rigidity may reduce loop
flexibility and could repel negatively charged substrates like malate or
NAD⁺, potentially disrupting binding or orientation. The S277D mimic
similarly introduces a negative charge but is smaller and structurally
distinct. It has a different carboxylate oxygen geometry compared to the
tetrahedral phosphate.This mismatch may lead to weaker or fewer
stabilizing interactions, limiting the mimic’s reliability in
reproducing true PTM behavior. Although Ser277 is not directly in the
active site, it is near residues important for substrate binding and
dimer stabilization. Increased loop rigidity from phosphorylation may
hinder substrate access, reduce conformational adaptability, or alter
NAD⁺/malate orientation, which could decrease enzymatic efficiency. The
difference in weak interactions may reflect misaligned interactions,
which could interfere with proper residue positioning in the catalytic
pocket. The loss of hydrogen bonding could disrupt the alignment of
active site residues, potentially affecting catalysis. MDH1 catalyzes
the conversion of malate to oxaloacetate in the TCA cycle, producing
NADH, a crucial electron donor for the electron transport chain.
Phosphorylation at Ser277 by reducing structural flexibility or
disrupting substrate binding may impair MDH1 function. This could slow
the TCA cycle, decrease NADH production, and compromise mitochondrial
ATP output. This disruption could have significant physiological
effects, particularly in high-energy-demand tissues like the heart,
skeletal muscle, and liver, where oxidative metabolism is essential.

1.  The RMSD of the final frame from MD simulations of MDH1 and MDHS277D
    was 0.41, and MDH1 and MDHpS277 was 0.32. The unmodified is shown in
    teal while the modified form is shown in purple. ![After simulation,
    the overall protein structures are similar, as well as within the
    modification and active
    sites](images/modified_unmodified_structure.png)

2.  The modification site alignment within MDH1 ![This shows aligned
    interactions between the phosphorylated modification and MDH1. Both
    share a hydrogen bond with Tyrosine and Asparagine, but only the
    original MDH makes a hydrogen bond between the serine and glutamic
    acid.](images/MDH1_S276_pS277_site.png)

3.  The active site alignment within MDH1 ![This shows aligned
    interactions between all models within the active site of MDH1. Both
    the modification and mimic variant share similar hydrogen bond weak
    interactions compared to the original MDH.] (images/active_site.png)

4.  Annotated RMSD plot of mimic variant !(images/RMSD_mimic.png)

5.  Annotated RMSD plot of unmodified model ![The RMSD plot helps look
    at the stability and any structural changes. In the RMSD plot for
    the mimic, the trajectory for the S277D mimic steadily increased and
    plateaued at approximately 1.5-1.7. In contrast, the unmodified MDH1
    model showed a lower RMSD plateau around 1.2-1.3, but maintained
    less of a “staggered” line like the mimic did. This reflects greater
    structural retention overtime and stability]
    (images/RMSD_unmodified.png)

6.  Annotated RMSF plot of mimic variant !(images/RMSF_mimic.png)

7.  Annotated RMSF plot of mimic variant ![The RMSF plots further
    support the structural differences observed in the models. The mimic
    RMSF plot exhibits elevated fluctuations near residue 277, with
    peaks reaching \~4.0, indicating increased local flexibility in that
    region. In contrast, the unmodified model in RMSF plot maintains
    lower fluctuations, rarely exceeding 3.0. These heightened dynamics
    in the mimic, particularly across loop regions, suggest that the
    S277D substitution may destabilize the surrounding
    structure—potentially impacting substrate binding or dimer interface
    stability. (images/RMSF_unmodified.png)

8.  Annotated plots of pKa for the key amino acids: mimic
    !(images/pka_mimic.png)

9.  Annotated plots of pKa for the key amino acids: unmodified ![In the
    mimic variant graph, a sharp spike in pKa up to as far as 8 is
    observed early in the simulation (around 200–300 units), followed by
    a return to a baseline near pKa 4 with mild fluctuations. This
    behavior suggests that the mimic (S277D) undergoes an initial period
    of electrostatic or conformational instability, possibly as the
    structure adapts to the negatively charged substitution. In
    contrast, the unmodified graph, which tracks the pKa of His186,
    shows consistent values fluctuating within a narrow range of 5–6
    over a shorter time frame (0–100 units). This reflects a more stable
    electrostatic environment and implies that the native structure
    maintains its integrity during
    simulation.](images/pka_unmodified.png)

Description of the data and changes

## Comparison of the mimic and the authentic PTM

While both the mimic and pS277 models introduce a negative charge at
residue 277, key differences exist. The mimic deviates more from the
native structure (RMSD = 0.41) than the phosphorylated model (RMSD =
0.32), suggesting reduced structural accuracy. Both variants maintain
global fold and do not displace the active site or dimer interface, but
their local environments differ. The phosphate group in pS277 is bulkier
and more rigid than the carboxylate in S277D, leading to distinct
hydrogen bonding patterns and reduced loop flexibility. RMSF analysis
shows greater fluctuation at residue 277 in the mimic, indicating less
conformational restraint compared to the PTM. These differences suggest
the mimic loop is more dynamic and may not replicate the stabilizing
effects of authentic phosphorylation. Functionally, both models preserve
active site hydrogen bonding, and key catalytic residues His186 and
His187 retain functional pKa values (\~5.5–6.5). However, the mimic
shows early pKa spikes and greater fluctuation over time, indicating
transient instability in protonation behavior. In summary, while the
S277D variant mimics charge and maintains general structure, it fails to
fully replicate the phosphate’s geometry, bonding, and stabilizing
effects. These differences may impact flexibility and interactions
important for MDH1 regulation. Therefore, S277D is a useful but limited
approximation for studying phosphorylation effects at this site.

### Colab notebook links

[Colab notebook
links](https://jmuedu-my.sharepoint.com/personal/berndsce_jmu_edu/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fberndsce%5Fjmu%5Fedu%2FDocuments%2FWork%2FTeaching%2FCHEM260L%2FSp2025%2Flecture%5Fdata%2FIndividual%20project%20data%2FTodd%5FM%2Fdata&csf=1&web=1&e=Xjf0OV&CID=8a98cdbb%2Dd304%2D484f%2D8252%2Db23814c7734b&FolderCTID=0x0120007ADA4311D7C89E4C8D83AC31CAD6B309)

## Authors

Mary Todd

## 5/7/24

## License

Shield: [![CC BY-NC
4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

This work is licensed under a [Creative Commons
Attribution-NonCommercial 4.0 International
License](https://creativecommons.org/licenses/by-nc/4.0/).

[![CC BY-NC
4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)

## References

[The Structural Biology and Dynamics of Malate Dehydrogenases][1]
[1]:<https://doi.org/10.1042/ebc20230082>

[Google Colaboratory][2]
[2]:<https://doi.org/10.1007/978-1-4842-4470-8_7>

[AlphaFold protein structure database][3]
[3]:<https://alphafold.ebi.ac.uk/entry/P40925>

[UniProt][4] [4]:<https://doi.org/10.1093/nar/gkae1010>

[Boltz-1 Democratizing Biomolecular Interaction Modeling][5]
[5]:<https://doi.org/10.1101/2024.11.19.624167>.
