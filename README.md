# Single-cell toolbox
  > Just a collection of tools I used in my analysis, will update depending on my own flavor.
  > And will put some useful knowledge here as well. 
  - A collection: https://www.scrna-tools.org/
  - Open problems group: https://openproblems.bio/
  - Guide: See, Peter, et al. "A single-cell sequencing guide for immunologists." Frontiers in Immunology 9 (2018): 2425.
## Pipelines/Tutorials/Resources:
  - Seurat: https://satijalab.org/seurat/index.html
    > Tutorial:https://github.com/hbctraining/scRNA-seq_online/tree/master/lessons;
    > https://www.singlecellcourse.org/index.html;
    > https://github.com/tallulandrews/scRNASeqPipeline
    
    > https://www.singlecellcourse.org/index.html

    > https://broadinstitute.github.io/2019_scWorkshop/index.html#course-overview
  - Tools: https://github.com/seandavi/awesome-single-cell
  - Scanpy: https://scanpy.readthedocs.io/en/stable/
    > https://chanzuckerberg.github.io/scRNA-python-workshop/intro/about.html
  - Scvi-tools: https://docs.scvi-tools.org/en/stable/index.html#
  - KNetL(with a new view of dimensionality reduction) from iCellR: https://github.com/rezakj/iCellR
  - https://chanzuckerberg.github.io/scRNA-python-workshop/intro/setup.html

  - Datasets: https://hemberg-lab.github.io/scRNA.seq.datasets/
## Integration:
  - Slow, Seurat CCA
  - Fast, RPCA and reference-based: https://satijalab.org/seurat/articles/integration_large_datasets.html
  - Harmony: https://portals.broadinstitute.org/harmony/articles/quickstart.html; 
    > Korsunsky, I., Millard, N., Fan, J. et al. Fast, sensitive and accurate integration of single-cell data with Harmony. Nat Methods 16, 1289–1296 (2019). https://doi.org/10.1038/s41592-019-0619-0
  - He, Zhisong, et al. "CSS: cluster similarity spectrum integration of single-cell genomics data." Genome biology 21.1 (2020): 1-21.
    > https://github.com/quadbiolab/simspec
  - De Donno, C., Hediyeh-Zadeh, S., Moinfar, A.A. et al. Population-level integration of single-cell datasets enables multi-scale analysis across samples. Nat Methods (2023). https://doi.org/10.1038/s41592-023-02035-2
    > Part of https://docs.scarches.org/en/latest/; transposase-accessible chromatin and cross-species datasets
## Automatic cell type identification:
  - Cortal, A., Martignetti, L., Six, E. et al. Gene signature extraction and cell identity recognition at the single-cell level with Cell-ID. Nat Biotechnol 39, 1095–1102 (2021). https://doi.org/10.1038/s41587-021-00896-6
    > https://github.com/RausellLab/CelliD;
  - Pliner, H.A., Shendure, J. & Trapnell, C. Supervised classification enables rapid annotation of cell atlases. Nat Methods 16, 983–986 (2019). https://doi.org/10.1038/s41592-019-0535-3
    > https://cole-trapnell-lab.github.io/garnett/;
    > https://cole-trapnell-lab.github.io/monocle3/docs/clustering/#garnett
  - Hu, C., Li, T., Xu, Y., Zhang, X., Li, F., Bai, J., ... & Zhang, Y. (2022). CellMarker 2.0: an updated database of manually curated cell markers in human/mouse and web tools based on scRNA-seq data. Nucleic Acids Research.
    > http://bio-bigdata.hrbmu.edu.cn/CellMarker or http://117.50.127.228/CellMarker/
  - Ianevski, A., Giri, A.K. & Aittokallio, T. Fully-automated and ultra-fast cell-type identification using specific marker combinations from single-cell transcriptomic data. Nat Commun 13, 1246 (2022). https://doi.org/10.1038/s41467-022-28803-w
    > https://github.com/IanevskiAleksandr/sc-type

  - Python-based: by integrating it into a reference atlas; Lotfollahi, M., Naghipourfar, M., Luecken, M.D. et al. Mapping single-cell data to reference atlases by transfer learning. Nat Biotechnol 40, 121–130 (2022). https://doi.org/10.1038/s41587-021-01001-7
    > https://github.com/theislab/scarches/tree/master/notebooks
  - Spatial cell annotation:
    > Brbić, M., Cao, K., Hickey, J.W. et al. Annotation of spatially resolved single-cell data with STELLAR. Nat Methods 19, 1411–1418 (2022). https://doi.org/10.1038/s41592-022-01651-8
   
    > https://github.com/snap-stanford/stellar

