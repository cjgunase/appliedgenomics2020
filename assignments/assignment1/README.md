## Assignment 1: Chromosome Structures
Assignment Date: Wednesday, Jan 29, 2020 <br>
Due Date: Wednesday, Feb. 5, 2020 @ 11:59pm <br>

### Assignment Overview

In this assignment you will profile the overall structure of the genomes of several important species and then study the yeast genome in more detail.
As a reminder, any questions about the assignment should be posted to [Piazza](https://piazza.com/class/k5vn2kkfo8g6n7)

### Question 1: Chromosome structures

Download the chomosome size files for the following genomes (Note these have been preprocessed to only include main chromosomes):

1. [Arabidopsis thaliana (TAIR10)](http://schatz-lab.org/appliedgenomics2020/assignments/assignment1/TAIR10.chrom.sizes) - An important plant model species [[info]](https://en.wikipedia.org/wiki/Arabidopsis_thaliana)
2. [Tomato (Solanum lycopersicum v4.00)](http://schatz-lab.org/appliedgenomics2020/assignments/assignment1/tomato.chrom.sizes) - One of the most important food crops [[info]](https://en.wikipedia.org/wiki/Tomato)
3. [E. coli (Escherichia coli K12)](http://schatz-lab.org/appliedgenomics2020/assignments/assignment1/ecoli.chrom.sizes) - One of the most commonly studied bacteria [[info]](https://en.wikipedia.org/wiki/Escherichia_coli)
4. [Fruit Fly (Drosophila melanogaster, dm6)](http://schatz-lab.org/appliedgenomics2020/assignments/assignment1/dm6.chrom.sizes) - One of the most important model species for genetics [[info]](https://en.wikipedia.org/wiki/Drosophila_melanogaster)
5. [Human (hg38)](http://schatz-lab.org/appliedgenomics2020/assignments/assignment1/hg38.chrom.sizes) - us :) [[info]](https://en.wikipedia.org/wiki/Homo_sapiens)
6. [Wheat (Triticum aestivum, IWGSC)](http://schatz-lab.org/appliedgenomics2020/assignments/assignment1/wheat.chrom.sizes) - The food crop which takes up the largest land area [[info]](https://en.wikipedia.org/wiki/Wheat)
7. [Worm (Caenorhabditis elegans, ce10)](http://schatz-lab.org/appliedgenomics2020/assignments/assignment1/ce10.chrom.sizes) - One of the most important animal model species [[info]](https://en.wikipedia.org/wiki/Caenorhabditis_elegans)
8. [Yeast (Saccharomyces cerevisiae, sacCer3)](http://schatz-lab.org/appliedgenomics2020/assignments/assignment1/yeast.chrom.sizes) - an important eukaryotic model species, also good for bread and beer [[info]](https://en.wikipedia.org/wiki/Saccharomyces_cerevisiae)

Using these files, make a table with the following information per species:

- Question 1.1. Total genome size
- Question 1.2. Number of chromosomes
- Question 1.3. Largest chromosome size and name
- Question 1.4. Smallest chromosome size and name
- Question 1.5. Mean chromosome length


### Question 2: Sequence content

Download the yeast genome from here: [http://schatz-lab.org/appliedgenomics2020/assignments/assignment1/yeast.fa.gz](http://schatz-lab.org/appliedgenomics2020/assignments/assignment1/yeast.fa.gz)

- Question 2.1. How many As, Cs, Gs, Ts are found in the entire genome
- Question 2.2. Make a scatterplot of the %GC of 100bp non-overlapping windows across the genome: x-axis = genome location, y-axis = (#G + #C) / 100. For this analysis the chromsomes can be concatenated together to form a long string of the chromosomes in numerical order: chr1, chr2, ... chrN. Make sure to draw a bar to indicate the ends of chromosomes
- Question 2.3. Make a histogram of the number of genomic bins of a given %GC: x-axis = %GC, y-axis = # genomic bins with this %GC. You should use the same 100bp bins as Q2.2
- Question 2.4. Recall that Illumina sequencing performs poorly when the %GC is <= 30% or >= 65%. Based on the analysis from Q2.2, what fraction of the genome do you expect to sequence poorly?


### Hints

- Many of the questions can be addressed with standard command line [tools](http://lh3lh3.users.sourceforge.net/biounix.shtml) such as grep, wc, awk, sort, fold, etc
- You may wish to try out [datamash](https://www.gnu.org/software/datamash/)
- You may find [samtools](http://www.htslib.org/) and especially `samtools faidx` helpful for indexing the fasta files
- Plotting can be done in any language; R or Python are recommended; Excel is okay but ugly :-P
- The final PDF can be made in any system: Markdown, Word, Google Docs, LaTeX, HTML
- Be sure to clearly mark each question and subquestion
- Mac and Linux can use the builtin terminal
- If you are using Windows, you may want to install [Ubuntu for Windows](https://tutorials.ubuntu.com/tutorial/tutorial-ubuntu-on-windows#0)


### Packaging

The solutions to the above questions should be submitted as a single PDF document that includes your name, email address, and 
all relevant figures (as needed). Make sure to clearly label each of the subproblems and give the exact commands and/or code snippets you used for 
solving the question. You do not need to show code for plotting. Submit your solutions by uploading the PDF to [GradeScope](https://www.gradescope.com/courses/85808). The Entry Code is: MR652Z 

If you submit after this time, you will start to use up your late days. Remember, you are only allowed 96 hours (4 days) for the entire semester!



