# Human Malate Dehydrogenase 1
# P40925
# phosphorylation of S153 (pS152 in structure)


## Description
This study explores variations of human malate dehydrogenase 1 (MDH1) and the phosphorylation of the amino acid at position 153.  The unmodified structure of MDH1 refers to position 153 while the position of the PTM modified and mimic variant is at position 152.  The amino acid at position 153 within the unmodified MDH1 is a serine. Serine is a part of a beta-sheet making up the structure of MDH1.  Although the unmodified MDH1 has no weak interactions across its dimer interface, amino acid 152 forms hydrogen bonds between an oxygen bond and nitrogen bonds on His252 (helix) and Val127 (sheet) respectively.  The serine also forms a hydrogen bond with an oxygen molecule on Val125 (sheet) from nitrogen and a hydrogen bond with a sulfur molecule of Cys136 (helix) from oxygen. 
The PTM-modified structure references the phosphorylation of serine, which becomes a phosphoserine (SEP).  Although there are no weak interactions across the dimer interface, SEP forms 3 additional bonds compared to its unmodified version.  The phosphoserine has an additional two bonds with the residue of Val125 (sheet) and His252 (helix) in addition to a hydrogen bond between the oxygen in SEP and a sulfur molecule of Met268, a part of an alpha helix. 
The variant structure of MDH1 underwent a point mutation where the serine was changed to an aspartic acid.  There are no weak interactions across the dimer interface, but formed are the same hydrogen bonds to the residues of the original structure.  The bonds within the variant and modified structure do not interact with the active site of MDH, histidine 187, but changes can contribute to effects on protein folding and stability.  The aggregation and degradation of the structure can ultimately reduce the overall effectiveness of the enzyme.

# Part 1 from Project 4 report outline (with citations as appropriate)

1. image of all aligned 
![Aligned structures of unmodified, PTM modified, and variant structures](images/align_all.png)

2. image of SER152 unmodified 
![Serine at position 152, unmodified structure. ](images/serine152.png)

3. image of position 152 aligned
![Position 152 in unmodified, PTM modified, and variant structures](images/align_site_152.png)

4. image of active site HIS187 unmodified 
![Active site His187 in unmodified structure](images/align_active_site_187.png)




## Effect of the sequence variant and PTM on MDH dynamics



1. RMSF plot

![Root mean standard fluctuation (RMSF) plot displaying specific amino acids.  Indicating amino acids that determine the secondary structure of the PTM and mimic variant.  A comparison of specific amino acid dynamics in a protein.  RMSF value increases with the movement of amino acids and indicates the individual residue flexibility and the movement (fluctuation) during a simulation.](images/RSMF.png)

2. ![SER187](images/SER187.png)

3. ![LYS109](images/LYS109.png)

4. ![MET95](images/MET95.png) 

Description of the data and changes
The modification of site 152 leads to deviations across the protein, with high RMSF values indicating high degrees of flexibility or mobility; often seen in loop and more unstructured regions.  Low RMSF values indicate greater stability; as seen in stable secondary structures (alpha helices or beta sheets).  An elevated RMSF value at the active site of MDH1, Ser187, indicates a slight impact on the flexibility of the structure.  This elevation could be due to weak interactions between residues close to the binding sites of MDH1. The negative charge of the phosphate group on the serine can induce conformational changes in the protein, affective stability, folding, and binding capabilities represented by peaks and elevation in the RMSF values.  The bulky phosphate group of the serine increases the steric bulk of the residue leading to interferences with nearby residues and structural changes.  

At the active site, SER187, the slight peak in RMSF value represents the bonds to loop and helix structures.  The PTM and mimic variant have the same bonds from SER187 and have varying RMSF levels making both stable and unstable between residues.  The identical bonding displays a match between the two different structures of MDH1.

A low RMSF value at residue 109, a lysine (LYS109), indicates greater stability between secondary structures.  The PTM (purple) and mimic variant (green) have hydrogen bonds between LYS109 and a residue on another helix (ALA333 and LEU330).  A bond between 2 rigid structures, alpha-helices are more stable.

A large peak in RMSF value at residue 95, a methionine (MET95), indicates low stability and higher flexibility within the structure.  The PTM and mimic variant have hydrogen bonds between MET95 and arginine at residue 92 (ARG92).  The bond is within a loop structure; a region of irregular or variable geometry compared to alpha-helices and beta-sheets.

5. pKa values over time 
![Predicted pKa values of reside 152 over time (frames)](images/pKa_line.png)

6. Box Plot of pKa values 
![Box plot of predicted pKa values of site 152, connecting residues, and the active site of MDH1.](images/pKa_box_plot.png)

