# Single-cell RNA-seq tools
  > Just a collection of tools I used in my analysis, will update depend on my own flavor.
  > And will put some useful knowledge here as well. 
## Pipelines/Tutuorials/Resources:
  - Seurat: https://satijalab.org/seurat/index.html
    > Tutorial: https://github.com/hbctraining/scRNA-seq_online/tree/master/lessons
    
    > https://www.singlecellcourse.org/index.html

    > https://broadinstitute.github.io/2019_scWorkshop/index.html#course-overview
  - Scanpy: https://scanpy.readthedocs.io/en/stable/
    > https://chanzuckerberg.github.io/scRNA-python-workshop/intro/about.html
  - Scvi-tools: https://docs.scvi-tools.org/en/stable/index.html#
  - KNetL(with a new view of dimensionality reduction) from iCellR: https://github.com/rezakj/iCellR
  - https://chanzuckerberg.github.io/scRNA-python-workshop/intro/setup.html
  - https://github.com/seandavi/awesome-single-cell
## Integration:
  - Slow, Seurat CCA
  - Fast, RPCA and reference based: https://satijalab.org/seurat/articles/integration_large_datasets.html
  - Harmony: https://portals.broadinstitute.org/harmony/articles/quickstart.html; 
    > Korsunsky, I., Millard, N., Fan, J. et al. Fast, sensitive and accurate integration of single-cell data with Harmony. Nat Methods 16, 1289–1296 (2019). https://doi.org/10.1038/s41592-019-0619-0
## Automatic cell type indentification:
  - Cortal, A., Martignetti, L., Six, E. et al. Gene signature extraction and cell identity recognition at the single-cell level with Cell-ID. Nat Biotechnol 39, 1095–1102 (2021). https://doi.org/10.1038/s41587-021-00896-6
    > https://github.com/RausellLab/CelliD;
  - Pliner, H.A., Shendure, J. & Trapnell, C. Supervised classification enables rapid annotation of cell atlases. Nat Methods 16, 983–986 (2019). https://doi.org/10.1038/s41592-019-0535-3
    > https://cole-trapnell-lab.github.io/garnett/;
    > https://cole-trapnell-lab.github.io/monocle3/docs/clustering/#garnett
## Cell relationship, fate, velocity and trajectory:
  - Saelens, W., Cannoodt, R., Todorov, H. et al. A comparison of single-cell trajectory inference methods. Nat Biotechnol 37, 547–554 (2019). https://doi.org/10.1038/s41587-019-0071-9
  - https://www.10xgenomics.com/resources/analysis-guides/trajectory-analysis-using-10x-Genomics-single-cell-gene-expression-data
  - Schwartz, G.W., Zhou, Y., Petrovic, J. et al. TooManyCells identifies and visualizes relationships of single-cell clades. Nat Methods 17, 405–413 (2020). https://doi.org/10.1038/s41592-020-0748-5
    > https://github.com/GregorySchwartz/too-many-cells
  - Xiaojie Qiu, Yan Zhang, Jorge D. Martin-Rufino, et al, Jonathan S. Weissman,Mapping transcriptomic vector fields of single cells,Cell,2022,,ISSN 0092-8674,https://doi.org/10.1016/j.cell.2021.12.045.
    > https://github.com/aristoteleo/dynamo-release;
    > https://dynamo-release.readthedocs.io/en/latest/
  - Lange, M., Bergen, V., Klein, M. et al. CellRank for directed single-cell fate mapping. Nat Methods 19, 159–170 (2022). https://doi.org/10.1038/s41592-021-01346-6
    > https://cellrank.readthedocs.io/en/stable/
  - La Manno, G., Soldatov, R., Zeisel, A. et al. RNA velocity of single cells. Nature 560, 494–498 (2018). https://doi.org/10.1038/s41586-018-0414-6
    > http://velocyto.org/ ; https://ucdavis-bioinformatics-training.github.io/2020-Advanced_Single_Cell_RNA_Seq/data_analysis/Velocyto_fixed
  - Bergen, V., Lange, M., Peidli, S. et al. Generalizing RNA velocity to transient cell states through dynamical modeling. Nat Biotechnol 38, 1408–1414 (2020). https://doi.org/10.1038/s41587-020-0591-3
    > https://scvelo.readthedocs.io/
  - Tedesco, M., Giannese, F., Lazarević, D. et al. Chromatin Velocity reveals epigenetic dynamics by single-cell profiling of heterochromatin and euchromatin. Nat Biotechnol 40, 235–244 (2022). https://doi.org/10.1038/s41587-021-01031-1
    > Chromatin Velocity: https://github.com/leomorelli/scGET; https://github.com/dawe/scatACC
