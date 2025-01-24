# human MDH2
# Uniprot ID: P40926
# Variation: Phosphorylation of S317


## Description

1. image of the unmodified site
![Unmodification site alignment within MDH2](images/unmodified.png)

2. image of modification site
![Modification site alignment within MDH2](images/modified.png)

Comparison of MDH2 models and phosphomodified MDH2

Serine 317 of MDH2 plays an essential role in the enzyme’s overall function due to its position on the protein’s surface, making it accessible for interactions with molecules such as ADP-ribose.¹ This has been supported by large-scale data and research showing that S317 is involved in ADP-ribosylation, a modification where an ADP-ribose molecule attaches to S317.¹ Previous studies support the idea that S317 has at least a minimal influence on MDH2’s function and its ability to interact with other proteins.  

Regarding S317’s position relative to substrate binding sites and the dimer interface, it is located near both but is not directly involved in either dimerization or substrate binding. The potential disruption of weak interactions, such as hydrogen bonding, is a possible consequence of alterations to S317. This could impair MDH2’s ability to function effectively or change how it interacts with other proteins.  

While evidence of S317 has been studied broadly, it is still unclear what modifications of this site specifically do to MDH2’s metabolic roles. However, there is evidence that alterations to S317 can have subtle effects while MDH2’s core function remains largely maintained overall.¹ 
In the MDH2 model used in Project 2, S317 formed hydrogen bonds with both Glu 313 and Ile 320. When phosphorylated, a new weak hydrogen bond with Pro 321 is formed. Similarly, the mimic variant, which replaces Ser 317 with Asp 317, also forms a weak hydrogen bond with Pro 321. While these changes may result in smaller alterations to the protein's structure, it is worth noting that even the most minor weak interactions can play a role in maintaining the protein’s stability and function.  


## Effect of the sequence variant and PTM on MDH dynamics

3. image of aligned PDB files
![Image of aligned PDB files](images/aligned.pdb.file.png)

4. image of the site with the aligned PDB files
![Weak interactions from the unmodified (purple), variant (blue), and PTM-modified (orange) models](images/weakinteractions_all3.png)

The molecular dynamics simulations revealed significant structural changes in the protein in the presence of the mimic aspartic acid (D). The RMSD graph further explains these structural changes, demonstrating how the protein’s structure evolves throughout the simulation. 
Initially, the Root Mean Square Deviation (RMSD) starts off with a large increase, which is indicative of large conformational changes in the protein. Over time, the RMSD continues to increase but at a much slower rate. This implies that the protein is reaching closer to a stable conformation relative to the start of the simulation. However, since the RMSD does not fully equilibrate, it is likely that the protein structure hasn’t completely stabilized by the end of the simulation. This suggests that the mimic influenced the protein’s structure, perhaps changing its flexibility, which, in turn, could affect its function.

The Root Mean Square Fluctuation is a good indicator of how the residues fluctuates. Based on the plot, there is a significant initial drop in the RMSF value from around 10 to approximately 1. This sharp decrease suggests that the protein underwent early conformation changes, which were likely induced by the mimic. Additionally, perhaps a structural alteration had stabilized some regions of the protein when the mimic was introduced. 

5. Annotated RMSF plot showing differences between the simulations
![RMSF plot showing the fluctuation of residues during simulation. The x-axis represents amino acid residues, while the y-axis reflects the RMSF value](images/rmsf_plot.png)

Between residues 15 and 325, the protein dynamics appear more stable, as the RMSF fluctuates minimally, shifting from low changes between rising and falling. This indicates that the protein begins to reach a more stable conformation when compared to when the mimic was first introduced. 

At around residue 350, there is a spike in RMSF, implying a conformational alteration occurred. However, this area is interestingly not associated with the substrate binding or active sites. With these key sites not having significant fluctuations, it can be suggested that the protein’s key functions remain relatively intact. Overall, the mimic caused initial structural disruptions based on the RMSF graph, suggesting that stabilization was maintained based on this measurement. 

6. Table showing pKa differences for the key amino acids
![Table showing the pKa values of multiple binding sites and the active site](images/pka.png)

