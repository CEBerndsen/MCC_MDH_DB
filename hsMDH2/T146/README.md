# Human Malate Dehydrogenase
# Uniprot: P40926
# Variation: phosphorylation of T146


## Description

Human MDH2 sequence was changed at threonine 146 to aspartic acid in addition to a phosphorylation PTM. There are no functional studies on this site, structural and functional changes were explored. 

1. image of the unmodified site
![This is Threonine 146 in the unmodified sequence of MDH2](images/unmodifiedchangesite.png)

2. image of modification site
![This is phosphorylated threonine 146. It shares bonds with glycine 144 (white arrow) and aspartic acid 149 (purple arrow) like the unmodified sequence however it also forms weak interactions with serine 265 (not shown, represented by yellow circle), and valine 172 (black arrow).](images/PTMchangesite.png)


## The phosphorylation of threonine introduces a negative charge to the amino acid affecting the bonds it makes, in this case allowing for four additional hydrogen bonds. 


1. Image of aligned PDB files (no solvent)
![This shows the mimic variant and the unmodified MDH2 strucure superimposed.](images/alignedpdb.png)

2. Image of the site with the aligned PDB files (no solvent)
![this image shows the modification site of the superimposed mimic variant and unmodified MDH2.](images/mimicandunmodsuperimposed.png)

3. Annotated RMSF plot showing differences between the simulations
![The RMSF plot provides insights into the flexibility and dynamics of protein residues. Higher RMSF values indicate greater flexibility. In this comparison, the mimic variant, left plot, exhibits increased flexibility in specific regions, particularly around residues 300 and 600.](images/rmsf_plot.png)

4. Annotated plots of pKa for the key amino acids
![The higher pKa values in the mimic variant indicate a reduced tendency for protonation at physiological pH. This can affect the charge state of the residues, which can influence their interactions with other residues, substrates, or cofactors. The pKa shift can directly affect the catalytic activity of the enzyme by altering the ability of key residues to participate in proton transfer reactions or to stabilize reaction intermediates.](images/mimicpKaplot.png)


## Comparison of the mimic and the authentic PTM
![The PTM, with a higher RMSD, shows significant structural differences, particularly around the phosphorylation site. The PTM variant and mimic variant were also superimposed and yielded a RMSD value of 1.27 indicating they are not structurally similar. The phosphate group in the PTM introduces additional hydrogen bonds and electrostatic interactions, leading to significant structural changes. These differences could impact the protein's function and stability.](images/mimicandPTMsuperimposed.png)

While the mimic variant provides an approximation of the PTM, it is not the best representation as the structures have significant differences. The differences in the hydrogen bonding like the PTM having several more bonds, intermolecular interactions, and potential conformational changes between the two modifications can lead to significant functional differences.


## Authors

Mackenzie Kidwell

## Deposition Date

## License

Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg


## References

*  Kozeleková, A.; Náplavová, A.; Brom, T.; Gašparik, N.; Šimek, J.; Houser, J.; Hritz, J. Phosphorylated and Phosphomimicking Variants May Differ-a Case Study of 14-3-3 Protein. ![PMC8935074](https://www.sciencedirect.com/topics/medicine-and-dentistry/malate-dehydrogenase)


