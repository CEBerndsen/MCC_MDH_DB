---
editor_options: 
  markdown: 
    wrap: 72
---

# Humans Malate Dehydrogenase 1

# P40925

# Acetylation at 298

## Description

# Malate Dehydrogenase (MDH) is a crucial enzyme for human metabolism, energy production, redox balance and biosynthetic processes. It works as a catalyst for the reversible reaction between malate and oxaloacetate by using NAD+ or NADP+ as a cofactor. Both cofactors are essential in the tricarboxylic acid cycle (TCA) and malate-aspartate shuttle (MAS), which helps cells maintain energy levels and redox states. There are many various forms within this enzyme family, which all share common features such as nucleotide and substrate binding regions. They are able to assemble subunits that form dimeric and tetrameric enzymes, depending on their structure (Berndsen & Bell, 2024). The primary differences between the various structures come down to the quaternary structure and active site movements. In humans, there are two isoforms that exist: MDH1 and MDH2. MDH1 is found in the cytosol and assists with the MAS, by shuttling electrons across the mitochondrial membrane to regenerate NAD+ for glycolysis. On the other hand, MDH2, is found in the mitochondria and is involved in the TCA cycle, where it helps produce ATP through oxidative phosphorylation. Interestingly, MDH1 has been shown to have a role in pathological conditions like cancer. The alterations in MDH activity can help contribute to metabolic reprogramming observed in tumor cells, helping their demands (Leverette et al., 2024). Overall, Malate Dehydrogenase plays a key role in maintaining various body processes in the human body. There has been little research done on Malate Dehydrogenase 1, specifically relating to mutations in the amino acid Lysine (K). When lysine is replaced with Glutamine (Q), it mimics Lysine acetylation. The mutation mimics lysine acetylation and is associated with increased enzymatic activity. This increased activity would lead to a more stable active site and enhance substrate binding.

1.  image of the unmodified site ![Image representing the unmodified
    site of MDH1 using mol\*, with information gathered from Alphafold3.
    The original site, Lysine 298 hydrogen bonded to Valine
    290.](images/originalsite.png)

2.  image of modification site ![Image representing the modification
    site of MDH1 using mol\*, with information gathered from Alphafold3.
    The modified site, Glutamine 297 hydrogen bonded to Valine
    290.](images/modifiedsite.png)

3.  image of mimic site ![Image representing the mimic site of MDH1
    using mol\*, from Alphafold3. The mimic site, Glutamine 297,
    hydrogen bonded to Valine 290.](images/mimicsite.png)

4.image of mimic site ![Image representing the mimic site of MDH1 using
mol\*, with information gathered from Boltz-1. The mimic site, Glutamine
297, hydrogen bonded to Valine 290.](images/mimicsiteBOLTZ.png)

## Effect of the sequence variant and PTM on MDH dynamics

1.  Image of aligned PDB files (no solvent) ![Image representing the
    alignment of mimic (pink), modified (orange), and unmodified (blue)
    PDB files in mol\*.](images/AlignedPDB.png)

2.  Image of the site with the aligned PDB files (no solvent) ![Image
    representing the site alignment of mimic (yellow), modified
    (orange), and unmodified (blue) PDB files in
    mol\*.](images/AlignedsitePDB.png)

3.  Annotated RMSF plot showing differences between the simulations
    ![Annotates RMSF plot showing peaks of the unmodified residues
    fluctuating between 0 and 3.5, with information gathered from
    Colab2.](images/originalRMSF.png)

4.  Annotated RMSF plot showing differences between the simulations
    ![Annotated RMSF plot showing peaks of the mimic residues
    fluctuating between 0 and 2.8, with information gathered from
    Colab2.](images/mimicRMSF.png)

5.  Annotated plots of pKa for the key amino acids ![Comparison of the
    pKa values of the active sites in the unmodified and mimic MDH1
    models. The active site shifted from Histidine 187 to Histidine 186
    after acetylation, however both were correctly aligned in mol\*. The
    standard deviations of the active sites were 0.7 in both
    models.](images/originalvsmodifiedpKagraph.png)

6.  Annotated plots of pKa for the key amino acids ![Annotates pKa plot
    for the unmodified residue amino acid ASP 159 vs the mimic residue
    amino acid ASP 158 in mol\*. The values fluctuated between pKa 2 and
    5 and the standard deviation for the mimic (0.8) and for the
    unmodified (0.6).](images/aminoacidresidueoriginalvsmimicpKa.png)

Description of the data and changes

