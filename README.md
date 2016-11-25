### Welcome to SQANTI: Structural and Quality Annotation of Novel Transcript Isoforms ###


```
#!python


```

**What is SQANTI for?**

SQANTI is a pipeline created for the in-depth characterization of isoforms obtained by full-length transcript sequencing, which are commonly returned in a fasta file format without any extra information about gene/transcript annotation or attribute description.

Although thought to be used for characterization of isoforms generated by long-read sequencing, SQANTI can be used for any set of transcript isoforms in fasta file format.

As long-read sequencing have a high error rate of errors, SQANTI:
* 1. First performs a reference-based correction of sequences.
* 2. Secondly, generates genes models and computes a ORF prediction for each isoform, obtaining information about the coding potential of each defined isoform. 
* 3. Finally it carries out a deep characterization of isoforms at both transcript and junction level and generates a report with several plots describing in detail the mayor attributes that catalog your set of sequenced-isoforms.



**What input files do I need?**




 reference-based corrected transcriptome, a transcript-level annotation file containing several expression, structural and quality features, and a set of different summary descriptive plots for the entire dataset 

the predicted ORF sequences for PacBio sequences and two annotation files. The first one at transcript-level annotation and containing …orf predicted informantion, gene characterization, etc, and the second one at junction-level.

* Version
* [Learn Markdown](https://bitbucket.org/tutorials/markdowndemo)

### How do I get set up? ###

* Summary of set up
* Configuration
* Dependencies
* Database configuration
* How to run tests
* Deployment instructions

### Contribution guidelines ###

* Writing tests
* Code review
* Other guidelines

### Who do I talk to? ###

* Repo owner or admin
* Other community or team contact