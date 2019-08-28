# [5k PBMCs from a healthy donor with cell surface proteins (v3 chemistry)](https://support.10xgenomics.com/single-cell-gene-expression/datasets/3.1.0/5k_pbmc_protein_v3)
 
_Single Cell Gene Expression Dataset by Cell Ranger 3.1.0 - Published on July 24, 2019 - 
This dataset is licensed under the Creative Commons Attribution license._

Peripheral blood mononuclear cells (PBMCs) from a healthy donor cells were stained with a panel of 31 TotalSeq™-B antibodies (BioLegend). PBMCs are primary cells with relatively small amounts of RNA (~1pg RNA/cell).
 
Libraries were prepared following the Chromium Single Cell 3ʹ Reagent Kits v3 with Feature Barcoding technology for Cell Surface Protein User Guide (CG000185 RevB).
 
5,247 cells detected
Sequenced on Illumina NovaSeq with approximately 28,918 reads per cell
28bp read1 (16bp Chromium barcode and 12bp UMI), 91bp read2 (transcript), and 8bp I7 sample barcode
run with --expect-cells=5000

## [Cellranger pipeline (3.1.0)](Cellranger_3.1.0_pipeline.ipynb)
This notebook uses the input files provided for the [5K PBMCs dataset](https://support.10xgenomics.com/single-cell-gene-expression/datasets/3.1.0/5k_pbmc_protein_v3) and generates the output files by using the `cellranger count` pipeline with [Feature Barcoding Analysis](https://support.10xgenomics.com/single-cell-gene-expression/software/pipelines/latest/using/feature-bc-analysis).

The outputs are created in the `5k_pbmc_protein_v3/outs` directory and contain the following:

- Run summary HTML:                      5k_pbmc_protein_v3/outs/outs/web_summary.html
- Run summary CSV:                       5k_pbmc_protein_v3/outs/metrics_summary.csv
- BAM:                                   5k_pbmc_protein_v3/outs/possorted_genome_bam.bam
- BAM index:                             5k_pbmc_protein_v3/outs/possorted_genome_bam.bam.bai
- Filtered feature-barcode matrices MEX:    5k_pbmc_protein_v3/outs/filtered_feature_bc_matrix
- Filtered feature-barcode matrices HDF5:   5k_pbmc_protein_v3/outs/filtered_feature_bc_matrix.h5
- Unfiltered feature-barcode matrices MEX:  5k_pbmc_protein_v3/outs/raw_feature_bc_matrix
- Unfiltered feature-barcode matrices HDF5: 5k_pbmc_protein_v3/outs/raw_feature_bc_matrix_h5.h5
- Secondary analysis output CSV:         5k_pbmc_protein_v3/outs/analysis
- Per-molecule read information:         5k_pbmc_protein_v3/outs/molecule_info.h5
- Loupe Cell Browser file:               5k_pbmc_protein_v3/outs/cloupe.cloupe

## [Example analysis in_python](10x_notebook_tutorial-3.0.0_python.ipynb)

This notebook is an adaptation for the [5K PBMCs dataset](https://support.10xgenomics.com/single-cell-gene-expression/datasets/3.1.0/5k_pbmc_protein_v3) of the notebook available on the 10x genomics [website](http://cf.10xgenomics.com/supp/cell-exp/notebook_tutorial-3.0.0.html)
