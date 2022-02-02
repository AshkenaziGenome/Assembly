# Ashkenazi Genome Assembly
This repository contains links to the Ashkenazi reference genome Ash1 assembly and annotation.  Ash1 is an assembly of an individual from Personal Genome Project codename HG002.
This repository has the initial version 1.7 assembly and all subsequent versions.

# Version 1.7
This is an initial version described in:

`Shumate A, Zimin AV, Sherman RM, Puiu D, Wagner JM, Olson ND, Pertea M, Salit ML, Zook JM, Salzberg SL. Assembly and annotation of an Ashkenazi human reference genome. Genome biology. 2020 Dec;21(1):1-8.` 

The article is available online at https://genomebiology.biomedcentral.com/articles/10.1186/s13059-020-02047-7

The sequence for the version 1.7 is available at these locations:

* https://ashkenazi-genome.s3.us-east-2.amazonaws.com/Assembly/index.html
* ftp://ftp.ccb.jhu.edu/pub/data/Homo_sapiens/Ash1/v1.7/Assembly/Ash1v1.7.fa.gz

# Version 2.0
This assembly is much more contiguous, containing only 660 contigs on the chromosomes, compared to 1538 in v1.7. This version has been built using the same software that has been used for v1.7 and described in the manuscript. It fixes several Mbp of spuriously duplicated sequence on chr9 and chr15 in v1.7.  The new version is based on reconciliation of assemblies produced from PacBio Hifi data with HiFiasm (https://arxiv.org/abs/2008.01237), along with a de novo MaSuRCA assembly of the latest Nanopore ultralong and Illumina data.  We filled gaps in chr8 and chrX using sequence from T2T consortium assemblies of CHM13 chromsomes X and 8 (https://www.nature.com/articles/s41586-020-2547-7_reference.pdf?proof=t, https://www.biorxiv.org/content/10.1101/2020.09.08.285395v1.full.pdf). Where possible, we filled gaps in the other chromosomes with sequence from GRCh38.p12, as described in the Ash1 manuscript.  The filled-in sequence that did not originate from HG002 individual is in lowercase letters. Here is the table comparing total size and number of contigs for each chromosome in v1.7 and v2.0 (N's are excluded for the total size computation):

|chromosome|GRCh38 # of contigs|GRCh38 size|v1.7 # of contigs|v1.7 size|v2.0 # of contigs|v2.0 size|
|----|----|----|----|----|----|----|
|chr1|165|230481014|194|232280045|43|232941810|
|chr2|25|240548237|67|241581444|28|241088594|
|chr3|21|198100142|58|199411976|22|198455190|
|chr4|17|189752667|19|190408510|32|190204789|
|chr5|35|178983193|63|181608321|28|180895704|
|chr6|14|170078523|24|170304801|20|171372493|
|chr7|16|158970135|67|160669899|43|160515359|
|chr8|11|144768136|16|144953907|1|146254838|
|chr9|42|121790553|111|122110712|51|123538660|
|chr10|43|133262998|42|134496302|12|133833314|
|chr11|16|134533742|73|135108547|17|136232750|
|chr12|26|133137819|83|135338731|17|133697965|
|chr13|19|97983128|58|98916572|18|98729624|
|chr14|11|88518101|50|90842875|12|93076130|
|chr15|18|84641325|35|91928716|41|86713045|
|chr16|20|81805944|65|82665194|42|85756159|
|chr17|35|82920216|31|83177337|27|84436288|
|chr18|60|80089605|73|81463364|51|80379216|
|chr19|5|55766397|17|67231982|12|57878605|
|chr20|89|63944257|122|65005954|60|64533361|
|chr21|35|38038574|81|40375064|45|39752918|
|chr22|26|37071985|118|42624612|10|37016933|
|chrX|28|154893034|38|153528413|1|154267970|
|chrY|50|23636355|33|27085372|27|27625515|
|chrM|1|16570|1|16570|1|16570|
|Total|827|2923732650|1538|2973135220|660|2959213800| 

The sequence for the version 2.0 is available at this location:

* ftp://ftp.ccb.jhu.edu/pub/data/Homo_sapiens/Ash1/v2.0/Assembly/Ash1_v2.0.fa.gz

# Version 2.2

This assembly contains the gapless chromosomes

|chromosome|v2.2 # of contigs|v2.2 size|
|----|----|----|
|chr1|1|249932541|
|chr2|1|242681487|
|chr3|1|200930272|
|chr4|1|193567215|
|chr5|1|181993881|
|chr6|1|172048152|
|chr7|1|160402684|
|chr8|1|146266741|
|chr9|1|150154455|
|chr10|1|134598001|
|chr11|1|134959473|
|chr12|1|133349155|
|chr13|1|113854012|
|chr14|1|101252837|
|chr15|1|100063229|
|chr16|1|96402991|
|chr17|1|83977505|
|chr18|1|80314204|
|chr19|1|61576862|
|chr20|1|66010062|
|chr21|1|44899981|
|chr22|1|51454416|
|chrX|1|154349815|
|chrY|1|62460029|
|chrM|1|16570|
|Total|25|3117516570|

The sequence for the version 2.2 is available at this location:

* ftp://ftp.ccb.jhu.edu/pub/data/Homo_sapiens/Ash1/v2.2/Assembly/Ash1_v2.2.fa.gz
