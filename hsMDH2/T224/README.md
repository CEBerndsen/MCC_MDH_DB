# Homo sapien malate dehydrogenase 2 (MDH2)
# P40926
# Phosphorylation of THR224 (TPO200 in modified structure/ASP200 in PTM mimic)


## Description

After ommitting transit peptides, THR 224 is renumbered as THR 200. The post translational modification (PTM) at the site is phosphorylation. Structural analysis shows that threonine 200 lies within an α-helix, 18.62 Å from the active site and 16.09 Å from the substrate binding site. In the phosphorylated enzyme, threonine 200 does not form hydrogen bonds with other residues. A phosphorylation PTM at this site has not been described previously.

1. image of the unmodified site
![In the unmodified enzyme (green), THR200 forms two hydrogen bonds with GLN196.](images/unmodified_site.png)

2. image of modification site
![In the modified enzyme (purple), THR200 is phosphorylated (TPO200) and does not establish any hydrogen bonds with other residues.](images/modification_site.png)


## Effect of the sequence variant and PTM on MDH dynamics

Part 3 from the Project 4 report

1. Image of aligned PDB files
![Superposed image of the modified enzyme (pink and purple) and the MD PTM mimic model (brownish yellow).](images/aligned_PTM_and_colab.png)

2. Image of the site with the aligned PDB files
![Superposed image of the modified enzyme (purple) and the MD PTM mimic model (brownish yellow) at the active site. At the active site, in the modified protein, HIS 176 forms a weak interaction with ASP 149, whereas in both monomers of the Colab model, HIS forms a hydrogen bond with ASN.](images/aligned_PTM_and_colab_at_active_site.png)

3. Image of the substrate binding site with the aligned PDB files
![Superposed image of the modified enzyme (purple) and the MD PTM mimic model (brownish yellow) at the substrate binding site. In the modified model, ARG 152 interacts with HIS 46, while in the Colab model, ARG forms interactions with both ASP and HIS in both monomers.](images/aligned_PTM_and_colab_at_binding_site.png)

4. Annotated RMSF plot showing differences between the simulations
![The plot displays the differences between the RMSF values of the PTM mimic (blue) and the RMSF values of the unmodified model (orange)](images/RMSF_compare.png)

5. Annotated plots of pKa for the key amino acids
![The plot displays the differences between the pKa values at the key amino acids. The active sites are HIS 176 and 490. The substrate binding sites are ARG 152 and ARG 466. There are two of each sites due to the numbering scheme used by Colab.](images/pKa_plot_for_key_aa.png)



## Comparison of the mimic and the authentic PTM

While the overall structures of the MD PTM mimic (Colab) and the modified model align well, discrepancies in the weak interactions highlight the need for a more detailed analysis to fully capture the structural implications of the modification. 

Notably, the MD PTM mimic (Colab) model does not fully reflect the changes at both the active site and substrate binding site seen in the PTM mimic. However, when viewed from a broader perspective, focusing on the overall protein structure rather than individual interactions, the mimic variant provides a reasonable approximation of the PTM modification, particularly in terms of its functional effects.


## Authors

Laura Phan

## Deposition Date
December 6, 2024

## License

Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg


## References

(1) “18.1: Properties of Amino Acids.” Chemistry LibreTexts, 17 July 2014, chem.libretexts.org/Bookshelves/Introductory_Chemistry/Basics_of_General_Organic_and_Biological_Chemistry_(Ball_et_al.)/18%3A_Amino_Acids_Proteins_and_Enzymes/18.01%3A_Properties_of_Amino_Acids.

(2) “AlphaFold Server.” Alphafoldserver.com, alphafoldserver.com/.

(3) Habets, G.G.M, et al. “Sublocalization of an Invasion-Inducing Locus and Other Genes on Human Chromosome 7.” Cytogenetic and Genome Research, vol. 60, no. 3-4, 1 Jan. 1992, pp. 200–205, https://doi.org/10.1159/000133336. Accessed 6 Dec. 2024.

(4) Ma, Jennifer C., and Dennis A. Dougherty. “The Cation−π Interaction.” Chemical Reviews, vol. 97, no. 5, 1 Aug. 1997, pp. 1303–1324, https://doi.org/10.1021/cr9603744.

(5) “Mol* Viewer.” Molstar.org, molstar.org/viewer/.

(6) “UniProt.” Uniprot.org, 2024, www.uniprot.org/uniprotkb/P40926/entry#disease_variants.
