# HiC_analysis

Part1 BL-HiC data
=

Setp1 ChIA-PET2 generate result.rmdup.bedpe
---
    /home/ZJRen/public2/m6AvsHiC/tools/ChIA-PET2-master/bin/ChIA-PET2 -g /public2/ZJRen/m6AvsHiC/tools/hg19/hg19_genome -b /public2/ZJRen/m6AvsHiC/tools/hg19/hg19_size.bed -f Control_BL-HiC_rep1_R1.fastq -r Control_BL-HiC_rep1_R2.fastq -A ACGCGATATCTTATC -B AGTCAGATAAGATAT -s 1 -m 1 -t 4 -k 2 -e 1 -l 15 -S 500 -n Control_BL-HiC_rep1_ChIAPET2_result -o ./Control_BL-HiC_rep1_ChIAPET2

    /home/ZJRen/public2/m6AvsHiC/tools/ChIA-PET2-master/bin/ChIA-PET2 -g /public2/ZJRen/m6AvsHiC/tools/hg19/hg19_genome -b /public2/ZJRen/m6AvsHiC/tools/hg19/hg19_size.bed -f Control_BL-HiC_rep2_R1.fastq -r Control_BL-HiC_rep2_R2.fastq -A ACGCGATATCTTATC -B AGTCAGATAAGATAT -s 1 -m 1 -t 4 -k 2 -e 1 -l 15 -S 500 -n Control_BL-HiC_rep2_ChIAPET2_result -o ./Control_BL-HiC_rep2_ChIAPET2

|chrom1|   start1|     end1|chrom2|   start2|     end2|    readname | value | strand1 | strand2 |
|:-----|:--------|:--------|:-----|:--------|:--------|:------------|:------|:--------|:--------|
| chr6 |108511370|108511520| chr6 |114767868|114767929|SRR7868823.2 | .     | +       | -       |       
| chr6 |102492337|102492414| chr6 |102499445|102499560|SRR7868823.90| .     | -       | +       |       
  
  




