---
editor_options: 
  markdown: 
    wrap: 72
---

# Malate Dehydrogenase 1 (MDH1)

# Uniprot ID: P40925

# Variation: phosphorylation of S123

## Description

Serine 123 of human MDH1 was identified as a post-translationally
modified (PTM) site in several large-scale PTM studies, including
UniProt entry P40926 (1). With this being said, there is limited direct
evidence on how this modification affects the MDH1 structure or
function. S123 is located in a loop region near the protein surface, but
not within the active site.

# Part 1 from Project 4 report outline (with citations as appropriate)

1.  Overview image of unmodified MDH1 ![Overview image of unmodified
    MDH1](images/unmodified.png)

2.  Image of modification site on unmodified MDH1 ![Image of
    modification site on unmodified
    model](images/modification_site_hmdh1.png)

3.  Image of modification site on variant model ![Image of modification
    site on variant model](images/variant.png)

4.  Image of modification site on PTM model ![Image of modification site
    on PTM model](images/PTM.png)

## Effect of the sequence variant and PTM on MDH dynamics

Part 3 from the Project 4 report

1.  Overview aligned image of MDH1, pS123, and S123D ![Image of overview
    aligned image of all three models](images/aligned.png)

2.  Modification site alignment within MDH1 ![Image of modification site
    alignment within MDH1](images/aligned_site.png)

3.  RMSF plots showing differences between the simulations ![RMSF plot
    of variant](images/rmsf_plot.png) ![RMSF plot of unmodified
    MDH1](images/rmsf_plot_unmod.png)

4.  Image of pKa plot for the key active site HIS187 ![pKa plot for the
    key active site HIS187](images/HIS187pKa.png)

Description of the data and changes

The pS123 in human MDH1 introduced a bulky, negatively charged phosphate
group that formed strong electrostatic interactions with the lysines
nearby. This helped stabilize the surrounding loop and reduce its
flexibility. The S123D variant increased loop mobility due to the weaker
interactions. The MD Google Colab Steps (2) confirmed greater
flexibility in the variant, as well as reduced pKa for the active site
histidine.

## Comparison of the mimic and the authentic PTM

While both pS123 and S123D introduced a negative charge at the same
location, their structural and dynamic consequences differed. The PTM
created a stronger interaction network and more rigid conformation due
to the phosphate's charge and size. The variant replicated some of these
aspects but lacked the interaction network and steric effects, making it
a partial and imperfect substitute.

### Colab notebook links

[MD Colab 1]
(<https://jmuedu-my.sharepoint.com/:u:/r/personal/berndsce_jmu_edu/Documents/Work/Teaching/CHEM260L/Sp2025/lecture_data/Individual%20project%20data/Robertson_R/data/colab_1/MD_simulation_Step1v2.ipynb?csf=1&web=1&e=IY4Tb4>)

[MD Colab 2]
([https://jmuedu-my.sharepoint.com/:u:/r/personal/berndsce_jmu_edu/Documents/Work/Teaching/CHEM260L/Sp2025/lecture_data/Individual%20project%20data/Robertson_R/data/colab_2/MDanalysis_Step2.ipynb%20(5_4_25)?csf=1&web=1&e=gGeMNo](https://jmuedu-my.sharepoint.com/:u:/r/personal/berndsce_jmu_edu/Documents/Work/Teaching/CHEM260L/Sp2025/lecture_data/Individual%20project%20data/Robertson_R/data/colab_2/MDanalysis_Step2.ipynb%20(5_4_25)?csf=1&web=1&e=gGeMNo){.uri})

## Authors

Rory Robertson

## Deposition Date

05/07/2025

## License

Shield: [![CC BY-NC
4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

This work is licensed under a [Creative Commons
Attribution-NonCommercial 4.0 International
License](https://creativecommons.org/licenses/by-nc/4.0/).

[![CC BY-NC
4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)

## References

1.  UniProt. UniProt: P40925 – Malate dehydrogenase, cytoplasmic.
    UniProt. (<https://www.uniprot.org/uniprotkb/P40925/entry>.)
2.  Google. Google Colaboratory. Google.com.
    (<https://colab.research.google.com/>.)