## Cell relationship, fate, velocity and trajectory:
  - Street, K., Risso, D., Fletcher, R. B., Das, D., Ngai, J., Yosef, N., ... & Dudoit, S. (2018). Slingshot: cell lineage and pseudotime inference for single-cell transcriptomics. BMC genomics, 19(1), 1-16.
    > Slingshot: https://bioconductor.org/packages/devel/bioc/vignettes/slingshot/inst/doc/vignette.html. 
  - Saelens, W., Cannoodt, R., Todorov, H. et al. A comparison of single-cell trajectory inference methods. Nat Biotechnol 37, 547–554 (2019). https://doi.org/10.1038/s41587-019-0071-9
  - https://www.10xgenomics.com/resources/analysis-guides/trajectory-analysis-using-10x-Genomics-single-cell-gene-expression-data
  - Schwartz, G.W., Zhou, Y., Petrovic, J. et al. TooManyCells identifies and visualizes relationships of single-cell clades. Nat Methods 17, 405–413 (2020). https://doi.org/10.1038/s41592-020-0748-5
    > https://github.com/GregorySchwartz/too-many-cells
  - Xiaojie Qiu, Yan Zhang, Jorge D. Martin-Rufino, et al, Jonathan S. Weissman, Mapping transcriptomic vector fields of single cells,Cell,2022,,ISSN 0092-8674,https://doi.org/10.1016/j.cell.2021.12.045.
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
  - Lynch, A. W., Theodoris, C. V., Long, H. W., Brown, M., Liu, X. S., & Meyer, C. A. (2022). MIRA: Joint regulatory modeling of multimodal expression and chromatin accessibility in single cells. Nature Methods, 1-12.
    > RNA+ATAC: https://github.com/cistrome/MIRA.
## Cell-cell interaction:
  - Jin, S., Guerrero-Juarez, C.F., Zhang, L. et al. Inference and analysis of cell-cell communication using CellChat. Nat Commun 12, 1088 (2021). https://doi.org/10.1038/s41467-021-21246-9
    > CellChat: http://www.cellchat.org/; https://github.com/sqjin/CellChat

  - LIANA: a LIgand-receptor ANalysis frAmework: Dimitrov, D., Türei, D., Garrido-Rodriguez M., Burmedi P.L., Nagai, J.S., Boys, C., Flores, R.O.R., Kim, H., Szalai, B., Costa, I.G., Valdeolivas, A., Dugourd, A. and Saez-Rodriguez, J. Comparison of methods and resources for cell-cell communication inference from single-cell RNA-Seq data. Nat Commun 13, 3224 (2022). https://doi.org/10.1038/s41467-022-30755-0
    > https://saezlab.github.io/liana/articles/liana_tutorial.html
## Differential abundance testing:
  - Dann, E., Henderson, N.C., Teichmann, S.A. et al. Differential abundance testing on single-cell data using k-nearest neighbor graphs. Nat Biotechnol 40, 245–253 (2022). https://doi.org/10.1038/s41587-021-01033-z
    > Milo: https://github.com/MarioniLab/miloR
## DEG calculation:
  - Squair, J.W., Gautier, M., Kathe, C. et al. Confronting false discoveries in single-cell differential expression. Nat Commun 12, 5692 (2021). https://doi.org/10.1038/s41467-021-25960-2
    > Libra: https://github.com/neurorestore/Libra
  - small difference: Weinberger, E., Lin, C. & Lee, SI. Isolating salient variations of interest in single-cell data with contrastiveVI. Nat Methods 20, 1336–1345 (2023). https://doi.org/10.1038/s41592-023-01955-3
