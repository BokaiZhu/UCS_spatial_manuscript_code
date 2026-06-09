# UCS CosMx Spatial Manuscript — Analysis Code

Code accompanying the manuscript:  
**"The Tumor-Immune Spatial Organization of Uterine Carcinosarcoma is Shaped by Molecular Subtype"**

---

## Data

Processed data files required to run this code are deposited on Zenodo: [[10.5281/zenodo.19828316](https://zenodo.org/records/19828316)] (currently not public).

Place all downloaded data files in a `data/` folder at the same level as the figure folders (`code_organize/data/`).

---

## Structure

| Folder | Figure | Description |
|---|---|---|
| `general_upstream/` | — | RNA processing and clustering |
| `fig1/` | Fig 1 | RNA and protein UMAPs, MaxFuse integration |
| `fig2/` | Fig 2 | Cell type frequency, spatial interaction, MESA |
| `fig3/` | Fig 3 | Protein cellular neighborhood (CN) analysis |
| `fig4/` | Fig 4 | Macrophage cNMF, MoMac-VERSE scoring, MiloR |
| `fig5/` | Fig 5 | EMT scoring, COMMOT ligand-receptor analysis |
| `legacy/` | — | Archived scripts, not used in final figures |

---

## Requirements

**R packages:** Seurat, miloR, ggplot2, patchwork, dplyr, FNN, rstatix, ggridges  
**Python packages:** scanpy, commot, cnmf, anndata, pandas, numpy, matplotlib, seaborn, scipy

---

## Contact

Brooke Howitt bhowitt@stanford.edu
Sizun Jiang sjiang3@bidmc.harvard.edu
