# Human malate dehydrogenase 1

# Uniprot ID: P40925
# Variation: phosphorylation of Y278



## Description

The altered amino acid was located at the base 278 on a loop. The phosphorylation of Tyr 278, the threonine (THR) changed to aspartic acid (ASP). Neither the Original, mimic, or PTM was close to the dimer interface, the binding sites, or the active site (HIS 187).All formed weak interactions with ASN 276 and ARG 310. Those however was the only bond that the mimic had. The Original and the PTM had the almost the same weak interactions, with the extra being Val 300 and Leu 303. The phosphorylation of TYR 278 however substituted the pi bond it had with TRP 184 in place of an H-bond with SER277

1. image of the unmodified site
![The TYR at the 278 position with the amino acids that bond with it labled](images/TYR278.png)

2. image of modification site
![The Mimic of TYR 278, ASP and the amino acids that bond with it labeled](images/ASP278.png) ![The phosphorylated TYR 278 and the amino acids that bond with it labeled](images/PTM.png)


## Effect of the sequence variant and PTM on MDH dynamics

1. Image of aligned PDB files (no solvent)
![The superimposed image of the Original, mimic, and PTM variants. All together, the RMSD came out to 0.26 which tells us that the structures are really similar](images/UnmoddedPDB.png)

2. Image of the site with the aligned PDB files (no solvent)
![The superimposed image of the Original, mimic, and PTM variants. This time with just at the site 278.](images/UnmoddedSite.png)

3. Annotated RMSF plot showing differences between the simulations
![The RMSF plots for the protein, blue is the original, orange is the mimic, and green is the PTM. The plots share a lot of traits which makes it easy to tell that despite the changes in the site, the amount of movement that happened in the protein was fairly stable](images/RMSF.png)

4. Annotated plots of pKa for the key amino acids
![The pka plots for the protein, blue is the original, orange is the mimic, and green is the PTM. The original was more consistent in its alternation from the protonated to deprotonated state which allowed for more consistent binding patterns. The mimic on the other hnd was mainly in the deprotonated stat making its binding patterns harder to predict. The same can be generally said for the PTM but it still showed more properties of the original as in seeing a dip past 100 for the protonated state](images/HIS187PKA.png)


## Comparison of the mimic and the authentic PTM

![Looking at the rmsf data, it showed similar patterns to that of the aforementioned original and mimic, this makes sense as the PTM is just an addition of a phosphate group on the original. This is not to say that there are not any changes, like around the position 278, the PTM shows more activity than normal. This is probably due to the changing of bonds (switched the pi bond of TRP 184 on the original with an H-bond on the SER 277)](images/RMSF.png)

![pka plot](images/HIS187PKA.png)

## Authors

Kwabena S. Mantey

## Deposition Date
12/06/2024

## License

Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg


## References

*  AlphaFold Server. (https://alphafoldserver.com/)

*  McCue, W. M.; Finzel, B. C. Structural Characterization of the Human Cytosolic Malate Dehydrogenase I. ACS Omega 2021, 7 (1), 207–214. (https://doi.org/10.1021/acsomega.1c04385)

* MolViewer. molstar.org. (https://molstar.org/viewer/.)

* Eun Kyung Kim; Won Ho Kim; Kang, H.; Jeong Hun Kim; Chung, S. J.; Seo, Y.-S.; Sung Sup Park; Sang Yup Lee; Bae, K.-H. Acetylation of Malate Dehydrogenase 1 Promotes Adipogenic Differentiation via Activating Its Enzymatic Activity. ScienceDirect 2012, 53 (9), 1864–1876. (https://doi.org/10.1194/jlr.m026567)

* Laura de Lorenzo; Stack, Tyler M. M.; Fox, K.; Walstrom, K. Catalytic Mechanism and Kinetics of Malate Dehydrogenase. Essays in biochemistry 2024. (https://doi.org/10.1042/ebc20230086)

* UniProt. Uniprot.org. (https://www.uniprot.org/uniprotkb/P40925/entry#ptm_processing)
