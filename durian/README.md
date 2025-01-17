# Telomere-to-Telomere(T2T) assembly of the durian genome


## Data


### Data coverage statistics
||Coverage|
|-|-|
|PacBio Hifi|~60x|
|UL ONT(>100kbp)|~30x|
|OMNI-C|~60x|

 
 
# Assembly  releases 
## Reference
For assembly evaluation, the current Durian [reference](https://www.nature.com/articles/ng.3972) was used.


## v0.1

The assembly was created using hifiasm utilizing Hi-C reads to produce a phased diploid assembly.

Haplotype 1 is available at [link](https://durianreferencelbcb.s3.eu-central-1.amazonaws.com/durian.hifiasm.hic.ulont100.asm.hic.hap1.p_ctg.fa)

Haplotype 2 is available at [link](https://durianreferencelbcb.s3.eu-central-1.amazonaws.com/durian.hifiasm.hic.ulont100.asm.hic.hap2.p_ctg.fa)
 
 
| | Haplotype 1 | Haplotype 2 |
|--------|---------|--------|
| NG50 | 20.685.927 | 21.459.630 |
| # contigs | 599 | 353 |
| # contigs >= 3Mbp | 45 | 45 |
| # contigs* with TR** at the beginning and ending | 12 | 11 |
| # contigs* with TR** at the beginning | 20 | 15 |
| # contigs* with TR** at the ending | 8 | 13 |
| # contigs* with no TR** at the beginning and ending | 5 | 6 |

contigs* - contigs larger or equal to 3Mbp

TR** - tandem repeats

### D-Genies plots - assemblies vs reference
![](https://github.com/lbcb-sci/T2T-assemblies/blob/main/data/v0.1-assembly-to-reference.png)

# Assembly  releases 
## v0.2

The assembly was created using hifiasm utilizing Hi-C reads to produce a phased diploid assembly.

Haplotype 1 is available at [link](https://durianreferencelbcb.s3.eu-central-1.amazonaws.com/hifiasm_err_corr_100k_nochim.asm.hic.hap1.p_ctg.fa)

Haplotype 2 is available at [link](https://durianreferencelbcb.s3.eu-central-1.amazonaws.com/hifiasm_err_corr_100k_nochim.asm.hic.hap2.p_ctg.fa)

Hifi reads were beforehand procured using [DeepConsensus](https://github.com/google/deepconsensus).

[Merlion](https://github.com/lbcb-sci/merlion) was used to detect UL ONT chimeric reads.


|Reads longer than 100kbp| Chimeric reads | % of chimeric reads |
|------------------------|----------------|---------------------|
|139.949|49.346|35,26|
 
 
| | Haplotype 1 | Haplotype 2 |
|--------|---------|--------|     
| NG50 | 21.458.057 | 22.634.734 |
| # contigs | 370 | 299 |
| # contigs >= 3Mbp | 43 | 40 |
| # contigs* with TR** at the beginning and ending | 13 | 14 |
| # contigs* with TR** at the beginning | 15 | 14 |
| # contigs* with TR** at the ending | 10 | 8 |
| # contigs* with no TR** at the beginning and ending | 5 | 4 |

contigs* - contigs larger or equal to 3Mbp

TR** - tandem repeats


### D-Genies plots - assemblies vs reference
![](https://github.com/lbcb-sci/T2T-assemblies/blob/main/data/v0.2-assembly-to-reference.png)

