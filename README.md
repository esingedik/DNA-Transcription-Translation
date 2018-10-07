# DNA Transcription & Translation
A Perl program that the DNA sequence is transcribed into mRNA and translation to the appropriate amino acid sequence.
The program read the DNA sequence from a data file and write the amino acid sequence into another data file.

The DNA can be subdivided into genes that is called information bytes. Each gene encodes a unique protein that is in the cell. 

Cells use the two-step process of transcription and translation to read each gene and produce the string of amino acids that makes up a protein.

Transcription is the process of copying out the DNA sequence of a gene in the similar alphabet of RNA. Like DNA; mRNA has four nucleotide bases, but in mRNA, Thymine (T) is replaced with Uracil (U).

Translation refers to the process of creating proteins from an mRNA template. The sequence of nucleotides on the RNA is translated into the amino acid sequence of proteins and this reaction is carried out by ribosomes.

First of all, DNA is transcribed to RNA. For this, instead of each DNA part, its counterpart is written (i.e., G for C, C for G, T for A and A for T). Since there is no Thymine in the RNA, the Thymin in DNA is replaced with Uracil, and then Transcripted RNA occurs. Transcripted RNA is splitted into triplets, each called codon. This section was Transcription.

![Alt text](https://user-images.githubusercontent.com/35924267/46584141-4fdb9400-ca68-11e8-90aa-52dbaa9fe065.png?raw=true "Transcription")

In the Translation Section, each codon is looked for in the genetic code table. So UAC becomes Tyrosine, which we can write as Tyr, or
just Y, etc. This process is continued until all the codons are finished.

![Alt text](https://user-images.githubusercontent.com/35924267/46584142-50742a80-ca68-11e8-8bd1-5139bd16a52d.png?raw=true "Translation")

![Alt text](https://user-images.githubusercontent.com/35924267/46584312-81edf580-ca6a-11e8-9ef7-a3c92ddcfc72.jpg?raw=true "Genetic Code Table")
