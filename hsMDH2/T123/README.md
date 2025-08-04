---
editor_options: 
  markdown: 
    wrap: 72
---

# Human MDH2

# Uniprot ID: P40926

# Variation: Phosphorylation of T123

## Description

The phosphorylation of threonine 123 (95 in the processed sequence) in
malate dehydrogenase 2 has had some previous studies, discovering that
this change significantly impacts the structure and function of this
protein. A study has shown that phosphorylation has the potential to
modulate the efficiency and dynamics of these interactions, affecting
the overall function of the metabolon and, by extension, the TCA cycle
(Atienza, Provost 2024). Phosphorylation of MDH can lead to unfolding,
changes in structure, and alter its interactions with other proteins and
overall affect its ability to participate in the citric acid cycle. This
specific modification has been previously researched, but overall the
phosphorylation of MDH2 will affect its catalytic activity and altering
its polarity, charges, and hydrogen bonds. When observing this certain
mimic, T123, in this project I was able to illustrate that the mimic and
the unmodified sites have only three of the same surrounding amino
acids, ALA 94, ASN 93 and ILE 96. The mimic site, TPO 95, has a direct
hydrogen bond attached to THR 99 with different surrounding amino acids
such as THR 92, and ALA 98. These are different from the amino acids
surrounding the unmodified site that is VAL 97, with the biggest
noticeable difference in the hydrogen bonding between the two. This
project will illustrate how this certain modification will alter the
structure and function of MDH2.

1.  image of the unmodified site ![unmodified
    site](/images/molstar/unmodified_image.png)

2.  image of modification site ![modification
    site](/images/molstar/mimic_image.png)

## Effect of the sequence variant and PTM on MDH dynamics

After running my data in the molecular dynamics, there are very
noticeable differences in my protein from the mimic. The pKa values that
were given to me showed a very low values, at around 4.0, at the
specific position of the mimic site (95). This indicates a stronger
acid, meaning it will more easily lose its proton and change the
hydrogen bonding and weak interactions of these amino acids, previously
shown in Mol\*. Both the RMSD and RMSF plots showed irregular patterns
and an overall slowing of this protein. These plots showed how the mimic
alters the protein's flexibility and stability, overall causing
conformational changes in its structure making this protein less likely
to perform its regular catalytic activity and bind to other proteins
that it normally could. Lastly, the line plots shown for my specific
amino acid sequence (95) showed a distinctly different pattern,
appearing to be much more irregular than the normal aspartic acid (70)
plot. Due to aspartic acid being in its wrong position, it destabilizes
the protein, completing altering its structure. Overall, the molecular
dynamics provided a large amount of data to illustrate how this mimic
will completely alter MDH2's structure in terms of hydrogen bonding and
weak interactions therefore resulting in alterations in function.

1.  Image of aligned PDB files (no solvent) ![aligned
    image](/images/alphafold/aligned.png)

2.  Image of the site with the aligned PDB files (no solvent) ![site
    aligned](/images/molstar/aligned_site.png)

3.  Annotated RMSF plot showing differences between the simulations
    ![RMSF plot](/images/colab_2/rmsf_plot.png)

4.  Annotated plots of pKa for the key amino acids ![pKa
    values](/images/colab_2/pKa_over_traj.png) ![pKa
    values](/images/colab_2/pKa_describe.png)

5.  Line plots for the key amino acids ![line plot amino acid
    95](/images/colab_2/line_plot_95.png) ![line plot amino acid
    70](/images/colab_2/line_plot_70.png)

## Comparison of the mimic and the authentic PTM

