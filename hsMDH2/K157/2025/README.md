---
editor_options: 
  markdown: 
    wrap: 72
---

# Human MDH2

# P40926

# K157Q

## Description

Malate dehydrogenase also commonly referred to as MDH is an enzyme that plays a crucial role in human cellular metabolism. It is most well-known for its oxidation of malate into oxaloacetate. This conversion is not only reversible but is also aided by NAD+ and NADH as cofactors of the reaction[^1].

[^1]: Malate dehydrogenases--structure and function

In topics related to metabolism, MDH is a vital resource that helps in
metabolic pathways such as the citric acid cycle. The citric acid cycle
is vital in humans metabolism as it generates energy through various
sources such as carbohydrates and proteins. In the citric acid cycle,
MDH aids in the cycle’s overall success of generating energy by
catalyzing the oxidation of malate into oxaloacetate. This conversion
benefits the overall success of energy production by producing
oxaloacetate and NADH. The production of NADH then allows for the
overall system to succeed by donating electrons to the electron
transport chain (ETC) to help in the generation of energy[^2].

[^2]: MDH2 produced OAA is a metabolic switch rewiring the fuelling of
    respiratory chain and TCA cycle

While MDH on a cellular level can seem to have little to do with the
overall health of humans, in actuality it has drastic effects if
mutations or loss of function occurred. Specifically for malate
dehydrogenase 2 (MDH2) conditions such as cancer and neurodegeneration
have worsened when MDH2 is impaired within the body. In cancer patients,
it was seen that overexpression led to worsening effects such as
aggressive tumor growth[^3]. Along with this, declines in MDH2 activity
were found to contribute to worsening neurodegeneration conditions such
as Alzheimer’s[^4]. When discussing MDH it is often easy to think of
changes in its function to be minor however in reality even slight
changes to MDH can lead to worsening conditions in human diseases.

[^3]: Pyk2 and Src Mediate Signaling to CCL18‐Induced Breast Cancer
    Metastasis

[^4]: Mitochondrial abnormalities in Alzheimer brain: Mechanistic
    implications

1.  image of the unmodified site ![Lysine at site 133 of the unmodified
    structure. The site was originally 157 in the unprocessed sequence
    however the site number is 133 in the processed
    sequence.](images/unmodified_site_133.png)

2.  image of modification site ![Acetyl-L-lysine at site 133 in the
    modification structure.](images/aly_modified_133.png)

## Effect of the sequence variant and PTM on MDH dynamics

In order to model how the modifications affected the original structure
of MDH2, various methods were used in order to understand the effects on
its structure and overall function. For both the modified version and
mimic version of the structure AlphaFold3 was initially used in order to
mainly learn the confidence of predicting the structure and gaining .cif
files for further analysis. Then the appropriate .cif file was used in
Colab Steps 1 & 2 in order to gain information on the effects of the
substitution on the overall structure and function of the protein. Colab
Step 1 provided both a .dcd file and .pdb file with waters removed from
the mimic structure. Colab Step 2 provided information on the dynamicity
and pKa values of the mimic structure. This provided further information
on how the changes to the protein affected its overall dynamics and
function. In order to visualize the changes that had occurred with both
the modification and mimic variants, Mol\* was used. In Mol\* the files
used were the unmodified structure from Project 2, the mimic Boltz file,
the mimic AlphaFold3 file, and the modified AlphaFold3 file. By
superimposing these files, the structural changes through both the
modification and mimic variant changes were able to be compared to the
unmodified structure from Project 2.

1.  Image of aligned PDB files (no solvent) ![PDB files from unmodified
    structure and mimic structure superimposed in
    Mol\*.](images/aligned_pdb.png)

2.  Image of the site with the aligned PDB files (no solvent) ![PDB
    files from unmodified structure and mimic structure superimposed in
    Mol\*, focused at amino acid site 133.](images/aligned_pdb_133.png)

3.  Annotated RMSF plot showing differences between the simulations
    ![The RMSF plot of the unmodified
    sequence.](images/unmodified_rmsf.png) ![The RMSF plot of the mimic
    sequence.](images/mimic_rmsf.png)

