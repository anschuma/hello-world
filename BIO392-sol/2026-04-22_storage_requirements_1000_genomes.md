# Estimated storage requirements for 1000 genomes 
## WES & WGS
- WES: Whole exome sequencing -> only 1-2% of the whole human genome are covered, which are ~30Mb per genome
  - for 1000 genomes: 30000Mb
- WGS: Whole genome sequencing -> The whole human genome is covered -> 3000Mb per genome
  - for 1000 genomes: 3000000Mb
## File formats
### SAM
- Sequence Alingment Map
- Text based -> readable for humans but very big
- storage requirements per genome (WGS): up to 500GB
### BAM
- Binary SAM
- not readable for humans but smaller than SAM (compressed)
- storage requirements per genome (WGS): up to 55GB
### VCF
- Variant Call Format
- Only contains variant calls -> small
- storage requirements per genome (WGS): ~3GB 
### FASTA
- Contains assembled reference genome
- storage requirements per genome (WGS): ~3GB
