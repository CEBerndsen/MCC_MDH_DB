---
editor_options: 
  markdown: 
    wrap: 72
---

# Human Malate Dehydrogenase

# Uniprot ID: P40926

# Variation: Acetylation of K185 (K161Ac in structure)

## Description

# Lysine 185 is in the C-terminal catalytic domain ofhMDH2 but not directly part of the active or binding sites. Studies have shown that the Acetylation of Lysine 185 enhances hMDH2 enzyme activity and that acetylation is the predominant form of modification that a substantial fraction of MDH can be acetylated in the cell [Zhao & Xu] (<https://doi.org/10.1126/science.1179689>) in 2010.

The acetylation of K161, K185 unprocessed, could lead to structural
changes in malate dehydrogenase through hydrogen bonding, charge
neutralization and potential allosteric effects. The modified structure
likely alters the existing hydrogen bonding patterns, either reducing or
redirecting interactions at this site. K161Ac is normally positively
charged, but acetylation can neutralize this charge, causing Van der
Wals interactions to destabilize changing how nearby residues pack
together.4 Regarding the mimic structure, the introduction of Glutamine
at position 161 may enable new hydrogen bonds with nearby residues as
well. The substitution of glutamine neutralizes the positive charge,
potentially disrupting interactions and causing structural
rearrangement. While K161Q mutation in hMDH2 does not directly alter the
active site or substrate binding residues, due to its distance it can
cause subtle structural changes causing indirect effects. Many studies
incorporating the acetylation of site 161 in hMDH2 have shown that the
post transactional modification occurring at this specific position does
not have a significant impact on the enzyme’s catalytic activity or
substrate binding.4 Structural mapping of the modified and unmodified
enzyme indicates that the location of K161 is distant from the active
site and ligand substrate binding sites. This separation suggests that
the acetylation occurring at K161 does not cause any structural changes
that would impact the active site or substrate binding site directly.
The acetylation and mimic of K161 in hMDH2 can affect the broader
metabolic pathways and it may indirectly change the enzymes catalytic
activity. These modifications can have an impact on the citric acid
cycle, malate aspartate shuttle, mechanisms and protein stability. hMDH2
catalyzes the reversible conversion of malate to oxaloacetate (OAA), if
K161Ac alters the enzyme activity it could affect how much OAA is
available which can reduce ATP production.3 The malate aspartate shuttle
is essential for transferring NADH from the cytosol to the mitochondria.
A K161Q variant could influence the activity of the shuttle by altering
enzyme interactions more specifically affecting the cellular redox
balance or ATP production. Acetylation can influence protein stability
and degradation pathways, K161Ac can alter the steady state levels of
hMDH2 influencing metabolic variability through pathways like the citric
acid cycle and malate aspartate shuttle.

1.  image of the unmodified site ![Lysine at site 161, processed
    sequence, of the unmodified structure.Originally at site 185 of the
    unprocessed sequence](images/ModsiteUnmodified.png)

2.  image of modification site ![ALY 161, highlighted in green, of the
    PTM modified protein with hydrogen bonds at Val 157 and ASP
    193](images/ModSitePMTModified.png)

## Effect of the sequence variant and PTM on MDH dynamics

In order to model the modifications and visualize how it affected the
unmodified structure of hMDH2, various methods were used. To create a
model with the modified (K185Ac) the processed sequence of hMDH2 was put
into the Alpha Fold 3 software. Since the number given of the amino acid
was from an unprocessed sequence, the next step was to find the amino
acid from the sequence given in the processed sequence, which was
161.\^7 To create the mimic model, the software Boltz was used. The
processed sequence of hMDH2, with the amino acid Q at 161 substituted
for the K in the sequence, was put into Boltz to generate the model with
the sequence change.6 Once both folders containing the .cif files for
the modified, and model structures were obtained and downloaded, Colab
software was used for the variant model structure to simulate the
effects of the substitution on the protein structure and dynamics. The
Colab required two steps to achieve the data needed to study the effects
of the substitution. Colab step 1 created the no-water .dcd and .pdb
files of the mimic structure needed to continue to step 2 of the Colab.
Running Colab Step 2 required inputting the .dcd and .pdb filed
generated and resulted in numerous codes being ran to develop RMSF
plots, and pKa values of amino acids affected. Developing these plots
and values allowed for the analysis of how the modification could have
affected the active site or substrate binding residues. To fully
visualize the effects of the modified and mimic compared to the
unmodified structure, obtained from project 2, these structures were
input into Mol\* and superimposed. The modified and unmodified were
input together and superimposed, the variant and unmodified were
superimposed, and the modified and mimic were superimposed and compared.
This allowed for the ability to visualize how close or far the
modification was to the active site, and binding sites and how the
modification directly affects the unmodified enzyme. Comparing the mimic
to the modified model gives the opportunity to analyze if the variant
and modified simulations match well together and if they could affect
the structure or function of the enzyme.

1.  Image of aligned PDB files (no solvent) ![Variant Structure, blue,
    and Unmodified superimposed, pink, in Mol\* with active site His 176
    and GLN 161 highlighted in green](images/VariantDistanceHis176.png)

2.  Image of the site with the aligned PDB files (no solvent) ![Variant
    Structure, in blue, superimposed in Mol\* with unmodified hMDH2 at
    site GLN 161](image/VariantSuperimposedUnmod.png)

