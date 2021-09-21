# Exercises

## 1. Command line

GFF file located in /scratch/bio373_2020/data/SNPcalling/reference

GFF files contains information on features of a sequence: genes, introns, etc. Take a look and familiarize yourself with the format.

<http://www.ensembl.org/info/website/upload/gff.html>

1. How many lines are in Ahal.gff? Characters?
2. How many of each type of feature (column 3) are there?
3. How many CDS’s are there within scaffold_1? Beware! There’s also scaffold_10, scaffold_11, etc

### Extra practice

Zip the file and modify your commands to answer the same questions!

```bash
$ cp /scratch/bio373_2021/data/SNPcalling/reference/Ahal.gff YOUR_DIRECTORY/
$ cd YOUR_DIRECTORY
$ gzip Ahal.gff
```

Answers can be found on the server here: `/scratch/bio373_2021/data/SNPcalling/answers/CommandLineAnswers.txt`

* * *

## 2. Set up environment

1. How many sequences are there in the reference sequence file (MedtrChr2.fa)? 

2. How many reads does each fastq file have (\*\_R1.fastq.gz)? Does each sample have the same number of R1 and R2 reads? (Caution: Q scores can be + or @)

3. How many bases are in the reference sequence? How many missing bases (N)? Don’t forget ‘\\n’ is considered a character!

## Answers

On the server: `/scratch/bio373_2020/data/SNPcalling/answers/fastAQ.txt`

* * *
