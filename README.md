CQS Bioinformatics Software Suite
==
* [Introduction](#Introduction)
* [Prerequisites](#Prerequisites)
* [Installation](#Installation)
* [Changes](#changes)

<a name="Introduction"/>
#Introduction

CQS bioinformatics software suite (cqstools) contains a bunch of tools used in genomics research, from preprocessing, format conversion, counting, summarizing to annotation, et al.

<a name="Prerequisites"/>
#Prerequisites
Although cqstools is developed by C#, it is majorly executed under linux through [mono] (https://github.com/mono/mono). So mono on your linux system is required for cqstools.

<a name="Installation"/>
#Installation
###Binary File
User can download compiled version from [github](https://github.com/shengqh/CQS.Tools/releases). Download the file and decompress it to any folder you want, run "mono CQS.Tools.exe" and have fun.

<a name="Changes"/>
#Changes

|Date|Version|Description|
|---|---|---|
|20141124| v1.4.9|New feature: impute2_distiller: extract target SNP from impute2 result|
|20141103| v1.4.8|New feature: unmapped_reads: extract unmapped read information|
|20141023| v1.4.7|Enhanced: mirna_nta_table: summerize miRNA count based on NTA and offset|
|20141013| v1.4.6|Enhanced: fastq_mirna: add information to record the trimmed nucleotides|
|20140912| v1.4.5|New feature: fastq_mirna: trimming last 1,2,3 bases from fastq file for miRNA analysis|
|20140911| v1.4.4|Enhanced: fastq_trimmer: can filter reads less than minimum length|
|20140829| v1.4.3|New feature: Chomosome count builder: group mapped reads based on chromosome, it is used for miRBase mapping result analysis now|
|20140703| v1.4.0|New feature: DepthProcessor: filter samtools depth result|
|20140624| v1.3.9|New feature: AlleleCountBuilder: extract allele count from bam file based on locus in VCF file|
|20140623| v1.3.8|Enhanced: Can use directory name as ID of file in file_def tool|
|20140326| v1.3.7|Enhanced: Can remove 'N' from both 5' and 3' of read when demultiplexing file|
|20140312| v1.3.6|New feature: RockhopperSummaryBuilder|