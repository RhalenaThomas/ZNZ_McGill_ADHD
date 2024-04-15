# ZNZ_McGill_ADHD
analysis of single cell sequencing data

# this repo will contain:

on going anaysis scripts for single cell sequencing of pooled samples

1. May 6th pilot data after demultiplexing: Workbook file name is "CheckNPCpiplot13lines_June28"
   a) Clustering and annotation
   b) adding meta data
   c) DGE between various groups.

2. Analysis of all 4 pools.
  a) Demultiplexing was run and annotations added
  b) Up to step 7 in scRNAbox was run.  The two NSC and two FCN pools were combined and integrated for batch effect.  https://neurobioinfo.github.io/scrnabox/site/ read documentation.
  Two annotate these files we look at : Known marker gene expression visually and with Module scores and at top markers, and with predictions from reference data. This is a large amount of data and cannot be shared here. The top marker data was analyzed using EnrichR
  c) analysis of the top markers using enricher can be found here:
          NSCs "GetEnricherMarkers.Rmd" 
          FCNs "GetEnricherMarkersFCN.Rmd"
          
  d) once the cell types were annotated we had several clusters with the same main cell type.  We defined cell type marker genes using FindMarkers comparing the clusters with the same main cell type.  This is found in the workbook "GetEnricherMarkers.Rmd"
  
I can share the data on onedrive.

e) The differential gene expression still needs to be performed. 
    