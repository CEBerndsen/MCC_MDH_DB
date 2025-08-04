# Homosapiens MDH1

# P40925

# Phosphorylaration of S152

## Malate Dehydrogenase (MDH) is an enzyme involved in cellular respiration across all domains of life (Fraizer et al. 2024). A reaction of the MDH cycle is the catalyzation between malate and oxaloacetate using NAD+ as a cofactor (Alburto-Rodriguez et al. 2016). In eukaryotic cells there are two different types of isozymes MDH1, and MDH2. MDH1 is found in the cytoplasm and participates in the malate/aspartate shuttle which transfers NADH equivalents into the mitochondria and could then be used as oxidative phosphorylation. MDH2 is found in the mitochondria which directly involved the Krebs Cycle.

In this project, each of us was assigned a specific post-translational modification (PTM) to Malate Dehydrogenase 1 (MDH1) in order to predict its structural and functional effects. My assigned residue was Serine 153 but due to the processed amino acid sequence being shorter than the full length, the amino acid I will be referring to is Serine 152. To create the mimic variant, Serine at position 152 was substituted with Aspartic Acid 152. This amino acid substitution was modeled using AlphaFold3 by first downloading both the original, unmodified MDH1 sequence and the new mimic-modified sequence. The mimic modified sequence, containing the Serine to Aspartic Acid change at position 152, was then ran through Boltz-1 to assess potential structural and functional impacts.

1.  image of the unmodified site [Position 152 in the unmodified model](images/unmodified%20Screenshot%202025.png)

2.  image of modification site [Position 152 in the modified model](images/modified%20Screenshot%202025.png)

## Effect of the sequence variant and PTM on MDH dynamics

Structural comparisons of the unmodified (original), modified (SER152), and mimic (ASP152) all had only small minor changes as the RMSD among all three models contained a value under 0.21. The mimic is also not positioned near the active site since the important catalytic residue, Histidine 186, is located pretty far away. The amino acids that interacted with my amino acid site ASP 152 were as hydrogen bonding Histidine 252, Cystine 136, Valine 127 and Valine 125 in the modified, variant, and unmodified state.

1.  Image of aligned PDB files (no solvent)

[Superposed 3D structure of unmodified, modified SER 152, and mimic ASP 152](images/All%203%20models%20superimposed%20Screenshot.png)

2.  Image of the site with the aligned PDB files (no solvent)

[Superposed close of residue 152 of unmodified, modified SER 152, and mimic ASP 152](images/all%203%20superposed%20at%20amino%20acid%20152%20Screenshot.png)

[Superimposed 3D structure of the amino acid Serine 152 with the mimic structure shown in green, and the modified structure shown in pink.] (images/Mimic X processed Screenshot 2025-05-06.png)

[Superimposed 3D structure of the amino acid Serine 152 with the mimic structure shown as green and the original structure from project 2 shown in pink.](images/Mimic%20X%20original%20Screenshot%202025-05-06.png)

[Superimposed 3D structure of the amino acid modified structure shown as pink while the original structure from project 2 is shown as green.] (images/Mimic X processed Screenshot 2025-05-06.png)

3.  Annotated RMSF plot showing differences between the simulations

[RSMF plot of the unmodified model] (images/RMSF_plot.png)

[RSMF plot of mimic structure](images/RMSF%20plotScreenshot%202025-05-06.png)

4.  Annotated plots of pKa for the key amino acids [Box plot of predicted aka values for residues ASP 152, ARG 161, and HIS 186 in mimic MD simulation as ARG 161 shows low variation while the others show variation.] (images/Box Plot Screenshot 2025-05-06.png)

[pKa fluctuation plot for HIS 186 in ASP 152 mimic model with pKa values ranging between 3.0-4.5 that were possibly altered by the environment.](images/PKA%20graph%20Screenshot%202025-05-06.png)

[pKa fluctuations for HIS 186 in the unmodified model where the graph shows fluctuations between 5.5 and 6.7 and is relatively stable.] (images/pKaplot_Histidine186.png)

The data set includes structural models of MDH1 in different forms being the unmodified original from project 2, the modified structure, and the mimic structure.The RMSD value of the mimic with the unmodified original was the same, 0.21, while the RMSD of the unmodified original with the modified was 0.15. All models were all relatively similar with the one that they were superimposed with. Both RSMF plots show similar patterns for both the mimic and the unmodified structures. The RSMF for the mimic ASP 152 is \~0.5-0.7. The mimic model of ASP 152 shows flexibility is many regions and suggests that the possible Serine to Aspartic Acid substitution caused a dynamic change in motion. RMSF values of the modified model shows greater fluctuations mostly between \~0.5-1.5 and shows relatively high flexibility.

## Comparison of the mimic and the authentic PTM

The structure compression between the mimic ASP 152 and the authentic PTM SER152 showed large similarities. One key difference was the loss of a bond at my modified residue 152. In the original structure, SER152 formed a hydrogen bond with HIS 252 that was not present in the mimic. Although the overall RMSD between the structures was 0.21, which was relatively low, meaning there were no big changes, this small change suggests that the substitution may have possibly altered a sidechain which somewhat disrupted the interaction.

### Colab notebook links

Copy of MD_simulation_Step1v2

Copy of MDanalysis_Step2-2

## Authors

Danielle Shahin

05/07/2025

## License

Shield: [![CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/).

[![CC BY-NC 4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)

## References

-   Takahashi-Íñiguez, T., Aburto-Rodríguez, N., Vilchis-González, A. L., & Flores, M. E. (2016). Function, kinetic properties, crystallization, and regulation of microbial malate dehydrogenase. Journal of Zhejiang University - Science B, 17(4), 247–261. [10.1631/jzus.B1500219](https://doi.org/10.1631/jzus.B1500219)

-   Wolyniak, M. J., Frazier, R. H., Gemborys, P. K., & Loehr, H. E. (2024). Malate dehydrogenase: A story of diverse evolutionary radiation. Essays in Biochemistry, 68(2), 213–220. [10.1042/EBC20230076](https://doi.org/10.1042/EBC20230076)
