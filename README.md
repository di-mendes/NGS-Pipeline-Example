#Bash pipeline
#Have the directories set:
#dnaseq/
#  ├── results/
#  ├── data/
#        ├── untrimmed_fastq
#        ├── trimmed_fastq
#        ├── reference
#        ├── aligned_data
#annotation file in reference: wget https://s3-eu-west-1.amazonaws.com/workshopdata2017/annotation.bed
#have the fastqs in untrimmed_fastq: wget https://s3-eu-west-1.amazonaws.com/workshopdata2017/NGS0001.R1.fastq.qz 
#                                    wget https://s3-eu-west-1.amazonaws.com/workshopdata2017/NGS0001.R2.fastq.qz
#have hg19 reference genome in reference: wget http://hgdownload.cse.ucsc.edu/goldenPath/hg19/bigZips/hg19.fa.gz
