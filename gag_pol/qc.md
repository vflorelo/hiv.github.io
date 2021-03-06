Quality assesment
=================
Quality and length based trimming
---------------------------------
We used [sickle](https://github.com/najoshi/sickle) to discard reads with a phred score of 28 or lower and a length of less than 190 nucleotides. In order to optimize the assembly process, we removed redundant reads using [fastuniq](http://sourceforge.net/projects/fastuniq/) [[ref](https://pubmed.ncbi.nlm.nih.gov/23284954/)].

NGS-quality was inspected using fastQC [[ref](https://www.bioinformatics.babraham.ac.uk/projects/fastqc/)] for the full, filtered and non-redundant datasets.

|Sample|Forward reads|Reverse reads|
|:----:|:-----------:|:-----------:|
|1|[Full dataset](qc/1_S1_L001_R1_001_fastqc.html)|[Full dataset](qc/1_S1_L001_R2_001_fastqc.html)|
|1|[Filtered dataset](qc/1_R1_fastqc.html)|[Filtered dataset](qc/1_R2_fastqc.html)|
|1|[Non-redundant dataset](qc/1_R1_nr_fastqc.html)|[Non-redundant dataset](qc/1_R2_nr_fastqc.html)|
|2|[Full dataset](qc/2_S2_L001_R1_001_fastqc.html)|[Full dataset](qc/2_S2_L001_R2_001_fastqc.html)|
|2|[Filtered dataset](qc/2_R1_fastqc.html)|[Filtered dataset](qc/2_R2_fastqc.html)|
|2|[Non-redundant dataset](qc/2_R1_nr_fastqc.html)|[Non-redundant dataset](qc/2_R2_nr_fastqc.html)|
|3|[Full dataset](qc/3_S3_L001_R1_001_fastqc.html)|[Full dataset](qc/3_S3_L001_R2_001_fastqc.html)|
|3|[Filtered dataset](qc/3_R1_fastqc.html)|[Filtered dataset](qc/3_R2_fastqc.html)|
|3|[Non-redundant dataset](qc/3_R1_nr_fastqc.html)|[Non-redundant dataset](qc/3_R2_nr_fastqc.html)|
|5|[Full dataset](qc/5_S4_L001_R1_001_fastqc.html)|[Full dataset](qc/5_S4_L001_R2_001_fastqc.html)|
|5|[Filtered dataset](qc/5_R1_fastqc.html)|[Filtered dataset](qc/5_R2_fastqc.html)|
|5|[Non-redundant dataset](qc/5_R1_nr_fastqc.html)|[Non-redundant dataset](qc/5_R2_nr_fastqc.html)|
|6|[Full dataset](qc/6_S5_L001_R1_001_fastqc.html)|[Full dataset](qc/6_S5_L001_R2_001_fastqc.html)|
|6|[Filtered dataset](qc/6_R1_fastqc.html)|[Filtered dataset](qc/6_R2_fastqc.html)|
|6|[Non-redundant dataset](qc/6_R1_nr_fastqc.html)|[Non-redundant dataset](qc/6_R2_nr_fastqc.html)|
|8|[Full dataset](qc/8_S6_L001_R1_001_fastqc.html)|[Full dataset](qc/8_S6_L001_R2_001_fastqc.html)|
|8|[Filtered dataset](qc/8_R1_fastqc.html)|[Filtered dataset](qc/8_R2_fastqc.html)|
|8|[Non-redundant dataset](qc/8_R1_nr_fastqc.html)|[Non-redundant dataset](qc/8_R2_nr_fastqc.html)|
|11|[Full dataset](qc/11_S7_L001_R1_001_fastqc.html)|[Full dataset](qc/11_S7_L001_R2_001_fastqc.html)|
|11|[Filtered dataset](qc/11_R1_fastqc.html)|[Filtered dataset](qc/11_R2_fastqc.html)|
|11|[Non-redundant dataset](qc/11_R1_nr_fastqc.html)|[Non-redundant dataset](qc/11_R2_nr_fastqc.html)|
|16|[Full dataset](qc/16_S8_L001_R1_001_fastqc.html)|[Full dataset](qc/16_S8_L001_R2_001_fastqc.html)|
|16|[Filtered dataset](qc/16_R1_fastqc.html)|[Filtered dataset](qc/16_R2_fastqc.html)|
|16|[Non-redundant dataset](qc/16_R1_nr_fastqc.html)|[Non-redundant dataset](qc/16_R2_nr_fastqc.html)|
|17|[Full dataset](qc/17_S9_L001_R1_001_fastqc.html)|[Full dataset](qc/17_S9_L001_R2_001_fastqc.html)|
|17|[Filtered dataset](qc/17_R1_fastqc.html)|[Filtered dataset](qc/17_R2_fastqc.html)|
|17|[Non-redundant dataset](qc/17_R1_nr_fastqc.html)|[Non-redundant dataset](qc/17_R2_nr_fastqc.html)|
|23|[Full dataset](qc/23_S10_L001_R1_001_fastqc.html)|[Full dataset](qc/23_S10_L001_R2_001_fastqc.html)|
|23|[Filtered dataset](qc/23_R1_fastqc.html)|[Filtered dataset](qc/23_R2_fastqc.html)|
|23|[Non-redundant dataset](qc/23_R1_nr_fastqc.html)|[Non-redundant dataset](qc/23_R2_nr_fastqc.html)|
|24|[Full dataset](qc/24_S11_L001_R1_001_fastqc.html)|[Full dataset](qc/24_S11_L001_R2_001_fastqc.html)|
|24|[Filtered dataset](qc/24_R1_fastqc.html)|[Filtered dataset](qc/24_R2_fastqc.html)|
|24|[Non-redundant dataset](qc/24_R1_nr_fastqc.html)|[Non-redundant dataset](qc/24_R2_nr_fastqc.html)|
|25|[Full dataset](qc/25_S12_L001_R1_001_fastqc.html)|[Full dataset](qc/25_S12_L001_R2_001_fastqc.html)|
|25|[Filtered dataset](qc/25_R1_fastqc.html)|[Filtered dataset](qc/25_R2_fastqc.html)|
|25|[Non-redundant dataset](qc/25_R1_nr_fastqc.html)|[Non-redundant dataset](qc/25_R2_nr_fastqc.html)|
|26|[Full dataset](qc/26_S13_L001_R1_001_fastqc.html)|[Full dataset](qc/26_S13_L001_R2_001_fastqc.html)|
|26|[Filtered dataset](qc/26_R1_fastqc.html)|[Filtered dataset](qc/26_R2_fastqc.html)|
|26|[Non-redundant dataset](qc/26_R1_nr_fastqc.html)|[Non-redundant dataset](qc/26_R2_nr_fastqc.html)|
|27|[Full dataset](qc/27_S14_L001_R1_001_fastqc.html)|[Full dataset](qc/27_S14_L001_R2_001_fastqc.html)|
|27|[Filtered dataset](qc/27_R1_fastqc.html)|[Filtered dataset](qc/27_R2_fastqc.html)|
|27|[Non-redundant dataset](qc/27_R1_nr_fastqc.html)|[Non-redundant dataset](qc/27_R2_nr_fastqc.html)|
|28|[Full dataset](qc/28_S15_L001_R1_001_fastqc.html)|[Full dataset](qc/28_S15_L001_R2_001_fastqc.html)|
|28|[Filtered dataset](qc/28_R1_fastqc.html)|[Filtered dataset](qc/28_R2_fastqc.html)|
|28|[Non-redundant dataset](qc/28_R1_nr_fastqc.html)|[Non-redundant dataset](qc/28_R2_nr_fastqc.html)|
|30|[Full dataset](qc/30_S16_L001_R1_001_fastqc.html)|[Full dataset](qc/30_S16_L001_R2_001_fastqc.html)|
|30|[Filtered dataset](qc/30_R1_fastqc.html)|[Filtered dataset](qc/30_R2_fastqc.html)|
|30|[Non-redundant dataset](qc/30_R1_nr_fastqc.html)|[Non-redundant dataset](qc/30_R2_nr_fastqc.html)|
|33|[Full dataset](qc/33_S17_L001_R1_001_fastqc.html)|[Full dataset](qc/33_S17_L001_R2_001_fastqc.html)|
|33|[Filtered dataset](qc/33_R1_fastqc.html)|[Filtered dataset](qc/33_R2_fastqc.html)|
|33|[Non-redundant dataset](qc/33_R1_nr_fastqc.html)|[Non-redundant dataset](qc/33_R2_nr_fastqc.html)|
|39|[Full dataset](qc/39_S18_L001_R1_001_fastqc.html)|[Full dataset](qc/39_S18_L001_R2_001_fastqc.html)|
|39|[Filtered dataset](qc/39_R1_fastqc.html)|[Filtered dataset](qc/39_R2_fastqc.html)|
|39|[Non-redundant dataset](qc/39_R1_nr_fastqc.html)|[Non-redundant dataset](qc/39_R2_nr_fastqc.html)|
|42|[Full dataset](qc/42_S19_L001_R1_001_fastqc.html)|[Full dataset](qc/42_S19_L001_R2_001_fastqc.html)|
|42|[Filtered dataset](qc/42_R1_fastqc.html)|[Filtered dataset](qc/42_R2_fastqc.html)|
|42|[Non-redundant dataset](qc/42_R1_nr_fastqc.html)|[Non-redundant dataset](qc/42_R2_nr_fastqc.html)|
|43|[Full dataset](qc/43_S20_L001_R1_001_fastqc.html)|[Full dataset](qc/43_S20_L001_R2_001_fastqc.html)|
|43|[Filtered dataset](qc/43_R1_fastqc.html)|[Filtered dataset](qc/43_R2_fastqc.html)|
|43|[Non-redundant dataset](qc/43_R1_nr_fastqc.html)|[Non-redundant dataset](qc/43_R2_nr_fastqc.html)|
|44|[Full dataset](qc/44_S21_L001_R1_001_fastqc.html)|[Full dataset](qc/44_S21_L001_R2_001_fastqc.html)|
|44|[Filtered dataset](qc/44_R1_fastqc.html)|[Filtered dataset](qc/44_R2_fastqc.html)|
|44|[Non-redundant dataset](qc/44_R1_nr_fastqc.html)|[Non-redundant dataset](qc/44_R2_nr_fastqc.html)|
|45|[Full dataset](qc/45_S22_L001_R1_001_fastqc.html)|[Full dataset](qc/45_S22_L001_R2_001_fastqc.html)|
|45|[Filtered dataset](qc/45_R1_fastqc.html)|[Filtered dataset](qc/45_R2_fastqc.html)|
|45|[Non-redundant dataset](qc/45_R1_nr_fastqc.html)|[Non-redundant dataset](qc/45_R2_nr_fastqc.html)|
|46|[Full dataset](qc/46_S23_L001_R1_001_fastqc.html)|[Full dataset](qc/46_S23_L001_R2_001_fastqc.html)|
|46|[Filtered dataset](qc/46_R1_fastqc.html)|[Filtered dataset](qc/46_R2_fastqc.html)|
|46|[Non-redundant dataset](qc/46_R1_nr_fastqc.html)|[Non-redundant dataset](qc/46_R2_nr_fastqc.html)|
|47|[Full dataset](qc/47_S24_L001_R1_001_fastqc.html)|[Full dataset](qc/47_S24_L001_R2_001_fastqc.html)|
|47|[Filtered dataset](qc/47_R1_fastqc.html)|[Filtered dataset](qc/47_R2_fastqc.html)|
|47|[Non-redundant dataset](qc/47_R1_nr_fastqc.html)|[Non-redundant dataset](qc/47_R2_nr_fastqc.html)|
|48|[Full dataset](qc/48_S25_L001_R1_001_fastqc.html)|[Full dataset](qc/48_S25_L001_R2_001_fastqc.html)|
|48|[Filtered dataset](qc/48_R1_fastqc.html)|[Filtered dataset](qc/48_R2_fastqc.html)|
|48|[Non-redundant dataset](qc/48_R1_nr_fastqc.html)|[Non-redundant dataset](qc/48_R2_nr_fastqc.html)|
|50|[Full dataset](qc/50_S26_L001_R1_001_fastqc.html)|[Full dataset](qc/50_S26_L001_R2_001_fastqc.html)|
|50|[Filtered dataset](qc/50_R1_fastqc.html)|[Filtered dataset](qc/50_R2_fastqc.html)|
|50|[Non-redundant dataset](qc/50_R1_nr_fastqc.html)|[Non-redundant dataset](qc/50_R2_nr_fastqc.html)|
|54|[Full dataset](qc/54_S27_L001_R1_001_fastqc.html)|[Full dataset](qc/54_S27_L001_R2_001_fastqc.html)|
|54|[Filtered dataset](qc/54_R1_fastqc.html)|[Filtered dataset](qc/54_R2_fastqc.html)|
|54|[Non-redundant dataset](qc/54_R1_nr_fastqc.html)|[Non-redundant dataset](qc/54_R2_nr_fastqc.html)|
|55|[Full dataset](qc/55_S28_L001_R1_001_fastqc.html)|[Full dataset](qc/55_S28_L001_R2_001_fastqc.html)|
|55|[Filtered dataset](qc/55_R1_fastqc.html)|[Filtered dataset](qc/55_R2_fastqc.html)|
|55|[Non-redundant dataset](qc/55_R1_nr_fastqc.html)|[Non-redundant dataset](qc/55_R2_nr_fastqc.html)|
|56|[Full dataset](qc/56_S29_L001_R1_001_fastqc.html)|[Full dataset](qc/56_S29_L001_R2_001_fastqc.html)|
|56|[Filtered dataset](qc/56_R1_fastqc.html)|[Filtered dataset](qc/56_R2_fastqc.html)|
|56|[Non-redundant dataset](qc/56_R1_nr_fastqc.html)|[Non-redundant dataset](qc/56_R2_nr_fastqc.html)|
|58|[Full dataset](qc/58_S30_L001_R1_001_fastqc.html)|[Full dataset](qc/58_S30_L001_R2_001_fastqc.html)|
|58|[Filtered dataset](qc/58_R1_fastqc.html)|[Filtered dataset](qc/58_R2_fastqc.html)|
|58|[Non-redundant dataset](qc/58_R1_nr_fastqc.html)|[Non-redundant dataset](qc/58_R2_nr_fastqc.html)|
|59|[Full dataset](qc/59_S31_L001_R1_001_fastqc.html)|[Full dataset](qc/59_S31_L001_R2_001_fastqc.html)|
|59|[Filtered dataset](qc/59_R1_fastqc.html)|[Filtered dataset](qc/59_R2_fastqc.html)|
|59|[Non-redundant dataset](qc/59_R1_nr_fastqc.html)|[Non-redundant dataset](qc/59_R2_nr_fastqc.html)|
|61|[Full dataset](qc/61_S32_L001_R1_001_fastqc.html)|[Full dataset](qc/61_S32_L001_R2_001_fastqc.html)|
|61|[Filtered dataset](qc/61_R1_fastqc.html)|[Filtered dataset](qc/61_R2_fastqc.html)|
|61|[Non-redundant dataset](qc/61_R1_nr_fastqc.html)|[Non-redundant dataset](qc/61_R2_nr_fastqc.html)|
|64|[Full dataset](qc/64_S33_L001_R1_001_fastqc.html)|[Full dataset](qc/64_S33_L001_R2_001_fastqc.html)|
|64|[Filtered dataset](qc/64_R1_fastqc.html)|[Filtered dataset](qc/64_R2_fastqc.html)|
|64|[Non-redundant dataset](qc/64_R1_nr_fastqc.html)|[Non-redundant dataset](qc/64_R2_nr_fastqc.html)|
|65|[Full dataset](qc/65_S34_L001_R1_001_fastqc.html)|[Full dataset](qc/65_S34_L001_R2_001_fastqc.html)|
|65|[Filtered dataset](qc/65_R1_fastqc.html)|[Filtered dataset](qc/65_R2_fastqc.html)|
|65|[Non-redundant dataset](qc/65_R1_nr_fastqc.html)|[Non-redundant dataset](qc/65_R2_nr_fastqc.html)|
|67|[Full dataset](qc/67_S35_L001_R1_001_fastqc.html)|[Full dataset](qc/67_S35_L001_R2_001_fastqc.html)|
|67|[Filtered dataset](qc/67_R1_fastqc.html)|[Filtered dataset](qc/67_R2_fastqc.html)|
|67|[Non-redundant dataset](qc/67_R1_nr_fastqc.html)|[Non-redundant dataset](qc/67_R2_nr_fastqc.html)|
|70|[Full dataset](qc/70_S36_L001_R1_001_fastqc.html)|[Full dataset](qc/70_S36_L001_R2_001_fastqc.html)|
|70|[Filtered dataset](qc/70_R1_fastqc.html)|[Filtered dataset](qc/70_R2_fastqc.html)|
|70|[Non-redundant dataset](qc/70_R1_nr_fastqc.html)|[Non-redundant dataset](qc/70_R2_nr_fastqc.html)|
|71|[Full dataset](qc/71_S37_L001_R1_001_fastqc.html)|[Full dataset](qc/71_S37_L001_R2_001_fastqc.html)|
|71|[Filtered dataset](qc/71_R1_fastqc.html)|[Filtered dataset](qc/71_R2_fastqc.html)|
|71|[Non-redundant dataset](qc/71_R1_nr_fastqc.html)|[Non-redundant dataset](qc/71_R2_nr_fastqc.html)|
|72|[Full dataset](qc/72_S38_L001_R1_001_fastqc.html)|[Full dataset](qc/72_S38_L001_R2_001_fastqc.html)|
|72|[Filtered dataset](qc/72_R1_fastqc.html)|[Filtered dataset](qc/72_R2_fastqc.html)|
|72|[Non-redundant dataset](qc/72_R1_nr_fastqc.html)|[Non-redundant dataset](qc/72_R2_nr_fastqc.html)|
|73|[Full dataset](qc/73_S39_L001_R1_001_fastqc.html)|[Full dataset](qc/73_S39_L001_R2_001_fastqc.html)|
|73|[Filtered dataset](qc/73_R1_fastqc.html)|[Filtered dataset](qc/73_R2_fastqc.html)|
|73|[Non-redundant dataset](qc/73_R1_nr_fastqc.html)|[Non-redundant dataset](qc/73_R2_nr_fastqc.html)|
|78|[Full dataset](qc/78_S40_L001_R1_001_fastqc.html)|[Full dataset](qc/78_S40_L001_R2_001_fastqc.html)|
|78|[Filtered dataset](qc/78_R1_fastqc.html)|[Filtered dataset](qc/78_R2_fastqc.html)|
|78|[Non-redundant dataset](qc/78_R1_nr_fastqc.html)|[Non-redundant dataset](qc/78_R2_nr_fastqc.html)|
|80|[Full dataset](qc/80_S41_L001_R1_001_fastqc.html)|[Full dataset](qc/80_S41_L001_R2_001_fastqc.html)|
|80|[Filtered dataset](qc/80_R1_fastqc.html)|[Filtered dataset](qc/80_R2_fastqc.html)|
|80|[Non-redundant dataset](qc/80_R1_nr_fastqc.html)|[Non-redundant dataset](qc/80_R2_nr_fastqc.html)|
|81|[Full dataset](qc/81_S42_L001_R1_001_fastqc.html)|[Full dataset](qc/81_S42_L001_R2_001_fastqc.html)|
|81|[Filtered dataset](qc/81_R1_fastqc.html)|[Filtered dataset](qc/81_R2_fastqc.html)|
|81|[Non-redundant dataset](qc/81_R1_nr_fastqc.html)|[Non-redundant dataset](qc/81_R2_nr_fastqc.html)|
|82|[Full dataset](qc/82_S43_L001_R1_001_fastqc.html)|[Full dataset](qc/82_S43_L001_R2_001_fastqc.html)|
|82|[Filtered dataset](qc/82_R1_fastqc.html)|[Filtered dataset](qc/82_R2_fastqc.html)|
|82|[Non-redundant dataset](qc/82_R1_nr_fastqc.html)|[Non-redundant dataset](qc/82_R2_nr_fastqc.html)|
|83|[Full dataset](qc/83_S44_L001_R1_001_fastqc.html)|[Full dataset](qc/83_S44_L001_R2_001_fastqc.html)|
|83|[Filtered dataset](qc/83_R1_fastqc.html)|[Filtered dataset](qc/83_R2_fastqc.html)|
|83|[Non-redundant dataset](qc/83_R1_nr_fastqc.html)|[Non-redundant dataset](qc/83_R2_nr_fastqc.html)|
|84|[Full dataset](qc/84_S45_L001_R1_001_fastqc.html)|[Full dataset](qc/84_S45_L001_R2_001_fastqc.html)|
|84|[Filtered dataset](qc/84_R1_fastqc.html)|[Filtered dataset](qc/84_R2_fastqc.html)|
|84|[Non-redundant dataset](qc/84_R1_nr_fastqc.html)|[Non-redundant dataset](qc/84_R2_nr_fastqc.html)|
|G1|[Full dataset](qc/G1_S46_L001_R1_001_fastqc.html)|[Full dataset](qc/G1_S46_L001_R2_001_fastqc.html)|
|G1|[Filtered dataset](qc/G1_R1_fastqc.html)|[Filtered dataset](qc/G1_R2_fastqc.html)|
|G1|[Non-redundant dataset](qc/G1_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G1_R2_nr_fastqc.html)|
|G2|[Full dataset](qc/G2_S47_L001_R1_001_fastqc.html)|[Full dataset](qc/G2_S47_L001_R2_001_fastqc.html)|
|G2|[Filtered dataset](qc/G2_R1_fastqc.html)|[Filtered dataset](qc/G2_R2_fastqc.html)|
|G2|[Non-redundant dataset](qc/G2_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G2_R2_nr_fastqc.html)|
|G3|[Full dataset](qc/G3_S48_L001_R1_001_fastqc.html)|[Full dataset](qc/G3_S48_L001_R2_001_fastqc.html)|
|G3|[Filtered dataset](qc/G3_R1_fastqc.html)|[Filtered dataset](qc/G3_R2_fastqc.html)|
|G3|[Non-redundant dataset](qc/G3_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G3_R2_nr_fastqc.html)|
|G4|[Full dataset](qc/G4_S49_L001_R1_001_fastqc.html)|[Full dataset](qc/G4_S49_L001_R2_001_fastqc.html)|
|G4|[Filtered dataset](qc/G4_R1_fastqc.html)|[Filtered dataset](qc/G4_R2_fastqc.html)|
|G4|[Non-redundant dataset](qc/G4_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G4_R2_nr_fastqc.html)|
|G5|[Full dataset](qc/G5_S50_L001_R1_001_fastqc.html)|[Full dataset](qc/G5_S50_L001_R2_001_fastqc.html)|
|G5|[Filtered dataset](qc/G5_R1_fastqc.html)|[Filtered dataset](qc/G5_R2_fastqc.html)|
|G5|[Non-redundant dataset](qc/G5_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G5_R2_nr_fastqc.html)|
|G6|[Full dataset](qc/G6_S51_L001_R1_001_fastqc.html)|[Full dataset](qc/G6_S51_L001_R2_001_fastqc.html)|
|G6|[Filtered dataset](qc/G6_R1_fastqc.html)|[Filtered dataset](qc/G6_R2_fastqc.html)|
|G6|[Non-redundant dataset](qc/G6_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G6_R2_nr_fastqc.html)|
|G7|[Full dataset](qc/G7_S52_L001_R1_001_fastqc.html)|[Full dataset](qc/G7_S52_L001_R2_001_fastqc.html)|
|G7|[Filtered dataset](qc/G7_R1_fastqc.html)|[Filtered dataset](qc/G7_R2_fastqc.html)|
|G7|[Non-redundant dataset](qc/G7_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G7_R2_nr_fastqc.html)|
|G8|[Full dataset](qc/G8_S53_L001_R1_001_fastqc.html)|[Full dataset](qc/G8_S53_L001_R2_001_fastqc.html)|
|G8|[Filtered dataset](qc/G8_R1_fastqc.html)|[Filtered dataset](qc/G8_R2_fastqc.html)|
|G8|[Non-redundant dataset](qc/G8_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G8_R2_nr_fastqc.html)|
|G9|[Full dataset](qc/G9_S54_L001_R1_001_fastqc.html)|[Full dataset](qc/G9_S54_L001_R2_001_fastqc.html)|
|G9|[Filtered dataset](qc/G9_R1_fastqc.html)|[Filtered dataset](qc/G9_R2_fastqc.html)|
|G9|[Non-redundant dataset](qc/G9_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G9_R2_nr_fastqc.html)|
|G10|[Full dataset](qc/G10_S55_L001_R1_001_fastqc.html)|[Full dataset](qc/G10_S55_L001_R2_001_fastqc.html)|
|G10|[Filtered dataset](qc/G10_R1_fastqc.html)|[Filtered dataset](qc/G10_R2_fastqc.html)|
|G10|[Non-redundant dataset](qc/G10_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G10_R2_nr_fastqc.html)|
|G11|[Full dataset](qc/G11_S56_L001_R1_001_fastqc.html)|[Full dataset](qc/G11_S56_L001_R2_001_fastqc.html)|
|G11|[Filtered dataset](qc/G11_R1_fastqc.html)|[Filtered dataset](qc/G11_R2_fastqc.html)|
|G11|[Non-redundant dataset](qc/G11_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G11_R2_nr_fastqc.html)|
|G12|[Full dataset](qc/G12_S57_L001_R1_001_fastqc.html)|[Full dataset](qc/G12_S57_L001_R2_001_fastqc.html)|
|G12|[Filtered dataset](qc/G12_R1_fastqc.html)|[Filtered dataset](qc/G12_R2_fastqc.html)|
|G12|[Non-redundant dataset](qc/G12_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G12_R2_nr_fastqc.html)|
|G13|[Full dataset](qc/G13_S58_L001_R1_001_fastqc.html)|[Full dataset](qc/G13_S58_L001_R2_001_fastqc.html)|
|G13|[Filtered dataset](qc/G13_R1_fastqc.html)|[Filtered dataset](qc/G13_R2_fastqc.html)|
|G13|[Non-redundant dataset](qc/G13_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G13_R2_nr_fastqc.html)|
|G15|[Full dataset](qc/G15_S59_L001_R1_001_fastqc.html)|[Full dataset](qc/G15_S59_L001_R2_001_fastqc.html)|
|G15|[Filtered dataset](qc/G15_R1_fastqc.html)|[Filtered dataset](qc/G15_R2_fastqc.html)|
|G15|[Non-redundant dataset](qc/G15_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G15_R2_nr_fastqc.html)|
|G16|[Full dataset](qc/G16_S16_L001_R1_001_fastqc.html)|[Full dataset](qc/G16_S16_L001_R2_001_fastqc.html)|
|G16|[Filtered dataset](qc/G16_R1_fastqc.html)|[Filtered dataset](qc/G16_R2_fastqc.html)|
|G16|[Non-redundant dataset](qc/G16_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G16_R2_nr_fastqc.html)|
|G17|[Full dataset](qc/G17_S60_L001_R1_001_fastqc.html)|[Full dataset](qc/G17_S60_L001_R2_001_fastqc.html)|
|G17|[Filtered dataset](qc/G17_R1_fastqc.html)|[Filtered dataset](qc/G17_R2_fastqc.html)|
|G17|[Non-redundant dataset](qc/G17_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G17_R2_nr_fastqc.html)|
|G18|[Full dataset](qc/G18_S61_L001_R1_001_fastqc.html)|[Full dataset](qc/G18_S61_L001_R2_001_fastqc.html)|
|G18|[Filtered dataset](qc/G18_R1_fastqc.html)|[Filtered dataset](qc/G18_R2_fastqc.html)|
|G18|[Non-redundant dataset](qc/G18_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G18_R2_nr_fastqc.html)|
|G19|[Full dataset](qc/G19_S62_L001_R1_001_fastqc.html)|[Full dataset](qc/G19_S62_L001_R2_001_fastqc.html)|
|G19|[Filtered dataset](qc/G19_R1_fastqc.html)|[Filtered dataset](qc/G19_R2_fastqc.html)|
|G19|[Non-redundant dataset](qc/G19_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G19_R2_nr_fastqc.html)|
|G20|[Full dataset](qc/G20_S63_L001_R1_001_fastqc.html)|[Full dataset](qc/G20_S63_L001_R2_001_fastqc.html)|
|G20|[Filtered dataset](qc/G20_R1_fastqc.html)|[Filtered dataset](qc/G20_R2_fastqc.html)|
|G20|[Non-redundant dataset](qc/G20_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G20_R2_nr_fastqc.html)|
|G21|[Full dataset](qc/G21_S64_L001_R1_001_fastqc.html)|[Full dataset](qc/G21_S64_L001_R2_001_fastqc.html)|
|G21|[Filtered dataset](qc/G21_R1_fastqc.html)|[Filtered dataset](qc/G21_R2_fastqc.html)|
|G21|[Non-redundant dataset](qc/G21_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G21_R2_nr_fastqc.html)|
|G22|[Full dataset](qc/G22_S65_L001_R1_001_fastqc.html)|[Full dataset](qc/G22_S65_L001_R2_001_fastqc.html)|
|G22|[Filtered dataset](qc/G22_R1_fastqc.html)|[Filtered dataset](qc/G22_R2_fastqc.html)|
|G22|[Non-redundant dataset](qc/G22_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G22_R2_nr_fastqc.html)|
|G23|[Full dataset](qc/G23_S66_L001_R1_001_fastqc.html)|[Full dataset](qc/G23_S66_L001_R2_001_fastqc.html)|
|G23|[Filtered dataset](qc/G23_R1_fastqc.html)|[Filtered dataset](qc/G23_R2_fastqc.html)|
|G23|[Non-redundant dataset](qc/G23_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G23_R2_nr_fastqc.html)|
|G25|[Full dataset](qc/G25_S67_L001_R1_001_fastqc.html)|[Full dataset](qc/G25_S67_L001_R2_001_fastqc.html)|
|G25|[Filtered dataset](qc/G25_R1_fastqc.html)|[Filtered dataset](qc/G25_R2_fastqc.html)|
|G25|[Non-redundant dataset](qc/G25_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G25_R2_nr_fastqc.html)|
|G26|[Full dataset](qc/G26_S15_L001_R1_001_fastqc.html)|[Full dataset](qc/G26_S15_L001_R2_001_fastqc.html)|
|G26|[Filtered dataset](qc/G26_R1_fastqc.html)|[Filtered dataset](qc/G26_R2_fastqc.html)|
|G26|[Non-redundant dataset](qc/G26_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G26_R2_nr_fastqc.html)|
|G27|[Full dataset](qc/G27_S68_L001_R1_001_fastqc.html)|[Full dataset](qc/G27_S68_L001_R2_001_fastqc.html)|
|G27|[Filtered dataset](qc/G27_R1_fastqc.html)|[Filtered dataset](qc/G27_R2_fastqc.html)|
|G27|[Non-redundant dataset](qc/G27_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G27_R2_nr_fastqc.html)|
|G28|[Full dataset](qc/G28_S69_L001_R1_001_fastqc.html)|[Full dataset](qc/G28_S69_L001_R2_001_fastqc.html)|
|G28|[Filtered dataset](qc/G28_R1_fastqc.html)|[Filtered dataset](qc/G28_R2_fastqc.html)|
|G28|[Non-redundant dataset](qc/G28_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G28_R2_nr_fastqc.html)|
|G29|[Full dataset](qc/G29_S70_L001_R1_001_fastqc.html)|[Full dataset](qc/G29_S70_L001_R2_001_fastqc.html)|
|G29|[Filtered dataset](qc/G29_R1_fastqc.html)|[Filtered dataset](qc/G29_R2_fastqc.html)|
|G29|[Non-redundant dataset](qc/G29_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G29_R2_nr_fastqc.html)|
|G30|[Full dataset](qc/G30_S71_L001_R1_001_fastqc.html)|[Full dataset](qc/G30_S71_L001_R2_001_fastqc.html)|
|G30|[Filtered dataset](qc/G30_R1_fastqc.html)|[Filtered dataset](qc/G30_R2_fastqc.html)|
|G30|[Non-redundant dataset](qc/G30_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G30_R2_nr_fastqc.html)|
|G31|[Full dataset](qc/G31_S72_L001_R1_001_fastqc.html)|[Full dataset](qc/G31_S72_L001_R2_001_fastqc.html)|
|G31|[Filtered dataset](qc/G31_R1_fastqc.html)|[Filtered dataset](qc/G31_R2_fastqc.html)|
|G31|[Non-redundant dataset](qc/G31_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G31_R2_nr_fastqc.html)|
|G32|[Full dataset](qc/G32_S73_L001_R1_001_fastqc.html)|[Full dataset](qc/G32_S73_L001_R2_001_fastqc.html)|
|G32|[Filtered dataset](qc/G32_R1_fastqc.html)|[Filtered dataset](qc/G32_R2_fastqc.html)|
|G32|[Non-redundant dataset](qc/G32_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G32_R2_nr_fastqc.html)|
|G33|[Full dataset](qc/G33_S14_L001_R1_001_fastqc.html)|[Full dataset](qc/G33_S14_L001_R2_001_fastqc.html)|
|G33|[Filtered dataset](qc/G33_R1_fastqc.html)|[Filtered dataset](qc/G33_R2_fastqc.html)|
|G33|[Non-redundant dataset](qc/G33_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G33_R2_nr_fastqc.html)|
|G34|[Full dataset](qc/G34_S74_L001_R1_001_fastqc.html)|[Full dataset](qc/G34_S74_L001_R2_001_fastqc.html)|
|G34|[Filtered dataset](qc/G34_R1_fastqc.html)|[Filtered dataset](qc/G34_R2_fastqc.html)|
|G34|[Non-redundant dataset](qc/G34_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G34_R2_nr_fastqc.html)|
|G35|[Full dataset](qc/G35_S75_L001_R1_001_fastqc.html)|[Full dataset](qc/G35_S75_L001_R2_001_fastqc.html)|
|G35|[Filtered dataset](qc/G35_R1_fastqc.html)|[Filtered dataset](qc/G35_R2_fastqc.html)|
|G35|[Non-redundant dataset](qc/G35_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G35_R2_nr_fastqc.html)|
|G36|[Full dataset](qc/G36_S13_L001_R1_001_fastqc.html)|[Full dataset](qc/G36_S13_L001_R2_001_fastqc.html)|
|G36|[Filtered dataset](qc/G36_R1_fastqc.html)|[Filtered dataset](qc/G36_R2_fastqc.html)|
|G36|[Non-redundant dataset](qc/G36_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G36_R2_nr_fastqc.html)|
|G37|[Full dataset](qc/G37_S76_L001_R1_001_fastqc.html)|[Full dataset](qc/G37_S76_L001_R2_001_fastqc.html)|
|G37|[Filtered dataset](qc/G37_R1_fastqc.html)|[Filtered dataset](qc/G37_R2_fastqc.html)|
|G37|[Non-redundant dataset](qc/G37_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G37_R2_nr_fastqc.html)|
|G38|[Full dataset](qc/G38_S12_L001_R1_001_fastqc.html)|[Full dataset](qc/G38_S12_L001_R2_001_fastqc.html)|
|G38|[Filtered dataset](qc/G38_R1_fastqc.html)|[Filtered dataset](qc/G38_R2_fastqc.html)|
|G38|[Non-redundant dataset](qc/G38_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G38_R2_nr_fastqc.html)|
|G39|[Full dataset](qc/G39_S77_L001_R1_001_fastqc.html)|[Full dataset](qc/G39_S77_L001_R2_001_fastqc.html)|
|G39|[Filtered dataset](qc/G39_R1_fastqc.html)|[Filtered dataset](qc/G39_R2_fastqc.html)|
|G39|[Non-redundant dataset](qc/G39_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G39_R2_nr_fastqc.html)|
|G40|[Full dataset](qc/G40_S11_L001_R1_001_fastqc.html)|[Full dataset](qc/G40_S11_L001_R2_001_fastqc.html)|
|G40|[Filtered dataset](qc/G40_R1_fastqc.html)|[Filtered dataset](qc/G40_R2_fastqc.html)|
|G40|[Non-redundant dataset](qc/G40_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G40_R2_nr_fastqc.html)|
|G41|[Full dataset](qc/G41_S78_L001_R1_001_fastqc.html)|[Full dataset](qc/G41_S78_L001_R2_001_fastqc.html)|
|G41|[Filtered dataset](qc/G41_R1_fastqc.html)|[Filtered dataset](qc/G41_R2_fastqc.html)|
|G41|[Non-redundant dataset](qc/G41_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G41_R2_nr_fastqc.html)|
|G42|[Full dataset](qc/G42_S6_L001_R1_001_fastqc.html)|[Full dataset](qc/G42_S6_L001_R2_001_fastqc.html)|
|G42|[Filtered dataset](qc/G42_R1_fastqc.html)|[Filtered dataset](qc/G42_R2_fastqc.html)|
|G42|[Non-redundant dataset](qc/G42_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G42_R2_nr_fastqc.html)|
|G43|[Full dataset](qc/G43_S79_L001_R1_001_fastqc.html)|[Full dataset](qc/G43_S79_L001_R2_001_fastqc.html)|
|G43|[Filtered dataset](qc/G43_R1_fastqc.html)|[Filtered dataset](qc/G43_R2_fastqc.html)|
|G43|[Non-redundant dataset](qc/G43_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G43_R2_nr_fastqc.html)|
|G44|[Full dataset](qc/G44_S80_L001_R1_001_fastqc.html)|[Full dataset](qc/G44_S80_L001_R2_001_fastqc.html)|
|G44|[Filtered dataset](qc/G44_R1_fastqc.html)|[Filtered dataset](qc/G44_R2_fastqc.html)|
|G44|[Non-redundant dataset](qc/G44_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G44_R2_nr_fastqc.html)|
|G45|[Full dataset](qc/G45_S7_L001_R1_001_fastqc.html)|[Full dataset](qc/G45_S7_L001_R2_001_fastqc.html)|
|G45|[Filtered dataset](qc/G45_R1_fastqc.html)|[Filtered dataset](qc/G45_R2_fastqc.html)|
|G45|[Non-redundant dataset](qc/G45_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G45_R2_nr_fastqc.html)|
|G46|[Full dataset](qc/G46_S8_L001_R1_001_fastqc.html)|[Full dataset](qc/G46_S8_L001_R2_001_fastqc.html)|
|G46|[Filtered dataset](qc/G46_R1_fastqc.html)|[Filtered dataset](qc/G46_R2_fastqc.html)|
|G46|[Non-redundant dataset](qc/G46_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G46_R2_nr_fastqc.html)|
|G48|[Full dataset](qc/G48_S81_L001_R1_001_fastqc.html)|[Full dataset](qc/G48_S81_L001_R2_001_fastqc.html)|
|G48|[Filtered dataset](qc/G48_R1_fastqc.html)|[Filtered dataset](qc/G48_R2_fastqc.html)|
|G48|[Non-redundant dataset](qc/G48_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G48_R2_nr_fastqc.html)|
|G49|[Full dataset](qc/G49_S82_L001_R1_001_fastqc.html)|[Full dataset](qc/G49_S82_L001_R2_001_fastqc.html)|
|G49|[Filtered dataset](qc/G49_R1_fastqc.html)|[Filtered dataset](qc/G49_R2_fastqc.html)|
|G49|[Non-redundant dataset](qc/G49_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G49_R2_nr_fastqc.html)|
|G50|[Full dataset](qc/G50_S9_L001_R1_001_fastqc.html)|[Full dataset](qc/G50_S9_L001_R2_001_fastqc.html)|
|G50|[Filtered dataset](qc/G50_R1_fastqc.html)|[Filtered dataset](qc/G50_R2_fastqc.html)|
|G50|[Non-redundant dataset](qc/G50_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G50_R2_nr_fastqc.html)|
|G51|[Full dataset](qc/G51_S83_L001_R1_001_fastqc.html)|[Full dataset](qc/G51_S83_L001_R2_001_fastqc.html)|
|G51|[Filtered dataset](qc/G51_R1_fastqc.html)|[Filtered dataset](qc/G51_R2_fastqc.html)|
|G51|[Non-redundant dataset](qc/G51_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G51_R2_nr_fastqc.html)|
|G52|[Full dataset](qc/G52_S10_L001_R1_001_fastqc.html)|[Full dataset](qc/G52_S10_L001_R2_001_fastqc.html)|
|G52|[Filtered dataset](qc/G52_R1_fastqc.html)|[Filtered dataset](qc/G52_R2_fastqc.html)|
|G52|[Non-redundant dataset](qc/G52_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G52_R2_nr_fastqc.html)|
|G53|[Full dataset](qc/G53_S4_L001_R1_001_fastqc.html)|[Full dataset](qc/G53_S4_L001_R2_001_fastqc.html)|
|G53|[Filtered dataset](qc/G53_R1_fastqc.html)|[Filtered dataset](qc/G53_R2_fastqc.html)|
|G53|[Non-redundant dataset](qc/G53_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G53_R2_nr_fastqc.html)|
|G56|[Full dataset](qc/G56_S5_L001_R1_001_fastqc.html)|[Full dataset](qc/G56_S5_L001_R2_001_fastqc.html)|
|G56|[Filtered dataset](qc/G56_R1_fastqc.html)|[Filtered dataset](qc/G56_R2_fastqc.html)|
|G56|[Non-redundant dataset](qc/G56_R1_nr_fastqc.html)|[Non-redundant dataset](qc/G56_R2_nr_fastqc.html)|
