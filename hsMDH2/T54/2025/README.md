# Human MDH2

# Uniprot number: P40926

# Variation: Phosphorylation at 54

## Description

Malate dehydrogenase (MDH) is a central enzyme in cellular metabolism. It is a catalyst in the reversible NAD-dependent reduction of L-malate to oxaloacetate, which is part of the Kreb Cycle. MDH has a variety of properties, which lead to it having different structures under different conditions. [^readme_template_human_mdh2_p54--1] MDH plays a key part in the mitochondrial membrane and in the tricarboxylic acid cycle within the mitochondrial matrix. MDH2 in humans has an active site at HIS 176 and when introduced to variants can cause diseases. [^readme_template_human_mdh2_p54--2] The modification that I received was a phosphorylation at number 54. This changed the original processed sequence at site 30.

[^readme_template_human_mdh2_p54--1]: De Lorenzo L, Stack TMM, Fox KM, Walstrom KM. Catalytic mechanism and kinetics of malate dehydrogenase. Essays Biochem. 2024 Oct 3;68(2):73-82.![10.1042/EBC20230086](DOI:%2010.1042/EBC20230086)

[^readme_template_human_mdh2_p54--2]: Uniprot. Uniprot.!(<https://www.uniprot.org/uniprotkb/P40926/entry>)

![The unmodified enzyme seen at site 30 with all of it's weak interactions](images/unmod.png) ![The unmodified enzyme in light green at HIS 176, the active site](images/active_site_compare.png)

![This is the modified enzyme at site 30 where there is now TPO 30 instead of THR 30.](images/modified.png)

## Effect of the sequence variant and PTM on MDH dynamics

![Unmodified MDH2 on the left in light green and Modified enzyme on the right in purple at site 30. Weak interactions labeled. They both have hydrogen bonding between their amino acids at site 30 and CYS 65, VAL 3, and VAL 5.](images/unmod_mod_compare.png)

![Unmodified MDH2 on the left in light green and mimic variant on the right in dark green at site 30. Weak interactions labeled. They both have hydrogen bonding between their amino acids at site 30 and Val 3 and Val 5](images/unmod_mimic_compare.png)

![RMSF data from project 2 MDH2 unmodified processed sequence on the left and RMSF data from colab 2 of this project with the mimic variant from AlphaFill on the right.The unmodified enzyme (left image) had a larger range as it was from about 0.8-4. In the RMSF data plot for the mimic variant (right image) the range is about 0.25-2.4. The mimic variant range being smaller than the unmodified enzyme RMSF range indicates less flexible and dynamic regions in the mimic variant enzyme.](images/rmsf_compare.png)

![pKa trends in the amino acid HIS 176. The MDH2 unmodified processed sequence from project 2 on the left and the mimic variant from colab 2 of this project on the right. The unmodified enzyme stays at a pKa of about 4-5 with some slight variations, most likely deprotonated. The mimic variant’s pKa seems to stay under 5 for the majority which means that it is deprotonated for the most part.](images/pka_compare.png)

## Comparison of the mimic and the authentic PTM

![The PTM modified sequence and mimic variant superimposed in molstar to show the differences at site 30. Weak interactions shown and labeled. They both have hydrogen bonding between their amino acids at site 30 and ARG 28, VAL 3, and VAL 5. Differences in their weak interactions are seen with the PTM modified enzyme’s TPO 30 bonding with CYS 65 and TYR 56, when the mimic variant’s ASP 30 doesn’t bond with either of those amino acids.](images/mod_mimic_compare_30.png)

## Authors

Ellie Pezzella

## Deposition Date

## License

Shield: [![CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/).

[![CC BY-NC 4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)

## References
