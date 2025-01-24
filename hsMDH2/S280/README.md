#Homo sapiens MDH2
#Uniprot ID:P40926
#Variation:phosphorylation of S280 (pS255 in structure)


## Description

Serine 280 of human MDH2 was identified at the post-translation modification site of phosphoserine 255. No previous studies outline the effect of this change in the protein, but certain amino acids involved in the site are changed from the original protein when phosphorylated. What has been identified is a shift in the amino acids with the unmodified version of the protein being at amino acid 256 while the modified version and variant version of the protein are at amino acid 255. This seems to represent a deletion mutation of the site that we are trying to modify.*Entry started on 12/5/2024*
 

1.![Unmodified site of Serine 280 with the green molecule in the middle of the image representing the site that is attached to the amino acids via hydrogen bonds](images/Unmodified.png)

2.![The PTM mimic of unmodified site serine 280; now Asparagine 255;showing the amino acids involved with the Asp 255.](images/PTM_mimic_site.png)


## Effect of the sequence variant and PTM on MDH dynamics

The pKa values of the PTM value seem to be higher with it stabilizing around 3 while the unmodified protein seems to stabilize around 1.1.In regards to the RMSF values the areas of higher flexibility seem to be moving from the 80 range of the unmodified protein to the 300 range in the protein mimic. All in all the PTM mimic shows little change in the structure with varying pKa and RMSF values being slightly variable from the unmodified protein.In addition the clashing ligands are being seen in the PTM mimic which involves the enzyme not being able to bind to certain spots because they are being occupied by another enzyme affecting the function of the protein.(https://doi.org/10.3390/biom12091175)

1.![Depiction of the site of modification on all protein models being aligned together.](images/Aligned.png)

2.![RMSF plot of the PTM mimic in which fluctuations are seen more around 300 amino acids then the original 80 amino acids in the unmodified RMSD.](images/RMSF_plot.png)

3.
![pKa values for an amino acid 601 in the PTM mimic of MDH2;601 was used in this study because no relevant amino acids where concluded in the simulation.](images/pKa_PTM_mimic.png)

4.![Depicts unmodified, modified, and PTM mimic of MDH2 clashing ligands.](images/superposed_ligands.png)

Since this modification and variation is not close to the active site or a binding site associated with the active site the protein is still able to participate in the Krebs cycle and produce oxaloacetate and NADH like the unmodified protein. In the active site of MDH2 all three versions of the proteins have all the same amino acids interacting with the Histidine with the exception of the Histidine being one amino acid back due to the deletion mutation. This deletion also seems to cause in the modified enzyme of MDH2 a change in the amino acid Asparagine to Arginine. This could have some effects for the active site by affecting what the active site can bind too because of arginine being positively charged and polar. 

## Comparison of the mimic and the authentic PTM
When looking at the PTM mimic in comparison to the modified protein they both have similar structures with the exception of the PTM mimic variant in having Asp 261 instead of the Thr 261 as seen in the modified protein structure this substitution of an amino acid can cause for the negatively charged aspartic acid to change the charges of several amino acids in the protein structure which would affect the function of the protein. Another piece of evidence that suggests that the PTM mimic variant is a good model for the modified protein is that when superposed together they have a RMSD of 1.45 which suggests that they have a similar structure due to it being a lower RMSD value.

![PTM mimic and modified protein aligned at the modification site. ](images/Aligned_PTM_mimic_and_modified.png)


## Authors

Jasmine Finch

## Deposition Date
12/6/2024
## License

Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg


## References

![https://doi.org/10.3390/biom12091175](2.Eo, Y.; Duong, M.T.H.; Ahn, H.-C. Structural Comparison of hMDH2 Complexed with Natural Substrates and Cofactors: The Importance of Phosphate Binding for Active Conformation and Catalysis. Biomolecules 2022, 12, 1175. https://doi.org/10.3390/biom12091175)