## Doublet removal:
  - McGinnis, Christopher S., Lyndsay M. Murrow, and Zev J. Gartner. "DoubletFinder: doublet detection in single-cell RNA sequencing data using artificial nearest neighbors." Cell systems 8.4 (2019): 329-337.
    > https://github.com/chris-mcginnis-ucsf/DoubletFinder
  - Wolock, Samuel L., Romain Lopez, and Allon M. Klein. "Scrublet: computational identification of cell doublets in single-cell transcriptomic data." Cell systems 8.4 (2019): 281-291.
    > https://github.com/swolock/scrublet
## Regulons/Transcription factor activity
  - SCENIC & SCENIC+: https://github.com/aertslab/SCENIC; http://htmlpreview.github.io/?https://github.com/aertslab/SCENIC/blob/master/inst/doc/SCENIC_Setup.html;  http://htmlpreview.github.io/?https://github.com/aertslab/SCENIC/blob/master/inst/doc/SCENIC_Running.html
    > Aibar, S., González-Blas, C., Moerman, T. et al. SCENIC: single-cell regulatory network inference and clustering. Nat Methods 14, 1083–1086 (2017). https://doi.org/10.1038/nmeth.4463;     
    > Van de Sande, B., Flerin, C., Davie, K. et al. A scalable SCENIC workflow for single-cell gene regulatory network analysis. Nat Protoc 15, 2247–2276 (2020). https://doi.org/10.1038/s41596-020-0336-2
    > Bravo González-Blas, C., De Winter, S., Hulselmans, G. et al. SCENIC+: single-cell multiomic inference of enhancers and gene regulatory networks. Nat Methods 20, 1355–1367 (2023). https://doi.org/10.1038/s41592-023-01938-4
  - BITFAM: https://github.com/jaleesr/BITFAM
    > Gao, S., Dai, Y., & Rehman, J. (2021). A Bayesian inference transcription factor activity model for the analysis of single-cell transcriptomes. Genome research, 31(7), 1296-1311.
  - Pando: https://github.com/quadbiolab/Pando
    > Fleck, J.S., Jansen, S.M.J., Wollny, D. et al. Inferring and perturbing cell fate regulomes in human brain organoids. Nature (2022). https://doi.org/10.1038/s41586-022-05279-8
  - Dictys: Wang, L., Trasanidis, N., Wu, T. et al. Dictys: dynamic gene regulatory network dissects developmental continuum with single-cell multiomics. Nat Methods 20, 1368–1378 (2023). https://doi.org/10.1038/s41592-023-01971-3
  - MIRA: Lynch, A.W., Theodoris, C.V., Long, H.W. et al. MIRA: joint regulatory modeling of multimodal expression and chromatin accessibility in single cells. Nat Methods 19, 1097–1108 (2022). https://doi.org/10.1038/s41592-022-01595-z
## Remove background/ambient RNA:
  - Fleming, S.J., Chaffin, M.D., Arduini, A. et al. Unsupervised removal of systematic background noise from droplet-based single-cell experiments using CellBender. Nat Methods 20, 1323–1335 (2023). https://doi.org/10.1038/s41592-023-01943-7
## Bam file processing:
- Subset bam with interested cells: https://kb.10xgenomics.com/hc/en-us/articles/360022448251-How-to-filter-the-BAM-file-produced-by-10x-pipelines-with-a-list-of-barcodes-

## TCR-seq analysis
- scRepertoire: https://ncborcherding.github.io/vignettes/vignette.html

## scRNAseq data simulator
- Splatter: Zappia, L., Phipson, B. & Oshlack, A. Splatter: simulation of single-cell RNA sequencing data. Genome Biol 18, 174 (2017). https://doi.org/10.1186/s13059-017-1305-0
- splatPop: Azodi, C.B., Zappia, L., Oshlack, A. et al. splatPop: simulating population scale single-cell RNA sequencing data. Genome Biol 22, 341 (2021). https://doi.org/10.1186/s13059-021-02546-1