## The authentic PTM and the mimic variant are both hydrogen bonded to the VAL 290. However, the difference is that the hydrogen bond of the mimic has a distance of 5.11 A, and the PTM has a distance of 1.62 A. The PTM would therefore have a tighter, and potentially stronger hydrogen bond to VAL 290, compared to the mimic who has a more relaxed,longer bond. The stronger bond with PTM helps stabilize the position, which will help catalytic activity and substrate binding. In contrast, the mimic would provide more flexibility which would reduce the effect of substrate binding. The PTM model enhances the stabilization of the enzyme, while the mimic is unable to fully match this effect, leading to reduced substrate interactions. The change between the two models could have a big effect when it comes to enzyme signaling and function. Both the mimic and the PTM portray a perfect example of how structure does equal function, and how a small change makes a big difference in enzymatic activity.

## Authors

Erin K Marks

## 05/07/2025

## License

Shield: [![CC BY-NC
4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

This work is licensed under a [Creative Commons
Attribution-NonCommercial 4.0 International
License](https://creativecommons.org/licenses/by-nc/4.0/).

[![CC BY-NC
4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)

## References

-   Beeler, S.; Liu, H. C.; Stadler, M.; Schreier, T.; Eicke, S.;
    Lue, W. L.; Truernit, E.; Zeeman, S. C.; Chen, J.; Kötting, O.
    Plastidial NAD-Dependent Malate Dehydrogenase Is Critical for Embryo
    Development and Heterotrophic Metabolism in Arabidopsis. Plant
    Physiol. 2014, 164 (3), 1175–1190.
    [10.1104/pp.113.233866](https://doi.org/10.1104/pp.113.233866)
-   Berndsen, C. E.; Bell, J. K. The Structural Biology and Dynamics of
    Malate Dehydrogenases. Essays Biochem. 2024, 68 (4),
    Article 39113569. (<https://pubmed.ncbi.nlm.nih.gov/39113569/>)
-   Hekkelman, M. L.; de Vries, I.; Joosten, R. P.; Perrakis, A.
    Alphafill: Enriching Alphafold Models with Ligands and Cofactors.
    Nature Methods 2022, 20 (2), 205–213.
    [10.1038/s41592-022-01685-y](DOI:10.1038/s41592-022-01685-y.)
-   Leverette, B.; Austin, S.; Tan-arroyo, J. Malate Dehydrogenase (MDH)
    in Cancer: A Promiscuous Enzyme, a Redox Regulator, and a Metabolic
    Co-Conspirator. Essays Biochem.
    (<https://pubmed.ncbi.nlm.nih.gov/38864161/>)
-   Minarik, P.; Tomaskova, N.; Kollarova, M.; Antalik, M. Malate
    Dehydrogenases—Structure and Function. Gen. Physiol. Biophys. 2002,
    21 (3), 257–265. (<https://pubmed.ncbi.nlm.nih.gov/12537350/>)
-   Mirdita, M.; Schütze, K.; Moriwaki, Y.; Heo, L.; Ovchinnikov, S.;
    Steinegger, M. Colabfold: Making Protein Folding Accessible to All.
    Nature Methods 2022, 19 (6), 679–682.
    [s41592-022-01488-1](DOI:10.1038/s41592-022-01488-1)
-   Peterson, C. N.; Cornely, K.; Parente, A. D.; Springer, A. L.;
    Provost, J. J. Uncovering Malate Dehydrogenase: Structure, Function
    and Role in Disease. Essays Biochem. 2024, 68 (6), Article 39361129
    (<https://pubmed.ncbi.nlm.nih.gov/39361129/>)
-   Sehnal, D.; Bittrich, S.; Deshpande, M.; Svobodová, R.; Berka, K.;
    Bazgier, V.; Velankar, S.; Burley, S. K.; Koča, J.; Rose, A. S.
    Mol\* Viewer: Modern Web App for 3D Visualization and Analysis of
    Large Biomolecular Structures. Nucleic Acids Research 2021, 49 (W1).
    [10.1093/nar/gkab314](DOI:10.1093/nar/gkab314)
-   Wang, M.; Zhou, C.; Yu, L.; Kong, D.; Ma, W.; Lv, B.; Wang, Y.; Wu,
    W.; Zhou, M.; Cui, G. Upregulation of MDH1 Acetylation by HDAC6
    Inhibition Protects Against Oxidative Stress-Derived Neuronal
    Apoptosis Following Intracerebral Hemorrhage. Cell. Mol. Life Sci.
    2022, 79, 159.
    [10.1007/s00018-022-04446-3](https://doi.org/10.1007/s00018-022-04446-3)