3.  Annotated RMSF plot showing differences between the simulations The
    value of His176 from the unmodified RMSF plot was 0.49 and the RMSF
    of position 176 in the mimic was 0.55. The RMSF value of position
    161 in the mimic was 1.033 in the unmodified was 0.86. The increase
    in RMSF values mimic after going through simulations shows that the
    modification increases enzyme activity. Although it may not be
    detectable in a RMSF plot, the loss of cation pi interaction can
    increase the flexibility of the mimic structure ![RMSF chart from
    Colab Step 2 Analysis on the left of PTM Mimic and unmodified hMDH2
    plot on the right](images/rmsfplotmimicandunmodified.png)

4.  Annotated plots of pKa for the key amino acids The pka values from
    table 1 indicate that the pKa of His176 in the mimic structure is
    6.16 and compared to the pH of 7 this is in indication of the His176
    being in a deprotonated state supporting the RMSF values. However,
    comparing the pKa value of 6.16 to the pKa value 4.35 of MDH2, from
    project 2, shows that the pKa of His176 of the mimic is more
    protonated. The PTM mimic modified the environment of the active
    site to favor protonation of His176 making it more likely to enhance
    enzyme activity and participate in acid-base catalysis. In the PTM
    mimic the removal of PHE 194, shown in figure 2, influenced the rise
    in His176 pKa value to 6.16, enhancing it catalytic potential.5
    ![pka value of Amino acid 176 from Colab Step 2
    Analysis](image/pKaValueHis176.png)

## Comparison of the mimic and the authentic PTM

After superimposing the mimic and modified protein models, the model and
simulation data on the mimic variant does match well with the PTM
modified protein to an extent. Both models have a neutral charge due to
the acetylation removing the Lys+ charge, and the mimic sequence change
causing glutamine to replace Lysine. The mimic structure partially
replicated some aspects of the PTM modification but does not have the
full electrostatic effects the PTM modified protein has. The low RMSF
values for the site, and pKa values are an indication that the mimic
captured some of the functional properties of the PTM modified protein
as well as some of its electrostatic effects. Structurally, the key
difference between the two protein models is the side chains and the
electrostatic properties. GLN 161 contains an amide functional group,
while ALY 161 is bulkier by contributing to hydrophobic packing.3
Hydrogen bonding and cation-pi interactions differ between the two which
can lead to subtle differences in stability and affinity of the protein.
GLN 161 (mimic) is more polar, has strong H-bond donors and acceptors,
while ALY 161 (modified) contributed fewer hydrogen bonds due to its
hydrophobic acetyl group. Acetylation removes the positive charge of the
Lysine which alters the electrostatic balance in the active site, and
influence the residue protonation, in response glutamine may over
stabilize and mask flexibility required for catalysis.4 When ALY 161
participates in hydrophobic interactions, glutamine may destabilize them
or prevent certain folding. Furthermore, functional interpretations can
become more complicated by the loss of the cation-pi interaction in the
acetylated state that the glutamine in the mimic cannot reproduce.5
Overall, the mimic protein has a shorter side chain, more polar and
forms more hydrogen bonds that can in contrast can stabilize different
interactions or alter active site orientation indicating that on an
atomic level they are not identical, even if they are dynamically. The
mimic variant is not the best approximation of the PTM modified protein
because both proteins interaction networks differ, the mimic lacks the
structural bulk of the acetyl group meaning it may not be the best
substitution for ALY 161 and could yield misleading results.

![Mimic Variant in green and PTM modified protein in purpose
superimposed on Mol\*](image/MimicandModifiedSuperimposed.png.png)

### Colab notebook links

Provide file names of completed colab notebooks Colab1Project4.ipynb
Colab2Project4.ipynb

## Authors

Anjali Menon

## Deposition Date

## License

Shield: [![CC BY-NC
4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

This work is licensed under a [Creative Commons
Attribution-NonCommercial 4.0 International
License](https://creativecommons.org/licenses/by-nc/4.0/).

[![CC BY-NC
4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)

## References

(1) !Musrati, R. A.; Kollárová, M.; Mernik, N.; Mikulásová, D. Malate
    Dehydrogenase: Distribution, Function and Properties. General
    Physiology and Biophysics 1998, 17 (3), 193–210.

(2) !(2) malate-dehydrogenase - Creative Biogene. Creative-biogene.com.
    <https://microbiosci.creative-biogene.com/similar/malate-dehydrogenase-1135.html?msclkid=c6f712b2b8271b1c7ae97aa69cf61df4>
    (accessed 2025-05-07).

(3) !(3)Laura de Lorenzo; Stack, Tyler M. M.; Fox, K.; Walstrom, K.
    Catalytic Mechanism and Kinetics of Malate Dehydrogenase. Essays in
    biochemistry 2024, 68 (2). <https://doi.org/10.1042/ebc20230086>

(4) !Zhao, S.; Xu, W.; Jiang, W.; Yu, W.; Lin, Y.; Zhang, T.; Yao, J.;
    Zhou, L.; Zeng, Y.; Li, H.; Li, Y.; Shi, J.; An, W.; Hancock, S. M.;
    He, F.; Qin, L.; Chin, J.; Yang, P.; Chen, X.; Lei, Q. Regulation of
    Cellular Metabolism by Protein Lysine Acetylation. Science 2010, 327
    (5968), 1000–1004. <https://doi.org/10.1126/science.1179689>.

(5) !(5)Berndsen, C.; Bell, J. The Structural Biology and Dynamics of
    Malate Dehydrogenases. Essays in Biochemistry 2024, 68 (2).
    <https://doi.org/10.1042/ebc20230082>

(6) !Google Colab.
    <https://colab.research.google.com/drive/11-YR740UivK423wbWVz2Wfr-LU-tDbkN#scrollTo=3bHTRIwzaezg>

(7) !UniProt. www.uniprot.org.
    <https://www.uniprot.org/uniprotkb/P40926/entry>
