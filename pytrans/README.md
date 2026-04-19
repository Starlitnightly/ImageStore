# pytrans — Python translation of R bioinformatics packages

Image hosting for the `py-*R` family of pure-Python ports of R single-cell / spatial bioinformatics packages.

## Repos

| Folder prefix | Source | PyPI | What |
|---|---|---|---|
| `py-mclustR_*` | [CRAN mclust](https://github.com/cran/mclust) | [pymclustR](https://pypi.org/project/pymclustR/) | Gaussian-mixture clustering, all 14 covariance parameterisations |
| `py-CCA_*` | [Seurat](https://github.com/satijalab/seurat) | (pending) | Canonical correlation analysis for single-cell integration |
| `py-monocle2_*` | [Monocle 2](https://github.com/cole-trapnell-lab/monocle-release) | [monocle2-py](https://pypi.org/project/monocle2-py/) | Trajectory inference (DDRTree + BEAM) |
| `py-miloR_*` | [miloR](https://github.com/MarioniLab/miloR) | [milor-py](https://pypi.org/project/milor-py/) | Differential abundance on k-NN neighbourhoods |
| `py-DoubletFinder_*` | DoubletFinder | (pending) | Doublet detection |
| `py-scDblFinder_*` | scDblFinder | (reserved) | Doublet detection |
| `py-dada2_*` | DADA2 | (pending) | 16S amplicon ASV inference |

## Naming

`py-{package}_{kind}.png` — kind tags include `seurat_parity`, `r_parity`, `embedding_visualization`, `loglik_scatter`, `bic_curves`, `cluster_scatters`, `confusion_matrices`, `correlation_heatmaps`, `parity_heatmap`, `per_model_agreement`.

## Embedding

Use raw GitHub URLs:

```markdown
![py-CCA seurat parity](https://raw.githubusercontent.com/Starlitnightly/ImageStore/main/pytrans/py-CCA_seurat_parity.png)
```
