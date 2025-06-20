---
editor_options: 
  markdown: 
    wrap: 72
---

# Homo sapiens and hMDH2

# P40926

# pS51

## Description

Mitochondrial malate dehydrogenase (MDH2) is a mitochondrial enzyme that plays an important role in the tricarboxylic acid (TCA) cycle, also known as the Krebs cycle. MDH2 does this by catalyzing the oxidation of malate to oxaloacetate using nicotinamide adenine dinucleotide (NAD+), which is a helper molecule that helps transfer energy from one molecule to another. This helps maintain the cycle?s efficiency by generating ATP and linking glycolysis to oxidative phosphorylation. According to UniProt, MDH2 is localized in the mitochondrial matrix and is involved in key metabolic processes such as aerobic respiration. This specific mitochondrial enzyme is a homodimer which means two identical protein subunits come together to form the active enzyme. Each of these subunits binds to the cofactor NAD+, and this specifically helps in the transfer of electrons talked about previously- from malate to oxaloacetate. This structure allows MDH2 to have several important binding sites for NAD+, to ensure the cycle runs smoothly. These binding sites play a key role in keeping the balance of the metabolic activity. Modifications such as phosphorylation, can help adjust MDH2?s activity, and this helps optimize its function under specific conditions. Mutations of MDH2 significantly alter mitochondrial function, and have been found to implicate many pathological conditions/metabolic imbalances. The structure of MDH2 is important in its ability to catalyze reactions, bind to ligands, and covert substrates. To further understand MDH2?s role in metabolism and its regulation through post-translational modifications, it is essential to examine whether the phosphorylation of serine51 affects MDH2?s enzymatic activity, stability, or interactions.?

1.  image of the unmodified site ![Unmodified Site of
    MDH2](images/unmodified.png)

2.  image of modification site ![Phosphorylated Site of
    MDH2](images/modified.png)

3 \## Effect of the sequence variant and PTM on MDH dynamics

To model and analyze the post-translational modification at Serine27 of
MDH2 tools such as AlphaFold3 and Mol\* were used for direct line
structure inspection, and to observe the interactions between amino
acids. The unmodified version of the AlphaFold3 model shows serine at
amino acid 27 and having weak hydrogen bonding interactions with ALA1,
and ALA52. When this is phosphorylated it is observed that there are
weak interactions between serine27 (p) and ALA1, ALA52, and now a new
interaction: ARG28. This suggests that the phosphorylation could have
induced charge shifts and structure changes in MDH2. In the mimic, when
we changed the serine to aspartic acid (D), using AlphaFold, it
maintained the same weak interactions with the addition of LYS50. LYS50
formed a new hydrogen bond with ASP27 and the rest of the environment
remains unchanged in terms of direct bonding. This addition of a
hydrogen bond, introduces a new additional double bonded oxygen in the
form of a carbonyl group that was not present in serine. This allows for
more potential for hydrogen bonding and basic residue interactions such
as LYS50.

These changes in weak interactions, while subtle, may have functional
consequences for MDH2. The differences in bonding between the three
models - unmodified, phosphorylated, and mimic - suggests that Ser27
could play a role in manipulating NAD+ binding flexibility and dynamics.
A more rigid loop, that is created by the new interaction (LYS50) in the
mimic model, may interfere with the MDH2 catabolic activity and/or how
quickly NAD+ binds. To understand these predicted structural changes,
root-mean-square deviation (RSMD) plots were generated to compare the
different variations in Mol\*.

1.  image of the processed sequence ![Ser27 in processed sequence with
    bonds](images/SER27.png)

2.  image of the phosphorylated sequence ![Ser27 in phosphorylated
    sequence with bonds](images/SER27phosphorylated.png)

3.  image of the mimic sequence ![ASP27 in mimic sequence with
    bonds](images/ASP27mimic.png)

4.  Annotated RMSF plot showing differences between the simulations
    ![The RMSF graph displays how much motion each amino acid has during
    simulation - it specifies the movement of each residue during
    simulation](images/RMSFplot.png)

5.  Annotated RMSD plot showing differences between the simulations
    ![The RMSD graph gives a sense of whether the protein has reached a
    fixed state over the simulation in
    GoogleColab.](images/RMSDplot.png)

6.  Annotated plots of pKa for the key amino acids ![pKa of original and
    mimic](images/pKadata.png)

Additionally, in the mimic model, a cation-pi interaction was observed
between ARG86 and HIS176. This interaction was not shown in the original
MDH2 sequence or the phosphorylated sequence, which supports the idea
that the specific S27D mutation caused a unique shift in MDH2. Since
HIS176 is the specific active site of MDH2, this new interaction could
significantly contribute to the protein stability and the functional
regions. His176 is a key part in the catalytic reaction of MDH2 and the
direct conversion of malate to oxaloacetate. The formation of this new
cation-pi bond could alter the position and orientation of HIS176 during
catalysis. Both of these observations are beneficial to our research,
because one shows the loss of a stabilizing interaction near the active
site and the other shows the formation of a new one (specifically in the
variant). This proves that even at a distance the modification at Ser27
effect?s MDH2 throughout the whole sequence.?

```         
The changes to the structure of MDH2 have consequences on the broader metabolic pathways it participates in - such as the TCA cycle. The structural alterations near Ser27, phosphorylated or mimic, have been shown to impact the NADH binding and potentially reposition active site residues such as HIS176. If these changes impair MDH2?s catalytic process, the production of oxaloacetate can slow and affect the following steps of the TCA cycle. In humans, MDH2 activity could decline and result in energy deficits because of the loss of ATP synthesis. 
```

7.  Cation-Pi interaction ![The Cation-Pi Interaction shown between Arg
    86 and His176 in mimic model](images/cationpibondinmimic.png)

## Comparison of the mimic and the authentic PTM

Lastly, a direct comparison between the PTM-modified MDH2 model and the
mimic was superimposed in Mol\* and the model revealed that the biggest
change between the two was specifically the hydrogen bond the mimic
formed at LYS50. Both of the modifications had a new charge at Ser27,
and both of them formed new interactions. The phosphorylated model
formed a hydrogen bond between Ser27 and Arg28 and the mimic formed a
hydrogen bond with Lys50. These changes show that the environment from
the original NAD+ binding loop changed with both shifts in the
sequence.? Based on all of our comparisons above as well, we found that
the mimic variant is not a great representation of the PTM. Although the
mimic tried to replicate some of the electrostatic aspects of the
phosphorylation model it has vastly different bonding patterns and the
shifts throughout the sequence are affected by the different amino acids
and phosphorylation.?

1.  image of the mimic and modified model ![A superimposed image of the
    mimic variant and modified model](images/mimicandPTM.png)

## Authors

Chloe Jackson

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

-   The UniProt Consortium , UniProt: the Universal Protein
    Knowledgebase in 2025, Nucleic Acids Research, Volume 53, Issue D1,
    6 January 2025, Pages
    D609?D617![DOI](https://doi.org/10.1093/nar/gkae1010)
