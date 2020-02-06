# ChIPseq-Differential-Binding-Analysis

This pipeline uses Diffbind to make the common peakset across conditions. However, it uses DEseq2 instead of Diffbind to identify differentially bound genomic regions. 

#Outline of pipeline

    1. Setup MACS2 environment
    2. Peak calling with MACS2
    3. Validate peakcalling via genome browser
    4. Generate consensus peak set with Diffbind
    5. Remove black-listed regions by bedtools
    6. Count reads within peaks by bedtools
    7. Perform differential bindign analysis with DEseq2
    
