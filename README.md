# BioPopWork
 
 
## Workshop : fast bioinformatic workflow for population genomics
 
This project is the workflow for a workshop in Bioinformatics for population genomics analyses with resequencing data and the reference genome.
The aim of the workflow is to show how to obtain formats and analyses for fast-and-first exploration of resequencing data of populations. During a paper
discussion on each session of the workshop, we will reflect on alternative methods to the ones used during the on-hand sessions.

In the future this workflow would have the flow to run in one-click script with many plots for biological interpretation as ouputs.

#check for read quality with Fred scores
module load fastqc/0.11.5
mkdir QUALITY-reads
fastqc 01.180603.B03.S1.1.fastq.gz -o ./QUALITY-reads
#for a loop
###Aligments
 
