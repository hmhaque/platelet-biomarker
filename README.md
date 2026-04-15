# Universal Platelet Biomarker

# Boolean implication analysis identifies TUBB1 as a lineage-restricted universal platelet biomarker

## Summary
This project develops a computational framework to identify transcriptomic biomarkers of platelet abundance and specificity across diverse human datasets. Using Boolean implication analysis, lineage-informed filtering, and multi-cohort benchmarking, the goal is to move beyond conventional platelet-associated markers and define biomarkers that remain reliable across tissues, diseases, and experimental settings.

We found:
- Built a two-step discovery pipeline combining Boolean implication analysis with megakaryocyte-versus-myeloid prioritization.
- Identified a compact five-gene platelet signature.
- Observed that some signature genes still show background expression in solid tissues, but TUBB1 remained the most consistently specific.
- Concluded that TUBB1 is the strongest candidate for a universal platelet biomarker. 

## Requirements
- Python
  - [ScanPy](https://scanpy.readthedocs.io/en/stable/) (v1.9.1)
  - [Matplotlib](https://matplotlib.org/) (v3.5.3)
  - [Seaborn](https://seaborn.pydata.org/index.html) (v0.12.2)
  - [BoNE](https://github.com/sahoo00/BoNE) (Boolean Network Explorer)


## Citation
```
@article{pltBioMarker2026,
  title  = {Boolean implication analysis identifies TUBB1 as a lineage-restricted universal platelet biomarker},
  author = {H M Zabir Haque, and Debashis Sahoo},
  note   = {Manuscript under review}
}
```
