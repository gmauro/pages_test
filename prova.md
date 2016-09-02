GALAXY WORKSHOP on GENOME ANNOTATION
------------------------------------
 
Genome annotation is the process of attaching biological information to sequences.
It consists of three main steps:

 - identifying portions of the genome that do not code for proteins
 - identifying elements on the genome, a process called gene prediction, and
 - attaching biological information to these elements.


# 1. Introduction into File Formats

**FASTA**

DNA and protein sequences are written in FASTA format where you have in the first line a ">" followed by the description. In the second line the sequence starts.


![FASTA file](images/fasta_format.png)



**GFF3**

The general feature format (gene-finding format, generic feature format, GFF) is a file format used for describing genes and other features of DNA, RNA and protein sequences.

<img src="images/gff3_format.png" width="70%">



**GENBANK**

The genbank sequence format is a rich format for storing sequences and associated annotations.

![genbank file](images/gb_full.png)


# 2. Structural Annotation

For the genome annotation we us a piece of the *Aspergillus fumigatus* [genome sequence](Aspergillus_sequence.fasta) as input file. 



## 2.1 Sequence Features

First we want to get some general information about our sequence. Count the number of bases in your sequence (**compute sequence length**), and check for sequence composition and GC content (**geecee**). Plot the sequence composition as bar chart. 

<img src="images/barchart_sequencecomposition.png" width="30%">


