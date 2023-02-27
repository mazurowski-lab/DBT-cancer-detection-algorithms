# DBT-cancer-detection-algorithms

## Introduction and Citation
Library of the publicly-availible lesion detection algorithm codebases from participating teams of the DBTex Digital Breast Tomosynthesis Lesion Detection Challenge, all of which use deep learning. If you use any of these codebases, please cite the authors, as well as the DBTex challenge [paper](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2801740):
```bib
@article{10.1001/jamanetworkopen.2023.0524,
    author = {Konz, Nicholas and Buda, Mateusz and Gu, Hanxue and Saha, Ashirbani and Yang, Jichen and Chłędowski, Jakub and Park, Jungkyu and Witowski, Jan and Geras, Krzysztof J. and Shoshan, Yoel and Gilboa-Solomon, Flora and Khapun, Daniel and Ratner, Vadim and Barkan, Ella and Ozery-Flato, Michal and Martí, Robert and Omigbodun, Akinyinka and Marasinou, Chrysostomos and Nakhaei, Noor and Hsu, William and Sahu, Pranjal and Hossain, Md Belayat and Lee, Juhun and Santos, Carlos and Przelaskowski, Artur and Kalpathy-Cramer, Jayashree and Bearce, Benjamin and Cha, Kenny and Farahani, Keyvan and Petrick, Nicholas and Hadjiiski, Lubomir and Drukker, Karen and Armato, Samuel G., III and Mazurowski, Maciej A.},
    title = "{A Competition, Benchmark, Code, and Data for Using Artificial Intelligence to Detect Lesions in Digital Breast Tomosynthesis}",
    journal = {JAMA Network Open},
    volume = {6},
    number = {2},
    pages = {e230524-e230524},
    year = {2023},
    month = {02},
    issn = {2574-3805},
    doi = {10.1001/jamanetworkopen.2023.0524},
    url = {https://doi.org/10.1001/jamanetworkopen.2023.0524},
    eprint = {https://jamanetwork.com/journals/jamanetworkopen/articlepdf/2801740/konz\_2023\_oi\_230034\_1676399873.35447.pdf},
}
```
## Algorithm Codebases

### Submitted Algorithms
**Please see Table 2 and the Supplementary Materials of the above paper for more technical details on each algorithm.**

1. Team ZeDuS: [work-reduction-dbt](https://github.com/IBM/work-reduction-dbt) ("Implementation of DBT inference ensemble, showing how a collection of predictions produced by multiple types of models (image detector, image classifier and clinical-information model) are combined into a single final per exam prediction.")
2. Team VICOROB:
    1. [Ensembled Fast R-CNN](https://github.com/ICEBERG-VICOROB/vicorob_DBT_Challenge) (from challenge phase 1)
    2. [Fast R-CNN + False Positive Reduction](https://github.com/ICEBERG-VICOROB/DBT_phase2) (from challenge phase 2)
3. Team UCLA-MII: [Faster R-CNN 2D (In-Slice) Detection Ensembling followed by 3D Reconstruction](https://github.com/aguron/DBTex)
4. Team pranjalsahu: [Faster R-CNN + Confidence Peak Finder](https://github.com/PranjalSahu/DBTNet)
5. Team PittRad: [Biopsied lesion detection leveraging non-biopsied (actionable) false postive findings (actFPs)](https://github.com/IRL-UP/TeamPittRad-DBTex1)

### Baseline Algorithms
1. [DenseNet Baseline](https://github.com/mazurowski-lab/duke-dbt-data)
2. [Faster R-CNN Baseline](https://github.com/mazurowski-lab/DBTex-baseline)

## License Information
Please refer to each codebase repository's respective license.