4.  Annotated plots of pKa for the key amino acids ![The pKa table of
    the unmodified sequence focusing on amino acid sites 167 &
    176.](images/unmodified_pka.png) ![The pKa table of the mimic
    sequence focusing on amino acid sites 167 &
    176.](images/mimic_pka.png)

5.  If needed, show ligand bound images and how modification affects
    substrate binding

Description of the data and changes

## Comparison of the mimic and the authentic PTM

When comparing the files that were generated with the unmodified
structure in Mol\*, structural changes were observed. The site that was
changed for variant sequences was at amino acid site 133 (Image 6).
Initially in the unmodified site 133 Lysine was present. With the
modification file the amino acid site 133 was Acetyl-L-lysine (ALY).
With the mimic file, site 133 was Glutamine. With this change in the
sequence from the mimic file, Lysine was changed to Glutamine. This
structure change does not clearly affect amino acids that are involved
in substrate binding as the site does not interact with other amino
acids involved in substrate binding. With this change in the sequence
from a Lysine to Glutamine this meant that a functional group was lost
in the process. Given that Lysine has an amine group that helps it
respond to pH changes, this helps it respond to its environment as
opposed to Glutamine which has an amide group which keeps it neutral in
all pH ranges. When thinking of the broader metabolic pathway this
change could have effects on the proteins ability to respond to its
environment and potentially decreasing its efficiency.

6.  

    ![An image of amino acid site 133 with the unmodified file, mimic
    AlphaFold3 file, mimic Boltz file, and modified AlphaFold3 model
    superimposed in Mol\*. The unmodified sequence is gold, the mimic
    AlphaFold3 sequence is green, the mimic Boltz file is orange, and
    the modified AlphaFold3 sequence is
    blue.](images/site_133_all_pose.png)

Another change that was noted between the structures is the difference
in hydrogen bonding between HIS 176 and ASP 149. In the unmodified
structure there were two hydrogen bonds between the amino acids (Image
7). However in the modified and mimic structure it was seen that only
one hydrogen bond between HIS 176 and ASP 149 was seen off of the double
bonded oxygen of aspartic acid (Image 8). This change due to
modification does effect potential substrate binding as it has changed
the hydrogen bonds to HIS 176. While the loss of a singular hydrogen
bond would not necessarily effect histidine’s ability to carry out
substrate binding, it would effect aspects of histidine’s overall state
such as its stability. The loss of the hydrogen bond due to this
modification could result in weakened stabilization at HIS 176 and
increase effects such as flexibility. For the overall metabolic pathway,
the loss of the hydrogen bond could have effects such as the geometry
affecting the protein’s overall efficiency and metabolism.

7.  

    ![The unmodified sequence in Mol\*. Shows two hydrogen bonds in blue
    dashes between HIS 176 and ASP 149.](images/unmodified_2h.png)

8.  

    ![The modified and mimic sequence files from AlphaFold3 superimposed
    in Mol\*. The image focuses on the singular hydrogen bond between
    HIS 176 and ASP 149.](images/structure_1h.png)

When looking at other amino acids sites related to substrate binding,
additional sites appeared to have the same interactions that they did
with HIS 176 both in the unmodified structure and variant structures. In
Image 9, it can be seen that with the unmodified and variant structures
superimposed there is still a consistent interaction between ARG 86 and
HIS 176. In Image 10, it can be seen that with the unmodified and
variant structures superimposed there is still hydrogen bonding
occurring between ASN 121 and HIS 176. While Figure 4 and 5 do not show
a change in structure due to the variant structures it is important to
note their consistency to understand which interactions near the
substrate binding site are disrupted due to the modification.

9.  

    ![An image of amino acid 176 and 86 with the unmodified file, mimic
    AlphaFold3 file, mimic Boltz file, and modified AlphaFold3 model
    superimposed in Mol\*. The image focuses on the interaction between
    HIS 176 and ARG 86.](images/interaction_superpose.png)

10. 

    ![An image of amino acid 176 and 121 with the unmodified file, mimic
    AlphaFold3 file, mimic Boltz file, and modified AlphaFold3 model
    superimposed in Mol\*. The image focuses on the interaction between
    HIS 176 and ASN 121.](images/asn_121.png)