Description of pKa values 
The changes in pKa are indicative of various things within the structure over time.  Conformational fluctuations occur with the changes in the local electrostatic environment around ionizable residues leading to changes in pKa.  A higher pKa, around 7.0 and above, means that the residue is more likely to remain acidic and in its protonated form.  Any change in pKa could correlate with the dynamics observed in the RMSF plot.  Such shifts could provide insights into the protonation state of the residue or indicate changes in the local environment, potentially signaling an environment-induced gain or loss of a proton.  The phosphorylation of serine could have altered the local environment of amino acids making it more or less likely to participate in hydrogen bonding or enzyme catalysis. 
Figure 5a. displays fluctuations in pKa at a 0.8-point difference ranging from around 12.5 and 13.3.  The pKa values are considered high, indicating that the residue is more likely to be in a deprotonated state at physiological conditions, pH ~ 7.4.  A high pKa can lead to implications for charge distribution, protein stability, and active site function.  The initial drop and peak at 13.2 pKa represent the system stabilizing followed by another drop and a slight plateau.  The graph displays the most fluctuation between the time 18t and 25t representing the flexibility and variability of residue 152.  The phosphate group attached to the serine holds a negative charge and creates a highly polar environment around the residue.  The phosphoserine would have caused this increase in pKa due to the electron-withdrawing effects of the phosphate group and a pKa of around 13 for serine.  
Figure 5b. is a box plot of the predicted pKa values at site 152, other amino acids involved in substrate binding, and amino acids at the active site.  Residue 152, a phosphoserine has the lowest pKa value, ~4, which is due to the negative charge of the phosphate group.  The phosphate group could have changed the protonation states of compared residues within MDH1.  Similarly, residues 186 and 252 have low pKa values being both histidines.  Histidines typically have a pKa of around 6, but due to the phosphorylated serine, its values have decreased slightly, disregarding outliers.  The negative charge of the phosphate group could have pulled the electron density away from the histidine side chain ultimately making it more likely to be deprotonated, lowering the pKa value.  Comparatively, residue 136, a cystine has a relatively high pKa making it more likely to stay protonated at a higher pH.  The cysteine may be located ina tight active site pocket making it more difficult to access water.  The thiol group becomes more acidic and it results in a higher pKa.  


## Comparison of the mimic and the authentic PTM

1. Image of RMSD
![Root mean square deviation (RMSD) of malate dehydrogenase 1 comparing the PTM (phosphoserine, SEP152) and mimic variant (aspartic acid, Asp152).](images/RMSD_line.png)

2. Image of RMSD Heatmap
![Heatmap of RMSD values specifying positions within the frames of the  PTM and mimic variant of MDH1.](images/RMSD_heatmap.png)

Description of data
The RMSD displays the differences in positioning of two structures, in this case the protein conformations of the PTM and mimic variant of MDH1.  The graph displays a visualization of the structural changes over time and the differences between models.  The graph starts at 0 indicating the structure analyzed aligns with the initial confirmation of MDH1.  At around 0.0025 there is a drastic jump to an RMSD value of 1.41indicating a structural adjustment in the system. A drop in RMSD value indicates the normalizing of stability within the structure which continues with slight raises and drops in the range of 0.9 and 1.2.  This fluctuation can indicate the flexibility of regions within the structure in addition to conformational changes between states.  As time continues there is a sudden jump and drop indicating instability of the protein or a new conformation such as a ligand bond of a correct protein fold.  Following this, there is a plateau in the RMSD value within a 0.2 range (1.4-1.6).  The stabilization indicates structural equilibrium or convergence and the system is no longer undergoing large changes.
The heatmap visually represents the root mean square deviation between the PTM and mimic variant structures.  Individual cells within the heatmap represent the conformations of the protein structures at a certain point in time (frame).  The blue represents a low RMSD value indicating a high structural similarity.  The blue is on a gradient moving to green and then yellow representing a high RMSD value and indicating significant structural differences.  The diagonal line is a comparison of each superposed structure to itself indicating a perfect match and an RMSD value of 0; there are no structural deviations from itself.  At 0 frames, there is a high RMSD value and strong deviations representing the initial jump within the preceding graph.  There is a sudden change from low to high RMSD values, an indication the transition between two conformational states.  Frames 3 to 14  and 13 to 24 display a blue-to-green box, a time of equilibrium although there are slight raises and drops in RMSD values.  The two clusters of lower RMSD values are an indication that the system underwent a transition between two stable states.  The structure of the PTM and mimic variant do not affect the active site a 187, but the conformational changes can impact substrate binding sites and their ability to catalyze reactions.  Additionally, there are recurring yellow cells within the heatmap representing that the system revisits similar conformations over time.  
The high deviations within the protein structures can lead to loss of regulation in its metabolic pathways, impaired enzyme activity, and overall imbalance. 

## Authors

Claire Lee

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

* Rowlands, C. F.; Taylor, A.; Rice, G. I.; Whiffin, N.; Hildegard Nikki Hall; Newman, W. G.; Black, G.; O’Keefe, R. T.; Hubbard, S. J.; Andrew G.L. Douglas; Baralle, D.; Briggs, T. A.; Ellingford, J. M. MRSD: A Quantitative Approach for Assessing Suitability of RNA-Seq in the Investigation of Mis-Splicing in Mendelian Disease. American Journal of Human Genetics 2022, 109 (2), 210–222. ![10.1016](https://doi.org/10.1016/j.ajhg.2021.12.014.)

* RMSD/RMSF Analysis | BioChemCoRe 2018. ctlee.github.io.  !(https://ctlee.github.io/BioChemCoRe-2018/rmsd-rmsf/.)

*8.3: pKa Values. Chemistry LibreTexts. !(https://chem.libretexts.org/Courses/Purdue/Chem_26505%3A_Organic_Chemistry_I_(Lipton)/Chapter_8._Acid-Base_Reactions/8.3%3A_pKa_Values.)


[def]: Images/RMSF.png