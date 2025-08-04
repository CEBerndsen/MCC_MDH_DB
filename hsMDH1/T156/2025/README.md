# Homo sapiens MDH1

# Uniprot ID: P40925

# Variation: phosphorylation of T156

## Description

The modification site observed in this project is at position 156 in the amino acid sequence. Since predictions were made using the processed amino acid sequence, I will refer to the substitution site at position 155 instead of 156 throughout this paper due to this processed sequence having one less amino acid than the full-length sequence. To create the mimic variant, aspartic acid was substituted in for threonine. The modified sequence had a phosphothreonine post-translational modification. This modification has not been described or researched previously. The location of this modification is located on a loop. This modification is relatively close to the active site and even bonds to the Histidine 186 in the active site only in the modified structure. The amino acids that interact at the 156 site in the unmodified structure are SER 286, CYS 153, and HIS 159. In the mimic variant the amino acids that interact at that position are CYS 153 and ASN 160. Finally, the amino acids that interact at that position in the modified sequence are LEU 154, ASP 158, and HIS 186.

# Part 1 from Project 4 report outline (with citations as appropriate)

1.  Image of unmodified site ![position 155 in the unmodified structure](unmod_site/.png)

2.  Image of modification site ![position 155 in the modified structure](mod_site/.png)

3.  Image of variant site ![position 155 in the variant structure](mimic_site/.png)

## Effect of the sequence variant and PTM on MDH dynamics

Looking at the position of the specific amino acid change that was made in the mimic sequence (Threonine being replaced with Aspartic acid) compared to the unmodified sequence, the amino acid, THR 155, in the unmodified sequence yielded more hydrogen bonds to surrounding amino acids including 286, CYS 153, and HIS 159. The difference between Threonine and Aspartic acid is that Threonine is a polar amino acid that contains a hydroxyl group, and Aspartic acid contains a carboxyl group (Ahern & Tan, 2024). Threonine is more likely to yield more hydrogen bonds due to the presence of the hydroxyl group while aspartic acid can still form hydrogen bonds with its carboxyl group, but the need of a hydrogen donor needs to be present making it less likely (Ahern et al., 2024).

Reduced hydrogen bonding in the mimic sequence can lead to less mechanism activity. Substrates can then be built up and less product is produced which disrupts metabolic equilibrium. Some examples of affected organelles and cell type are the mitochondria and the liver. If the mitochondria are involved in oxidative phosphorylation, with the imbalance, ATP production may be impaired. As for the liver, disrupted enzymatic control could impact things like lipid processing.

At position 155 in the unmodified sequence, there is the amino acid THR. For the modified sequence, TPO 155 is present. The post transitional modification was a phosphorylation of threonine. This is the transferring of the phosphate group of ATP to threonine (Pang et al., 2022). This ultimately changes the hydroxyl side chain into a bulky, negatively charged phosphate group.

TPO 155 in the modified structure has more hydrogen bonds compared to THR 155. These extra hydrogen bonds are seen at the amino acid LEU 154, and two hydrogen bonds each at both HIS 186 and ASP 158 positions. More amounts of hydrogen bonds at this loop position can hinder or enhance substrate binding. More hydrogen binding can mean greater stability and supports the reaction, or it can make this position rigid and inhibit the reaction due to necessary movement not able to occur.

Part 3 from the Project 4 report

1.  Image of aligned PDB files (no solvent) ![alignment of the unmodified, modified, and mimic structures](align/.png)

2.  Image of the site with the aligned PDB files (no solvent)

Alignment of the unmodified and mimic structures in the active site ![Aligned structures in mol\*](images/activesite_um&mimic.png)

Alignment of the unmodified and mimic structures in the modification site ![Aligned structures in mol\*](images/modsite_um&mimic.png)

Alignment of the unmodified and modified structures in the active site ![Aligned structures in mol\*](images/activesite_um&mod.png)

Alignment of the unmodified and mimic structures in the modification site ![Aligned structures in mol\*](images/modsite_um&mimic.png)

3.  Annotated RMSF plot showing differences between the simulations ![RMSF plot for unmodified structure](images/RMSF-Unmod.png) ![RMSF plot for variant structure](images/RMSF-Mimic.png)

4.  Annotated plots of pKa for the key amino acids ![pKa comparison plot at key sites](images/pKa-Boxplot.png) ![pKa for amino acid 186 in unmodified structure](images/pKa186-unmod.png) ![pKa for amino acid 186 in variant structure](images/pka186-mimic.png)

Description of the data and changes The amino acid sequence of the variant was run through an MDAnalysis package, generating RMSD, RMSR, and pKa results. The root mean square deviation (RMSD) is the measure of how much a structure changes over time. Even though the unmodified structure is shown to have more hydrogen bonds which can provide stability and less change overtime, the plot shows an increase of RMSD overtime (Figure 6). This could be due to the protein having more conformational changes to be able to bind to substrates. More hydrogen bonds can provide a stable core of the protein but allow the flexible regions to move without changing the whole protein. Another reason for these results could be the flexible regions such as loops are moving. The RMSD plot of the mimic sequence shows a constant RMSD plot overtime (Figure 7). A constant RMSD can indicate that the structure is not moving much during the simulation and may be losing key interactions in order for catalysis to happen.

The root mean square fluctuation (RMSF) measures the flexibility of a specific residue overtime; it highlights which amino acids in a protein move the most (Lee, 2018). The amino acid at position 100 is relatively near a loop as well as at position 205. These residues can help bind or release substrates. Finally, position 245 is not on a loop which means it presents significant movement unexpectedly. Compared to the unmodified structure, the mimic sequence has higher flexibility and more regions. With this substitution, regions that were once rigid have seemed to be flexible.

In the mimic structure, different residues have different pKa values. The substitution site at position 155 shows the lowest pKa value meaning its most stable. At position 161, the most extreme pKa value is seen. Finally, at position 186, shows an instable pKa value as well proving that the mimic structure disrupts its usual behavior. Looking deeper into the pKa graph fluctuations in the active site of the modified and mimic structures at specially HIS 186, after simulations in Colab 2, the unmodified structure shows that the pKa ranges enforce a fairly stable environment surrounding HIS 186 to help maintain the pronation state of residues (Figure 11). In the mimic structure, there is shown to be a broader range of pKa values with more frequent spikes (Figure 12). These fluctuations may indicate that there is more instability, or dynamic interactions that may be occurring around HIS 186 therefore affecting its role in catalysis. This more basic environment may encourage deprotonation and affect the proton transfer to malate in the MDH reaction mechanism impairing the enzyme function.

## Comparison of the mimic and the authentic PTM

Alignment of the modified and mimic structures in the modification site ![Aligned structures in mol\*](images/modsite_mod&mimic.png)

Part 4 from the Project 4 report outline include images as needed

### Colab notebook links

Provide file names of completed colab notebooks

Copy_of_MD_simulation_Step1v2.ipynb Copy_of_MDanalysis_Step2.ipynb

## Authors

Contributors names: Sophia Verrecchia

## Deposition Date

## License

Shield: [![CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/).

[![CC BY-NC 4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)

## References

-   Citation1 ![DOI:10.1371/journal.pone.0083091](DOI%20link:https://doi.org/10.1371/journal.pone.0083091)

-   Citation2 ![DOI:10.1021/acsomega.1c04385](DOI%20link:https://doi.org/10.1021/acsomega.1c04385)

-   Citation2 ![DOI:10.1002/mco2.175](DOI%20link:https://doi.org/10.1002/mco2.175)
