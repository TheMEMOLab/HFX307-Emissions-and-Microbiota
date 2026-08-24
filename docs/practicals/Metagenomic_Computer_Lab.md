# HFX307/407 Metagenomic Computer Lab

## Exercise A – Genome annotation in bacteria and archaea – genomes and MAGs

[Prokka](https://github.com/tseemann/prokka) is a rapid genome annotation pipeline designed for bacterial and archaeal genomes. It identifies genomic features such as protein-coding sequences (CDSs), rRNAs and tRNAs, and assigns putative functions to predicted genes by comparing them against reference databases. Prokka can also be applied to metagenome-assembled genomes (MAGs), producing standard output files containing gene coordinates, nucleotide sequences and predicted protein sequences.

In this exercise, Prokka will be used to annotate the MAG and generate the predicted protein sequences that will be used for downstream functional analyses.


1. The first we need a fasta file, let's download the file from [here](https://ns9864k.web.sigma2.no/TheMEMOLab/courses/hfx307_407/Genome/)
    - Do click on the ```Control_HighE.metabat.733.fa``` file an save link as. Save it to your PC.

2. We can use Galaxy, a web-based platform for data intensive life science research that provides users with a unified, easy-to-use graphical interface to a host of different analysis tools to launch Prokka and 
annotate our genome. Let's login to [Galaxy](https://usegalaxy.no/) using our Feide credentials. 

3. Upload the fasta file using the ```upload``` buttom as it is shown here ![upload](../images/Upload.png)

4. Once uploaded you shoudl see it in your history: ![history](../images/uploadfile.png)


5. To launch Prokka we can look for it in the Tools search ![Prokka in Galaxy](../images/prokka.png). 

6. Select the ```Control_HighE.metabat.733.fa``` file adn 