## Seq platforms
- CEL-Seq2: Hashimshony, T., Senderovich, N., Avital, G. et al. CEL-Seq2: sensitive highly-multiplexed single-cell RNA-Seq. Genome Biol 17, 77 (2016). https://doi.org/10.1186/s13059-016-0938-8
- Quartz-Seq2: Sasagawa, Y., Danno, H., Takada, H. et al. Quartz-Seq2: a high-throughput single-cell RNA-sequencing method that effectively uses limited sequence reads. Genome Biol 19, 29 (2018). https://doi.org/10.1186/s13059-018-1407-3
- Smart-seq2: 
  Picelli, S., Björklund, Å., Faridani, O. et al. Smart-seq2 for sensitive full-length transcriptome profiling in single cells. Nat Methods 10, 1096–1098 (2013). https://doi.org/10.1038/nmeth.2639- 
  - Ramsköld, D., Luo, S., Wang, YC. et al. Full-length mRNA-Seq from single-cell levels of RNA and individual circulating tumor cells. Nat Biotechnol 30, 777–782 (2012). https://doi.org/10.1038/nbt.2282
- 10X


## Spatial
### Pipeline
- lmweber.org: https://lmweber.org/BestPracticesST/
### DEG
- Cable, D. M., Murray, E., Shanmugam, V., Zhang, S., Zou, L. S., Diao, M., ... & Chen, F. (2022). Cell type-specific inference of differential expression in spatial transcriptomics. Nature Methods, 1-12.
  > C-SIDE: https://github.com/dmcable/spacexr
## Disease association
- With GWAS co-exp: Zhang, M.J., Hou, K., Dey, K.K. et al. Polygenic enrichment distinguishes disease associations of individual cells in single-cell RNA-seq data. Nat Genet 54, 1572–1580 (2022). https://doi.org/10.1038/s41588-022-01167-z
  > scDRS: https://github.com/martinjzhang/scDRS.
- Jagadeesh, K.A., Dey, K.K., Montoro, D.T. et al. Identifying disease-critical cell types and cellular processes by integrating single-cell RNA-sequencing and human genetics. Nat Genet 54, 1479–1492 (2022). https://doi.org/10.1038/s41588-022-01187-9

# Multi-omics integration
- Stark, S. G. et al. SCIM: universal single-cell matching with unpaired feature sets. Bioinformatics 36, i919–i927 (2020).

# Databases
- Deeply Integrated human Single-Cell Omics data: https://immunesinglecell.org/


# Current techniques and reviews:
  - Ogbeide, Silvia, et al. "Into the multiverse: advances in single-cell multiomic profiling." Trends in Genetics (2022).https://doi.org/10.1016/j.tig.2022.03.015
![image](https://user-images.githubusercontent.com/19710340/169665170-60d55541-1571-4586-ba30-0a5da50cf89f.png)
![image](https://user-images.githubusercontent.com/19710340/169665211-092743a0-dbe7-4bfc-b983-849f5465afbf.png)
  - Preissl, S., Gaulton, K.J. & Ren, B. Characterizing cis-regulatory elements using single-cell epigenomics. Nat Rev Genet (2022). https://doi.org/10.1038/s41576-022-00509-1


# Single-cell ATACseq: 
- ArchR:Granja, J.M., Corces, M.R., Pierce, S.E. et al. ArchR is a scalable software package for integrative single-cell chromatin accessibility analysis. Nat Genet 53, 403–411 (2021). https://doi.org/10.1038/s41588-021-00790-6
  > https://www.archrproject.com/bookdown/index.html#section
- SnapATAC2: Fang, R., Preissl, S., Li, Y. et al. Comprehensive analysis of single cell ATAC-seq data with SnapATAC. Nat Commun 12, 1337 (2021). https://doi.org/10.1038/s41467-021-21583-9
  > https://github.com/r3fang/SnapATAC
