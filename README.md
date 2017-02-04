# 1000GenomesDUF1220-variationRD
Analysis of DUF1220 variation in a subset of 1000Genomes samples by read depth

## 1. Analyze effect of sequencing center on DUF1220 copy number (before and after correcting for population)
Run scripts/effect-of-center-and-pop.Rmd  
  To View results, download: scripts/effect-of-center-and-pop.html and click on the file.  The file will open in your browser  
  
  https://github.com/IleaHeft/1000GenomesDUF1220-variationRD/blob/master/scripts/effect-of-center-and-pop.nb.html

**Based on results of sequencing center analysis, might need to:**
- Exclude samples sequenced at ILLUMINA, BGI, AND BI  
- Issue with ILLUMINA sample might be resolvable by adding more samples

## 2. Summarise observed variation in DUF1220 at different levels (e.g. total, clade, gene-specific clade groups, and by population)
**Note:**
- REMOVING samples sequenced at BCM from variation analysis because of poor correlation between read depth and ddPCR for these samples  
- REMOVING samples sequenced at ILLUMINA from variation analysis because violation of homoscedasticity (might just be because of small sample size - could retest this with more samples an if looks good, coule possibly add these samples back into the analysis)  