## Cell-cell interaction:
  - Jin, S., Guerrero-Juarez, C.F., Zhang, L. et al. Inference and analysis of cell-cell communication using CellChat. Nat Commun 12, 1088 (2021). https://doi.org/10.1038/s41467-021-21246-9
    > CellChat: http://www.cellchat.org/; https://github.com/sqjin/CellChat
## Differential abundance testing:
  - Dann, E., Henderson, N.C., Teichmann, S.A. et al. Differential abundance testing on single-cell data using k-nearest neighbor graphs. Nat Biotechnol 40, 245–253 (2022). https://doi.org/10.1038/s41587-021-01033-z
    > Milo: https://github.com/MarioniLab/miloR
## DEG calculation:
  - Squair, J.W., Gautier, M., Kathe, C. et al. Confronting false discoveries in single-cell differential expression. Nat Commun 12, 5692 (2021). https://doi.org/10.1038/s41467-021-25960-2
    > Libra: https://github.com/neurorestore/Libra
## Doublet removal:
  - McGinnis, Christopher S., Lyndsay M. Murrow, and Zev J. Gartner. "DoubletFinder: doublet detection in single-cell RNA sequencing data using artificial nearest neighbors." Cell systems 8.4 (2019): 329-337.
    > https://github.com/chris-mcginnis-ucsf/DoubletFinder
  - Wolock, Samuel L., Romain Lopez, and Allon M. Klein. "Scrublet: computational identification of cell doublets in single-cell transcriptomic data." Cell systems 8.4 (2019): 281-291.
    > https://github.com/swolock/scrublet
## Transcription factor activity
  - SCENIC: https://github.com/aertslab/SCENIC; http://htmlpreview.github.io/?https://github.com/aertslab/SCENIC/blob/master/inst/doc/SCENIC_Setup.html;  http://htmlpreview.github.io/?https://github.com/aertslab/SCENIC/blob/master/inst/doc/SCENIC_Running.html
    > Aibar, S., González-Blas, C., Moerman, T. et al. SCENIC: single-cell regulatory network inference and clustering. Nat Methods 14, 1083–1086 (2017). https://doi.org/10.1038/nmeth.4463; 
    
    > Van de Sande, B., Flerin, C., Davie, K. et al. A scalable SCENIC workflow for single-cell gene regulatory network analysis. Nat Protoc 15, 2247–2276 (2020). https://doi.org/10.1038/s41596-020-0336-2
  - BITFAM: https://github.com/jaleesr/BITFAM
    > Gao, S., Dai, Y., & Rehman, J. (2021). A Bayesian inference transcription factor activity model for the analysis of single-cell transcriptomes. Genome research, 31(7), 1296-1311.

## Bam file processing:
- Subset bam with interested cells: https://kb.10xgenomics.com/hc/en-us/articles/360022448251-How-to-filter-the-BAM-file-produced-by-10x-pipelines-with-a-list-of-barcodes-

## TCR-seq analysis
- scRepertoire: https://ncborcherding.github.io/vignettes/vignette.html

# Current techniques and reviews:
  - Ogbeide, Silvia, et al. "Into the multiverse: advances in single-cell multiomic profiling." Trends in Genetics (2022).https://doi.org/10.1016/j.tig.2022.03.015
![image](https://user-images.githubusercontent.com/19710340/169665170-60d55541-1571-4586-ba30-0a5da50cf89f.png)
![image](https://user-images.githubusercontent.com/19710340/169665211-092743a0-dbe7-4bfc-b983-849f5465afbf.png)
  - Preissl, S., Gaulton, K.J. & Ren, B. Characterizing cis-regulatory elements using single-cell epigenomics. Nat Rev Genet (2022). https://doi.org/10.1038/s41576-022-00509-1
