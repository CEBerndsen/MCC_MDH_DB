---
editor_options: 
  markdown: 
    wrap: 72
---

# MDH2

# P40926

# Acetylation of 203K

## Description

# This project analyzes the post-translational modification site at amino acid 203K within MDH2. An acetyl group was added which altered the structure and function of the protein. Using Uniprot, this modification site was studied before, but no literature was found on it to describe its effects.

1.  image of the unmodified site ![Unmodified structure from Alphafold3
    depicting LYS179 within an alpha helix and no hydrogen
    bonds](images/UNMODLYS179.png)

2.  image of modification site ![Modified structure depicting ALY179 in
    an alpha helix hydrogen bonded to
    GLN207](images/MODALY179_GLN207.png)

## Effect of the sequence variant and PTM on MDH dynamics

Part 3 from the Project 4 report

1.  Image of aligned PDB files (no solvent) ![Mimic and unmodified
    structures superimposed in Mol\*](images/MIM&UNMOD.png)

2.  Image of the site with the aligned PDB files (no solvent) ![Modified
    and unmodified structures superimposed in
    Mol\*](images/MOD&UNMOD.png)

3.  Annotated RMSF plot showing differences between the simulations
    ![RMSF plot from Colab2 of Project 4 (left), RMSF plot from Colab2
    of Project 2 (right)](images/RMSFplotcomparison.png)

4.  Annotated plots of pKa for the key amino acids ![pKa of HIS176 shown
    at 4.62](images/HIS176pka.png)

5.  If needed, show ligand bound images and how modification affects
    substrate binding ![HIS176 (active site) has a cation-pi interaction
    with ARG86 in the unmodified structure, two hydrogen bonds with
    ASP149, and one hydrogen bond with ASN121](images/UNMODHIS176.png)
    ![HIS176 (active site) in the mimic structure has a cation-pi
    interaction with ARG86, two hydrogen bonds with ASP149, and one
    hydrogen bond with ASN121](images/MIMHIS176.png) ![HIS176 (active
    site) in the modified structure hydrogen bonded to ASP149 and
    ASN12](images/MODHIS176.png) Description of the data and changes

Images are shown of the unmodified, mimic, and modified structures alone
as well as superimposed. The modified variant altered the weak
interactions with other residues as well as the weak interactions of the
active site. All modification sites are seen within alpha helices on the
outside of the structure away from the dimer interface. The mimic and
unmodified structures were very similar, but found some functional
alterations with the mimic decreasing enzyme activity and increasing
movement. The acetylation of 203K overall is predicted to decrease
enzyme activity as it altered enzyme activity which can affect metabolic
pathways.

## Comparison of the mimic and the authentic PTM

![Mimic and modified structures superimposed in
Mol\*](images/MIM&MOD.png) Part 4 from the Project 4 report outline
include images as needed

Although the major increase in RMSF values and increase in pKa values
found in the mimic simulations suggest a decrease in enzyme activity and
stability, it fails to indicate the differences in interactions. The
modified model introduced a new hydrogen bond between ALY179 and GLN207
which also caused the active site, HIS176, to lose its cation-pi bond
with ARG86. This new hydrogen bond stabilizes the protein's structure
differently from the mimic which does not have a hydrogen bond.

### Colab notebook links

Provide file names of completed colab notebooks

Copy_of_MD_simulation_Step1v2(1).ipynb

Copy_of_MDanalysis_Step2.ipynb

## Authors

Natalie Murphy

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

-   Chapman, A. D. M., Cortés, A., Dafforn, T. R., Clarke, A. R., &
    Brady, R. L. (1999). Structural basis of substrate specificity in
    malate dehydrogenases: Crystal structure of a ternary complex of
    porcine cytoplasmic malate dehydrogenase, α-ketomalonate and
    tetrahydronicotinamide. Journal of Molecular Biology, 285(2),
    703–712.![10.1006/jmbi.1998.2357](https://doi.org/10.1006/jmbi.1998.2357)
-   Christopher E. Berndsen, Jessica K. Bell; The structural biology and
    dynamics of malate dehydrogenases. Essays Biochem 3 October 2024; 68
    (2):
    57–72.![10.1042/EBC20230082](https://doi.org/10.1042/EBC20230082)
-   Lisa M. Baird, Christopher E. Berndsen, Jonathan D. Monroe; Malate
    dehydrogenase in plants: evolution, structure, and a myriad of
    functions. Essays Biochem 3 October 2024; 68 (2):
    221–233.![10.1042/EBC20230089](https://doi.org/10.1042/EBC20230089)
-   Kuhn, M. L., Rakus, J. F., & Quenet, D. (2024). Acetylation,
    ADP-ribosylation and methylation of malate dehydrogenase. Essays in
    Biochemistry, 68(2),
    199–212.![10.1042/EBC20230080](https://doi.org/10.1042/EBC20230080)
-   Zhang, Y., Zhang, Y., & Zhang, Y. (2017). Studying the lysine
    acetylation of malate dehydrogenase. Journal of Molecular
    Biology.![10.1016/j.jmb.2017.03.027](https://doi.org/10.1016/j.jmb.2017.03.027)