After completing this project, I have gathered a large amount of data to
observe the effects of phosphorylation of MDH2 by changing the amino
acid threonine to aspartic acid. The data that I gathered from AlphaFold
3, Boltz, Mol\*, and both of the MD Colabs all supported the idea that
changing the amino acid sequence will alter the structure and function
of MDH2. The structure of this protein will completely change by
flipping and becoming more compacted, which will then affect the
function of this protein. If the entire structure is changed, this
protein will not be able to interact as well with other proteins that it
normally can interact with. Being that MDH2 is essential in the citric
acid cycle, if there is a mimic or PTM in the amino acid sequence, then
this protein will not be able to carry out the proper functions for the
body during this cycle. Phosphorylation can lead to poor
substrate-binding with other proteins, specifically in the citric acid
cycle. MDH2 localizes to the mitochondria in humans and the cytoplasm in
plants, which are the key organelles in carrying out the citric acid
cycle. Structural changes will affect this normal functioning from
happening. In conclusion, altering the MDH2 amino acid sequence at
position 95 by phosphorylation will result in a complete protein
structural change, therefore leading to the disruption of catalytic
activity, substrate binding, and the citric acid cycle in mitochondrial
and cytoplasmic organelles.

## Authors

Mazur A. Rachel

## 5/7/2025

## License

Shield: [![CC BY-NC
4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

This work is licensed under a [Creative Commons
Attribution-NonCommercial 4.0 International
License](https://creativecommons.org/licenses/by-nc/4.0/).

[![CC BY-NC
4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)

## References

-   Peterson, Celeste N.; Cornely, K.; Parente, Amy D.; Springer, Amy
    L.; Provost, Joseph J. Uncovering Malate Dehydrogenase: Structure,
    Function and Role in Disease. Essays in Biochemistry 2024, 68 (2),
    53–55. [DOI](https://doi.org/10.1042/ebc20240044)

-   Parente, Amy D.; Bolland, Danielle E.; Huisinga, Kathryn L.;
    Provost, Joseph J. Physiology of Malate Dehydrogenase and How
    Dysregulation Leads to Disease. Essays in Biochemistry 2024.
    [DOI](https://doi.org/10.1042/ebc20230085)

-   Atienza, E.; Provost, J. Abstract 2020 Probing the Impact of
    Phosphorylation between MDH2 and CS Interactions through In-Vitro
    Crosslinking. Journal of Biological Chemistry 2024, 300 (3),
    107024–107024. [DOI](https://doi.org/10.1016/j.jbc.2024.107024)

-   Provost, J.; Cornely, K.; Mertz, P.; Peterson, C.; Riley, S.;
    Tarbox, H.; Narasimhan, S.; Pulido, A.; Springer, A. Phosphorylation
    of Mammalian Cytosolic and Mitochondrial Malate Dehydrogenase:
    Insights into Regulation. Essays in Biochemistry 2024.
    [DOI](https://doi.org/10.1042/ebc20230079)

-   Martínez, L. Automatic Identification of Mobile and Rigid
    Substructures in Molecular Dynamics Simulations and Fractional
    Structural Fluctuation Analysis. PLOS ONE 2015, 10 (3),
    e0119264.[DOI](https://doi.org/10.1371/journal.pone.0119264)

-   Sehnal, D.; Bittrich, S.; Deshpande, M.; Svobodová, R.; Berka, K.;
    Bazgier, V.; Velankar, S.; Burley, S. K.; Koča, J.; Rose, A. S.
    Mol\* Viewer: Modern Web App for 3D Visualization and Analysis of
    Large Biomolecular Structures. Nucleic Acids Research 2021, 49 (W1).
    [DOI](https://doi.org/10.1093/nar/gkab314)

-   Desai, D.; Kantliwala, S.; Vybhavi, J.; Ravi, R.; Patel, H.;
    Patel, J. Review of AlphaFold 3: Transformative Advances in Drug
    Design and Therapeutics. Cureus 2024, 16 (7).
    [DOI](https://doi.org/10.7759/cureus.63646)

-   Wohlwend, J.; Corso, G.; Passaro, S.; Mateo Reveiz; Leidal, K.;
    Swiderski, W.; Tally Portnoi; Chinn, I.; Silterra, J.; Tommi
    Jaakkola; Barzilay, R. Boltz-1: Democratizing Biomolecular
    Interaction Modeling. bioRxiv (Cold Spring Harbor Laboratory) 2024.
    [DOI](https://doi.org/10.1101/2024.11.19.624167)