Key sites include the active site amino acids or substrate-binding amino acids.  The pKa values at such places show significant fluctuations in response to the mimic, which suggests that the environment around these sites changes during simulation. These changes indicate how the ionization states may influence the protein’s stability, ultimately impacting how it interacts with other molecules.

For binding sites 31 to 37, specifically residues 26 to 45 in the table, the mean of pKa values drops from 10.47 to 7.17. This suggests that these residues became more acidic during simulation, which could make them less likely to be protonated in a more acidic environment. The pKa mean at residue 56 was 11.29 but dropped to 4.45 at residue 57, a binding substrate site. This large change could indicate that this region becomes much more acidic during the simulation. Between residues 94 and 104, the pKa values shift from 4.27 to 12.01, suggesting that the protein undergoes a major shift in the ionization state. Specifically, it becomes more basic, perhaps indicating that the mimic has induced a conformational change at site 104 (another binding site). Between site 110 (a binding site) and residue 111, the pKa mean changes from 12.41 to 2.96. This means there is an increase in acidity. Between residues 112 to 128, the pKa mean increases from 2.58 to 17.03, indicating that the region becomes more basic. Site 117, which is another binding site, is between these two residues. Between residues 173 to 183, the pKa values fluctuate from 4.3 to 10.95 and then back to 3.89, suggesting a shift from acidic to neutral states. This region could be highly sensitive to changes in the protein’s environment, perhaps due to the mimic’s binding. At the active site, residue 200 shows a pKa of 5.30, suggesting a moderately acidic environment. At nearby residues, the pKa values were slightly more basic than this.

Based on these pKa changes, there is support that the mimic significantly alters the electrostatic environment of the protein’s active and binding shifts. Shifts towards acidity could indicate a disruption in the protein’s conformation, while basic shifts may indicate conformational stabilization. 

Overall, according to the graphs and pKa table, the mimic variant induces structural changes but stabilizes certain regions in other forms of measurements, particularly around functional sites. In the RMSD graph, it can be seen that there are initial conformational changes that slow down, indicating that the protein gradually stabilizes over time. Similarly, the RMSF displays similar trends where certain regions stabilize after initial fluctuations. At the same time, pKa values are changed significantly, especially around the binding sites, reflecting changes in the electrostatic environment of the protein.

7. Annotated plots of pKa for the key amino acids
![pKa values of active site histidine with only minor differences in the spread of data over the simulation](images/His.png)


## Comparison of the mimic and the authentic PTM

The mimic variant and PTM-modified model both show similarities and differences between each other. Post-translational modifications (PTMs) are known to influence protein function by altering structure and residue interactions, which is somewhat evident in the PTM-modified model but at a low degree. For example, slight variations in amino acid positions appeared after the increased exposure of SEP 317 on the protein’s surface, which may have displayed changes in the accessibility of the protein to other molecules. However, the mimic resulted in a more dramatic alteration in conformation, followed by a gradually incomplete stabilization. 

While the mimic variant is not a perfect representation of the PTM-modified model, it does exhibit trends similar to those seen in the PTM, such as hydrogen bonding patterns with the same amino acids as each other. This suggests that the mimic variant can serve as a helpful model for studying PTM's effects. However, it does remain an imperfect approximation due to differences in the extent and nature of the structural changes. Plus, the simulation gives specific data such as RMSD, RMSF, and pKa values and trends of the mimic variant rather than the PTM-modified model. The next step to see how well they match would be having the PTM undergo the same simulation to compare the values the mimic variant resulted in. 


## Authors

Riley Clanton

## 12/06/2024

## License

Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg


## References

* Kuhn, M. L.; Rakus, J. F.; Quenet, D. Acetylation, ADP-Ribosylation and Methylation of Malate Dehydrogenase. Essays in Biochemistry 2024, 68 (2), 199–212.![10.1042/EBC20230080](https://doi.org/10.1042/EBC20230080)

* Pillai, S.; Gopalan, V.; Smith, R. A.; Lam, A. K.-Y. Updates on the Genetics and the Clinical Impacts on Phaeochromocytoma and Paraganglioma in the New Era. Critical Reviews in Oncology/Hematology 2016, 100, 190–208.![10.1016/j.critrevonc.2016.01.022](https://doi.org/10.1016/j.critrevonc.2016.01.022)
