# Ashkenazi Genome Assembliy
This repository contains links to the Ashkenazi reference genome Ash1 assembly and annotation.  Ash1 is an assembly of an individual from Personal Genome Project codename HG002.
This repository has the initial version 1.7 assembly and all subsequent versions.

# Version 1.7
This is an initial version described in:

`Shumate A, Zimin AV, Sherman RM, Puiu D, Wagner JM, Olson ND, Pertea M, Salit ML, Zook JM, Salzberg SL. Assembly and annotation of an Ashkenazi human reference genome. Genome biology. 2020 Dec;21(1):1-8.`

This version is available here:

* Ash1 v1.7: [AWS](https://ashkenazi-genome.s3.us-east-2.amazonaws.com/Assembly/index.html) or ftp://ftp.ccb.jhu.edu/pub/data/Homo_sapiens/Ash1/v1.7/Assembly/

# Version 2.0
This version has been built using the same software that has been used for v1.7 and described in the manuscript.  This assembly is much more contiguous, containing only 660 contigs on the chromosomes, compared to 1538 in v1.7.  It fixes several Mbp of spuriously duplicated sequence on chr9 and chr15 in v1.7.  The new version is based on reconciliation of assemblies produced from PacBio Hifi data with HiFiasm (https://arxiv.org/abs/2008.01237), along with a MaSuRCA assembly of Nanopore and Illumina data.  We filled gaps in chr8 and chrX using sequence from T2T consortium assemblies of CHM13 chromsomes X and 8 (https://www.nature.com/articles/s41586-020-2547-7_reference.pdf?proof=t, https://www.biorxiv.org/content/10.1101/2020.09.08.285395v1.full.pdf). Where possible, we filled gaps in the other chromosomes with sequence from GRCh38.p12, as described in the Ash1 manuscript.  The filled-in sequence that did not originale from HG002 individual is in lowercase letters. Here is the table comparing total size and number of contigs for each chromosome in v1.7 and v2.0:

|chromosome|v1.7 # of contigs|v1.7 total size|v2.0 # of contigs|v2.0 total size|
|----|----|----|----|----|
|chr1|194|232280045|43|232941810|
|chr2|67|241581444|28|241088594|
|chr3|58|199411976|22|198455190|
|chr4|19|190408510|32|190204789|
|chr5|63|181608321|28|180895704|
|chr6|24|170304801|20|171372493|
|chr7|67|160669899|43|160515359|
|chr8|16|144953907|1|146254838|
|chr9|111|122110712|51|123538660|
|chr10|42|134496302|12|133833314|
|chr11|73|135108547|17|136232750|
|chr12|83|135338731|17|133697965|
|chr13|58|98916572|18|98729624|
|chr14|50|90842875|12|93076130|
|chr15|35|91928716|41|86713045|
|chr16|65|82665194|42|85756159|
|chr17|31|83177337|27|84436288|
|chr18|73|81463364|51|80379216|
|chr19|17|67231982|12|57878605|
|chr20|122|65005954|60|64533361|
|chr21|81|40375064|45|39752918|
|chr22|118|42624612|10|37016933|
|chrX|38|153528413|1|154267970|
|chrY|33|27085372|27|27625515|
|Total|1538|2973118650|660|2959197230| 

This version, along with an updated annotation will be available for download shortly.

