# Code review

In this assignment, we will provide the background  information, links, the papers associated with the project,along with the related code that will be used for this project.

## Papers

The sequence data to be analyzed will be taken from the research paper [Chrzastek et.al, 2023](https://bioone.org/journals/avian-diseases/volume-66/issue-4/aviandiseases-D-22-99999/A-Universal-Single-Primer-Amplification-Protocol-to-Perform-Whole-Genome/10.1637/aviandiseases-D-22-99999.full). Following that, sequences will be processed and analyzed using the protocols described in [Chrzastek et.al, 2023](https://bioone.org/journals/avian-diseases/volume-66/issue-4/aviandiseases-D-22-99999/A-Universal-Single-Primer-Amplification-Protocol-to-Perform-Whole-Genome/10.1637/aviandiseases-D-22-99999.full) and [Egana-labrin et. al, 2019](https://www.nature.com/articles/s41598-019-45494-4#Sec7). Shortly,the reads will be aligned to chicken reference genome (galGal5) using BWA-MEM. From the non-host reads contigs will be made and aligned to identified viral reference  contigs to find the number of viral reads. The obtained viral gene sequences will be compared with  the vaccine strain S1133, and sequence homology will be calculated. 

## Associated code
The preprocessing step described in the study includes adapter trimming and quality filtering using [Trim Galore(v0.5.0)](https://github.com/FelixKrueger/TrimGalore/blob/master/trim_galore). The analysis code for this project is available in the [script](script.py)