From the mimic variant, the most notable structural shift was the change
at amino acid site 133 of Lysine to Glutamine. This change in amino acid
caused the functional group of the Lysine to be lost in the shift from
Lysine to Glutamine. At site 133 comparing the Boltz mimic structure
with the Colab mimic structure, similarity was seen. Even after
simulation, the Glutamine identity at site 133 remained (Image 11). When
looking at the effects of dynamics in key sites within the protein both
before and after modification differences were observed. At residue 176,
there was a slightly higher RMSF value seen in the mimic RMSF chart in
comparison to the unmodified RMSF chart. While the two RMSF charts are
on different scales with the mimic RMSF scale measuring up to 2.5 and
unmodified RMSF scale measuring up to 3.0, the mimic RMSF scale still
shows HIS 176 having a slightly elevated RMSF value in comparison to the
unmodified RMSF scale. Residue 86 was also noted to have an elevated
RMSF value in the mimic RMSF chart as opposed to the unmodified RMSF
chart. Both of these sites having elevated RMSF values indicates that
the mimic variant increased flexibility in the respective amino acids
sites.

11. 

    ![An image of Mol\* at site 133 showing the mimic Boltz and Colab
    structures superimposed with one another.](images/boltz_colab.png)

Along with analyzing the RMSF charts for changes in dynamics after
variant changes, it was also analyzed how the pKa values changed with
the variant sequence compared to the unmodified sequence. The pKa value
at amino acid site 133 was not found for the mimic sequence as Colab
would not generate a pKa value for the site. The Colab would not
generate a pKa value for the site given that the Glutamine of site 133
in the mimic variant did not have a functional group which meant it
could not be deprotonated. While amino acid 133 did not have a pKa value
for analysis, both sites 167 and 176 did have changes in their pKa
values. In the unmodified structure, site 167 had a pKa value of 12.77
and site 176 had a pKa value of 4.35. In the mimic variant, site 167 had
a pKa value of 13.09 and site 176 had a pKa value of 4.23. At site 176
there was a decrease in pKa value with the mimic variant. This decrease
in pKa value indicates that the histidine with modification is more
likely to be deprotonated. The increased chance of deprotonation could
take effects such as potential loss of hydrogen bonding at the site. The
increase in pKa value at site 167 with the mimic variant indicates that
the site is more likely to be protonated. This increase is beneficial to
the overall protein as it could gain more stabilizing interactions for
the site which could compensate for the loss in stabilizing forces with
a decrease in pKa value at site 176.

## Authors

Vanessa George

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

-   Minárik, P.; Tomásková, N.; Kollárová, M.; Antalík, M. Malate
    Dehydrogenases--Structure and Function. Gen Physiol Biophys 2002, 21
    (3), 257–265. [12537350](http://www.gpb.sav.sk/2002_03_257.pdf)

-   Kufareva, I.; Abagyan, R. Methods of Protein Structure Comparison.
    In Homology Modeling; Orry, A. J. W., Abagyan, R., Eds.; Humana
    Press: Totowa, NJ, 2011; Vol. 857, pp 231–257.
    [10.1007/978-1-61779-588-6_10](https://doi.org/10.1007/978-1-61779-588-6_10)

-   Molinié, T.; Cougouilles, E.; David, C.; Cahoreau, E.; Portais,
    J.-C.; Mourier, A. MDH2 Produced OAA Is a Metabolic Switch Rewiring
    the Fuelling of Respiratory Chain and TCA Cycle. Biochim Biophys
    Acta Bioenerg 2022, 1863 (3), 148532.
    [10.1016/j.bbabio.2022.148532](https://doi.org/10.1016/j.bbabio.2022.148532)

-   Li, H.; Cui, X.; Wu, W.; Yu, F.; Yao, H.; Liu, Q.; Song, E.;
    Chen, J. Pyk2 and Src Mediate Signaling to CCL18‐Induced Breast
    Cancer Metastasis. J of Cellular Biochemistry 2014, 115 (3),
    596–603. [10.1002/jcb.24697](https://doi.org/10.1002/jcb.24697.)

-   Bubber, P.; Haroutunian, V.; Fisch, G.; Blass, J. P.; Gibson, G. E.
    Mitochondrial Abnormalities in Alzheimer Brain: Mechanistic
    Implications. Annals of Neurology 2005, 57 (5), 695–703.
    [10.1002/ana.20474](https://doi.org/10.1002/ana.20474)
