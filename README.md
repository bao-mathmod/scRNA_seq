# scRNA-seq Mentorship Course (R-based)

A structured mentorship course for beginners learning single-cell RNA-seq analysis from conceptual orientation to practical R/Seurat workflows.

## Course goals

By the end of the mentorship, students should be able to:

1. Explain why single-cell RNA-seq is different from bulk RNA-seq.
2. Understand how barcodes, UMIs, and count matrices connect wet-lab protocols to computational analysis.
3. Run a beginner-friendly R/Seurat workflow for QC, normalization, dimensionality reduction, clustering, marker detection, and annotation.
4. Interpret scRNA-seq results with scientific caution, especially around dropout, doublets, ambient RNA, batch effects, and over-annotation.
5. Prepare a small final report that explains the analysis process and biological interpretation.

## Website

This repository is designed as a Quarto website published with GitHub Pages.

Local preview:

```bash
quarto preview
```

Render:

```bash
quarto render
```

## Recommended learning path

- Orientation: big picture of scRNA-seq
- Day 0: R setup and minimal R foundation
- Week 1: scRNA-seq biology and technology
- Week 2: data structure and Seurat object
- Week 3: quality control
- Week 4: normalization, PCA, UMAP
- Week 5: clustering and marker genes
- Week 6: cell-type annotation and integration
- Week 7: differential expression and interpretation
- Week 8: advanced overview and mini-project

## Repository policy

Do not commit private student data, unpublished datasets, or slide decks with unclear redistribution rights. Put large datasets behind download scripts or external links.
