<STRONG>MATERIALS</STRONG>

Merely all the records selected for this study were derived manually from Gene Expression Omnibus (GEO), ArrayExpress, and BioProject. 
Exclusively, raw RNA-seq was obtained from the NCBI Sequence Read Archive (SRA). 
All samples were analysed on microarrays and with RNA-sequencing. 
SRA files were converted to FASTQ format using fasterq-dump (SRA Toolkit) with flags --split-files --skip-technical, followed by compression using pigz. 
Library layout was confirmed as single-end for all samples based on fasterq-dump output (absence of _1/_2 paired-end files).
The dataset comprises both pooled and individual biological samples. 
Pooled samples, where material from multiple donors was combined prior to hybridization, are treated as a single biological replicate (n=1). 
Although pooling reduces between-donor variance and may provide a more stable estimate of mean population expression (Kendziorski et al., 2005), 
a single pooled array yields only one expression vector per gene, precluding estimation of biological variance. 
Consequently, assigning n=1 reflects the number of statistically independent observations available, not the number of donors contributing to the pool.
Of all the entries, some experiments are on dual-channel matrices.
