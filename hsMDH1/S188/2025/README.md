# Human MDH1
# Uniprot ID: P40925
# Variation: phosphorylation of S188 (pS188 in structure)


## Description

# Part 1 from Project 4 report outline (with citations as appropriate)
Malate dehydrogenase (MDH) is an essential enzyme that plays a key role in cellular energy production. Found in nearly all living organisms, including humans, MDH catalyzes the reversible conversion of malate to oxaloacetate using the coenzyme NAD⁺/NADH. This reaction is a part of the citric acid cycle (also known as the Krebs cycle or TCA cycle), which is crucial for aerobic respiration and ATP generation in cells. In humans, there are two main isoforms of malate dehydrogenase: the mitochondrial isoform (MDH2) and the cytosolic isoform (MDH1). MDH2 is located in the mitochondria and functions in the citric acid cycle, helping to regenerate oxaloacetate for continuous cycle turnover. MDH1, on the other hand, participates in the malate-aspartate shuttle, a process that transfers reducing equivalents from NADH in the cytosol into the mitochondria. This shuttle is particularly important in tissues with high energy demands, such as the heart and brain. Structurally, MDH functions as a dimer and has a well-defined active site where malate binds. The enzyme is highly conserved and exhibits a classic Rossmann fold that accommodates the NAD⁺ coenzyme. Its activity is influenced by substrate concentrations, pH, and the availability of cofactors.
Overall, malate dehydrogenase is not only vital for energy metabolism but also serves as a model for studying enzyme kinetics and regulation. Its function illustrates the elegant balance of biochemical pathways that sustain cellular life.


1. image of the unmodified site
![Unmodified structure Ser188](images/modified_site.png)

2. image of modification site
![alt text](images/modification_site.png)


## Effect of the sequence variant and PTM on MDH dynamics
This Mol* visualization compares the mimic variant and the PTM-modified MDH1 structures at residue 188. In the mimic model, SER 188 is replaced by aspartate to simulate the negative charge of phosphorylation, while the PTM model contains a phosphorylated serine. The overlay shows that both residues adopt similar positions and side-chain orientations, but the PTM-modified residue carries a larger, tetrahedral phosphate group. Despite these differences, the surrounding backbone structure remains consistent. This suggests that while both modifications introduce similar electrostatic effects, the PTM may create slightly more steric bulk and potential for extended hydrogen bonding.


Part 3 from the Project 4 report

1. Image of aligned PDB files (no solvent)
![Aligned PDB file MDH1 models superposed](images/aligned_PDB.png)

2. Image of the site with the aligned PDB files (no solvent)
![SER188 site comparison across all three models. Unmodified, mimic, and modified](images/modified_mimic.png) ![SER188 site comparison across all three models.](images/originial_mimic) !SER188 site comparison across all three models.](images/original_modified)

3. Annotated RMSF plot showing differences between the simulations
![RMSF plot for the mimic protein](images/rmsf_plot.png)

4. Annotated plots of pKa for the key amino acids
![Boxplot of pKa values HIS 187, ASP159, ARG162, and SER188 in MDH1 from project 3, unmodified MDH1] (images/boxplot.png)

5. If needed, show ligand bound images and how modification affects substrate binding
In the updated MDH1 structure, Asp188 is seen making several polar connections in the active site area. The Mol* visualization reveals a series of dashed lines linking the aspartate side chain to nearby residues and the attached ligand, hinting at possible hydrogen bonds. These connections are facilitated by the negatively charged carboxyl group that comes from the mutation. The surrounding structure looks neat and compact, indicating that Asp188 helps stabilize the active site of the modified protein


Description of the data and changes
Structural changes in the modified and mimic models were explored using Mol*. In the modified structure (Figure 5), Asp188 forms several new polar interactions, indicated by dashed lines, suggesting increased hydrogen bonding capacity. These interactions involve nearby residues and the bound ligand, indicating that the mutation could influence local ligand stabilization. When compared to the unmodified structure (Figure 6), the side chain change from serine to aspartate does not affect the backbone alignment or surrounding secondary structures, confirming that the mutation’s effects are local rather than global.
Introducing a negative charge near the active site through mutation or modification at residue 188 may affect the binding of MDH1 to NAD⁺ or malate. Although residue 188 is not directly involved in catalysis, changes in the local electrostatics could influence the orientation of substrate-binding loops or adjacent active site residues. If the binding of the ligand is either stabilized or altered, this may slow down or modify the efficiency of the conversion from malate to oxaloacetate. In a broader metabolic framework, such modifications could impact the malate-aspartate shuttle, thereby affecting the transfer of NADH into the mitochondria. This is particularly significant for tissues with high energy requirements, such as the heart, brain, and skeletal muscle, where maintaining the NAD⁺/NADH balance is essential for ATP production. While the overall protein folding remains unaffected, even minor local changes at or near the active site can significantly influence enzyme efficiency and the cellular energy equilibrium.



## Comparison of the mimic and the authentic PTM
The mimic variant (S188) exhibits a comparable pattern (Figure 7), with aspartate establishing more polar interactions than the original serine. While the charged carboxyl group of aspartate simulates the electrostatic characteristics of a phosphorylated serine, it does not possess the complete steric volume and geometry of a phosphate group. This is illustrated in the comparison between the mimic and the PTM-modified model (Figure 8), where both occupy similar positions; however, the PTM features a larger tetrahedral group that allows for extended hydrogen bonding. Consequently, the mimic variant captures the electrostatic influences of phosphorylation but fails to entirely replicate the steric or bonding capabilities of the genuine PTM. Thus, it functions as a partially accurate representation.
The mimic variant (S188) exhibits a comparable pattern (Figure 7), with aspartate establishing more polar interactions than the original serine. While the charged carboxyl group of aspartate simulates the electrostatic characteristics of a phosphorylated serine, it does not possess the complete steric volume and geometry of a phosphate group. This is illustrated in the comparison between the mimic and the PTM-modified model (Figure 8), where both occupy similar positions; however, the PTM features a larger tetrahedral group that allows for extended hydrogen bonding. Consequently, the mimic variant captures the electrostatic influences of phosphorylation but fails to entirely replicate the steric or bonding capabilities of the genuine PTM. Thus, it functions as a partially accurate representation.



Part 4 from the Project 4 report outline
include images as needed


### Colab notebook links

Provide file names of completed colab notebooks



## Authors

Tina Aziz

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

* Berndsen CE, Bell JK. The structural biology and dynamics of malate dehydrogenases. Essays Biochem. 2024 Oct 3;68(2):57-72.![10.1042/EBC20230082](https://doi.org/10.1042/EBC20230082)

* MDH1 malate dehydrogenase 1 [Homo sapiens (Human)]—Gene—NCBI (https://www.ncbi.nlm.nih.gov/gene?Db=gene&Cmd=DetailsSearch&Term=4190)
