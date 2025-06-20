# Human Mitochondrial MDH2

# Uniprot ID: P40926
# Variation: phosphorylation of Y80 (pY56 in structure)



## Description

Phosphorylation of Tyrosine is a modified residue of large scale data by [Chi V. Dang] (https://www.science.org/doi/10.1126/scisignal.297pe75) in 2009. The study suggests that the receptor tyrosine directly phospohrylates pyruvate kinase resulting in catabolosis of lactate by lactate dehydrogenase in human MDH2 [(P40926)](https://www.uniprot.org/uniprotkb/P40926/entry) 

# Comparison of MDH2 models and phospho modified MDH2

1. Alignment of MDH2 (green), MDH2 with phosphoY 80 (red), and Y80D (blue)
<img width="800" alt="Align" src="https://github.com/user-attachments/assets/c46cadd6-4bf9-41a8-9479-c76dac0feb97">


2. Modification site alignment within MDH2
<img width="556" alt="Mod Site" src="https://github.com/user-attachments/assets/b001b7a3-4783-4fc7-a8af-3adb4d3df9dd">

3. Weak interactions among unmodified, variant, and mimic
<img width="284" alt="image" src="https://github.com/user-attachments/assets/983b2576-c532-4139-b920-3cf2b2e91ef1">

There are numerous instances of weak interactions around the K54, D64, and T30 amino acids. These side chains contain instances of hydrogen and ionic bonding interactions. 

## Effect of the sequence variant and PTM on MDH dynamics
4. Binding sites (black) and active site (pink)
<img width="296" alt="image" src="https://github.com/user-attachments/assets/9b983580-32f5-4fed-bfb8-c2d88f662aa0">

The RMSD of original AF3 and PTM shows had an RMSD of 0.16 Å. The original AF3 and mimic structures had an RMSD of 0.23 Å. Values determine these structures are very similar in their spatial arrangment.


5. Original MDH2 (green) and mimic (orange)
<img width="364" alt="image" src="https://github.com/user-attachments/assets/c2b5d1e6-e048-4a2a-bbd9-561c718dbfef">
The mimic is showing interactions between K54 and L31 while the original MDH2 only shows interactions with L31. The molecules have slightly different weak interactions.



6. Potential chloride ion replacing K54
<img width="250" alt="image" src="https://github.com/user-attachments/assets/3ed94a14-ef8e-4bcd-97b5-c948a1b215ff">

### Comparison of the enzyme dynamics
THe RMSF values for both MDH2 original and mimic vary higly. The mimic is more dynamic and able to change conformation to perform energy changes. Before the phosphorylation of Tyrosine there was no peak around amino acid 80. The phosphorylation of Tyrosine was able to increase the structures overall flexibility as there are numerous other peaks when compared to the original. Many peaks located around 250, 400, and 475. Mimic and original were measured at 0.63 Å, mimic measured at 0.66 Å The vertical line indicates the end of one subunit and the beginning of the next subunit of the MDH1 dimer.

<img width="375" alt="image" src="https://github.com/user-attachments/assets/4a5805d1-d45b-4861-8c2e-7f4195992ef0">


<img width="283" alt="image" src="https://github.com/user-attachments/assets/ef042e9d-2612-44d6-b426-32883bdc6417">
D64 contained various flucutations in pKa. Aspartic acid is sensitive to electrostatic environments. Aspartic acid could be placed near a charged molecule. Normally aspartic acid would react similarly with water, water molecules were removed during the colab. 


The loops sites are shown below in blue with stick representations. The upper grouping is the active site loop. The yellow ellipse shows the approximate bind sites of the carboxylic acid and NAD+ substrates.


### Effect of modification on the pKa values

Original in orange has a decreased overall pKa and the mimic has an increased overall pKa. His 176 is the active site for MDH2. Original has more difficulty deprotonating. Phosphorylation of Tyrosine within the mimic is increased compared to the original model.

<img width="449" alt="image" src="https://github.com/user-attachments/assets/cc9cf9b2-d1bf-4815-adf3-a6a1148f8c9a">



## Comparison of the mimic and the authentic PTM
The RMSD PhophoY80 and Y80D MDH1 was 0.18 Å. The overall structures are similar with no major differences in structure or position.

<img width="251" alt="image" src="https://github.com/user-attachments/assets/38e992cc-6335-42bd-ba62-049462950455">

## Authors

Philip C. McKenna

## Deposition Date
10/6/2024

## License

Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg

## References

AlphaFold Server. https://alphafoldserver.com/ (accessed 2024-12-06).

Dang, C. V. PKM2 Tyrosine Phosphorylation and Glutamine Metabolism Signal a Different View of the Warburg Effect. Science Signaling 2009, 2 (97). DOI:10.1126/scisignal.297pe75. 

Sehnal, D.; Bittrich, S.; Deshpande, M.; Svobodová, R.; Berka, K.; Bazgier, V.; Velankar, S.; Burley, S. K.; Koča, J.; Rose, A. S. Mol* Viewer: Modern Web App for 3D Visualization and Analysis of Large Biomolecular Structures. Nucleic Acids Research 2021, 49 (W1), W431–W437. https://doi.org/10.1093/nar/gkab314.

UniProt. https://www.uniprot.org/uniprotkb/P40926/entry (accessed 2024-12-06).
