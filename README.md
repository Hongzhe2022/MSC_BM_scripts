# MSC_BM_scripts

Here we present the scripts used to process the MSC_BM data published on the [NCBI GEO GSE190965](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE190965) as well as [BioRxiv](https://www.biorxiv.org/content/10.1101/2022.01.26.477664v1).

All script are in the scripts sub-folder, both as python notebooks (.ipynb) and html pages. Due to inline graphics these are too big to show here. You need to download them and load the local copies.
 
The data has been processed in three steps:
1. Combining the loom files created during mapping of the data using kallist/bustools filtering and normalization: [Hongze_healthy_2020_10_merged](./scripts/Hongze_healthy_2020_10_merged.ipynb)
2. 2D UMAP, clustering and downstream analysis: [Hongze_healthy_2020_10_merged_2D](./scipts/Hongze_healthy_2020_10_merged_2D.ipynb)
3. Figures and analyses for the paper: [20220328revision]( scripts/20220328revision.ipynb)
4. Removal of doublets [DubletSearch](scripts/DubletSearch.iypnb)
4. Analysis of doublet removed data [DoubletRemoved](scripts/DoubletRemoved.ipynb)
5. The Female vs male comparison [Female_male20220316]( scripts/Female_male20220316.ipynb)



