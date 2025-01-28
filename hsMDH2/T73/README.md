# Human Mitochondrial MDH2

# Uniprot ID: P40926
# Variation: phosphorylation of T73 (pT49 in structure)



## Description

Threonine 73 of Human MDH2 was phosphorylated to TPO 73, and substitued for aspartic acid (D316) in another sequence in order to create a mimic variant. The modified amino acid is in a loop segment in between a alpha helix and beta sheet and is very close to the dimeric interface.  It is far from all active and binding sites.  All three models of MDH2 have hydrogen bonding from residue 73(49) to LYS 45(21) and ILE 71(47).  However, the residue at 73 in the phosphoT73 model has an additional two interactions connecting itself to ASN 46(22) and LYS 74(50). 

# Comparison of MDH2 models and phospho modified MDH2

1. Alignment of MDH2(Yellow), MDH2 with phosphoT 73(Red), and T73D(Blue)
<img width="400" alt="align" src="https://github.com/user-attachments/assets/2b341f32-4d44-43d8-bd29-752a12ffd125">

The RMSD values between the original MDH2 and the mimic MDH2 was 0.25Å; the original MDH2 and phosphoT73 MDH2 was 1.39Å.

2. Representation of Active(pink), Binding(green), and Modification(yellow, red, blue) sites on MDH2
<img width="400" alt="Screenshot 2024-12-06 at 10 33 25 PM" src="https://github.com/user-attachments/assets/352f6006-c2e7-4b64-9eea-47de8751f01a">

3. Comparison of amino acid 73 weak interactions with surrounding amino acids in Original (yellow), phosphoT73 (red), and mimic T73D(blue)
<img width="400" alt="Screenshot 2024-12-06 at 10 34 19 PM" src="https://github.com/user-attachments/assets/ab4f4312-bf46-41f0-ac9e-9551384dea09">

All three models of MDH2 have hydrogen bonding from residue 73(49) to LYS 45(21) and ILE 71(47).  However, the residue at 73 in the phosphoT73 model has an additional two interactions connecting itself to ASN 46(22) and LYS 74(50).  The mimic variant replaced the threonine for aspartic acid at residue 73.  Aspartic acid has a shorter side chain which can explain the loss of one of the hydrogen bonds towards LYS 45.


## Effect of the sequence variant and PTM on MDH dynamics

1. Comparison of post-MD simulations of original MDH2(yellow) and mimic T73D MDH2(blue)
<img width="400" alt="Screenshot 2024-12-06 at 10 37 03 PM" src="https://github.com/user-attachments/assets/68f27407-de2b-4541-ad59-6fb52cfd7068">

The superposition of post-MD simulations of original MDH2 and mimic T73D MDH2 yield a RMSD of 0.80Å which signifies a strong similarity between the two structures.

2. Comparison of modification sites on post-MD simulations of original MDH2(yellow) and mimic T73D MDH2(blue)
<img width="400" alt="Screenshot 2024-12-06 at 10 40 38 PM" src="https://github.com/user-attachments/assets/a8bd55b2-a94d-41b5-b635-b08e2224676d">
 
The MD simulations showed absolutely no change between pre-MD and post-MD weak interaction bonding and amino acid interactions.  The differences that were present prior to the molecular dynamics colab are still present after the completion of the molecular dynamics colab.


### Comparison of the enzyme dynamics

1. Overlapping Comparison of RMSF values in Angstroms (y-axis) for each amino acid position (x-axis) for MD simulations of original MDH2(yellow) and mimic T73D MDH2(blue)
<img width="400" alt="Screenshot 2024-12-06 at 10 42 04 PM" src="https://github.com/user-attachments/assets/ce2e11fc-0685-474b-b59f-c8bf7d68621a">

The mimic T73D MDH2 model has more dynamic change and flexibility around amino acid 420 while the original MDH2 model has more dynamic change and flexibility around amino acid 580.  The average RMSF value for all amino acids in the original MDH2 was 0.627Å while for mimic T73D MDH2 it was 0.631Å. The two amino acid areas that were different(420 and 580) are far from and unrelated to the active and binding sites of MDH2.  Based on the information given from the RMSF outputs in google drive colab for original MDH2 and mimic T73D MDH2, it indicates that the function of the enzyme has not been affected in the aspect of RMSF and will not alter MDH2 affinity for the substrates of NAD+ and malate.

### Effect of modification on the pKa values

1. pKa fluctuation for Histidine 200(176 in structure)(active site) for MD simulations of original MDH2(yellow) and mimic T73D MDH2(blue)
<img width="400" alt="Screenshot 2024-12-06 at 10 43 10 PM" src="https://github.com/user-attachments/assets/851585f1-7a9d-4dad-98ab-d6ff0c507610">

the pKa of the HIS 200(176 in structure) in the mimic T73D MDH2 was greater than the pKa of the HIS 200 in the original MDH2.  HIS 200 is the active site of MDH2 and the enzymatic mechanism of this protein is heavily dependent on the protonation and deprotonation of HIS 200.  Therefore, with the pKa being greater in the mimic T73D MDH2, the modified MDH2 would have more difficulty deprotonating which could severely reduce efficiency or completely inhibit the enzymatic function of MDH2.


## Comparison of the mimic and the authentic PTM

1. Alignment of the MDH2 with phosphoT 73(red), MDH2 mimic T73D(blue)
<img width="400" alt="Screenshot 2024-12-06 at 10 43 58 PM" src="https://github.com/user-attachments/assets/5f33d250-84de-4e6a-80b5-40dfb19460e7">

The RMSD MDHT73D and phosphoT73 MDH2 was 1.43 Å. The overall structures are similar with no major differences in structure or position. The mimic T73D MDH2’s loss of an additional bond to LYS 45 is most likely the reasoning behind the slightly increased RMSD value between itself and the phosphoT 73 MDH2. 

## Authors

Ali Khajavi

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

(1) UniProt. https://www.uniprot.org/uniprotkb/P40926/entry (accessed 2024-12-06).

(2) AlphaFold Server. https://alphafoldserver.com/ (accessed 2024-12-06).

(3) Sehnal, D.; Bittrich, S.; Deshpande, M.; Svobodová, R.; Berka, K.; Bazgier, V.; Velankar, S.; Burley, S. K.; Koča, J.; Rose, A. S. Mol* Viewer: Modern Web App for 3D Visualization and Analysis of Large Biomolecular Structures. Nucleic Acids Research 2021, 49 (W1), W431–W437. https://doi.org/10.1093/nar/gkab314.
