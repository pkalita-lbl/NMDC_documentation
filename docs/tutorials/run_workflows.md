# Running the Workflows

## NMDC EDGE QuickStart

<div align="center">
    <video src="https://nmdc-edge.org/docs/videos/nmdc-edge.mp4" width="80%" height="80%" controls />
</div>
<br><br>

> ### NMDC EDGE QuickStart Tutorial Practice
>
>Task 1:  Create an NMDC EDGE account with either your email address or your ORCiD account.
>
>Task 2: Download the small interleaved [data file listed here.](
https://nmdc-edge.org/publicdata/test_data/SRR7877884-int-0.1.fastq.gz) Upload the file to NMDC EDGE.
>
>Task 3: Click the user icon (in the top right corner with your initials) and under “Files”, click on “Manage Uploads”. Verify that the file you uploaded is there. (Note: Later you can delete uploads that are no longer needed.)
>
>Task 4 (optional):  Click the user icon and under “Account”, click on “Profile”. Edit your account to receive email notification of project status by clicking “ON”.

## Metagenomics

### ReadsQC

<div align="center">
    <video src="https://nmdc-edge.org/docs/videos/ReadsQC.mp4" width="80%" height="80%" controls />
</div>
<br><br>

>NMDC EDGE Metagenome ReadsQC Tutorial Practice 
>
>Task: Log into NMDC EDGE and run the Metagenome ReadsQC workflow using the dataset uploaded in the QuickStart tutorial.
>
>&nbsp;&nbsp;&nbsp;&nbsp;Question 1:  How many reads were in the input file? How many bases were in the input file?
>
>&nbsp;&nbsp;&nbsp;&nbsp;Question 2:  How many reads were in the output file? How many bases were in the output file?
>
>&nbsp;&nbsp;&nbsp;&nbsp;Question 3:  What file in the output would be used in the next workflow?


### Read-based Taxonomy Classification

<div align="center">
    <video src="https://nmdc-edge.org/docs/videos/ReadBasedAnalysis.mp4" width="80%" height="80%" controls />
</div>
<br><br>

>NMDC EDGE Metagenome Read-based Taxonomy Classification Tutorial Practice 
>
>Task: Log into NMDC EDGE and run the Metagenome Read-based Taxonomy Classification workflow with all three taxonomy classification tools. (Note: All three tools are selected by default. While a user can opt to turn off one or two tools, it is recommended to run all three.) Use the clean data output file from the project run in the ReadsQC Tutorial (the file ending in .anqdpht.fq.gz). In this case, the file will be treated as single-end reads.
>
>&nbsp;&nbsp;&nbsp;&nbsp;Question 1:  How many of the Top 10 species are called by more than one tool?
>
>&nbsp;&nbsp;&nbsp;&nbsp;Question 2:  List the **genera** that are called by all three tools in the Top 10.
>
>&nbsp;&nbsp;&nbsp;&nbsp;Question 3:  Open a full window of the Krona plot at **species level** from the taxonomy classification tool Centrifuge. What percentage of the sample is estimated to be _Pseudomonas aeruginosa_? 

### Assembly

<div align="center">
    <video src="https://nmdc-edge.org/docs/videos/MetagenomeAssembly.mp4" width="80%" height="80%" controls />
</div>
<br><br>

>NMDC EDGE Metagenome Assembly Tutorial Practice 
>
>Task: Log into NMDC EDGE and run the Metagenome Assembly workflow. Use the clean data output file from the project run in the ReadsQC Tutorial (the file ending in .anqdpht.fq.gz). In this case, the file is interleaved paired data and only one file is required for input.
>
>&nbsp;&nbsp;&nbsp;&nbsp;Question 1:  How many contigs were generated from the assembly?
>
>&nbsp;&nbsp;&nbsp;&nbsp;Question 2:  How many scaffolds were generated from the assembly?
>
>&nbsp;&nbsp;&nbsp;&nbsp;Question 3:  From the covstats.txt file, what percentage of the reads map back to the assembled contigs?

### Annotation

<div align="center">
    <video src="https://nmdc-edge.org/docs/videos/MetagenomeAnnotation.mp4" width="80%" height="80%" controls />
</div>
<br><br>

>NMDC EDGE Metagenome Annotation Tutorial Practice 
>
>Task: Log into NMDC EDGE and run the Metagenome Annotation workflow. Use the assebled contigs which are output from the project run in the Assembly Tutorial (assembled_contigs.fna). 
>
>&nbsp;&nbsp;&nbsp;&nbsp;Question 1:  How many contigs had genes called (sequences_with_genes)?
>
>&nbsp;&nbsp;&nbsp;&nbsp;Question 2:  How many coding sequences (genes) were called by Prodigal? How many were called by GeneMark?
>
>&nbsp;&nbsp;&nbsp;&nbsp;Question 3:  What is the coding density of this metagenome?

### MAGs Generation

<div align="center">
    <video src="https://nmdc-edge.org/docs/videos/MetagenomeMAGs.mp4" width="80%" height="80%" controls />
</div>
<br><br>

>NMDC EDGE MAGs Generation Tutorial Practice 
>
>Task: Log into NMDC EDGE and run the Metagenome MAGs workflow. Use the assebled contigs and the read mapping file which are output from the project run in the Assembly Tutorial (assembled_contigs.fna and pairedMapped_sorted.bam) and the combined functional annotation file fromt he Annotation Tutorial (the file ending in fuctional_annotation.gff)
>
>&nbsp;&nbsp;&nbsp;&nbsp;Question 1:  What percentage of the contigs were binned?
>
>&nbsp;&nbsp;&nbsp;&nbsp;Question 2:  How many bins were determined to be high quality (HQ)? How many bins were determined to be medium quality (MQ)?
>
>&nbsp;&nbsp;&nbsp;&nbsp;Question 3: What is the organism identified from genome in the bin which is most complete and has the least contamination (the highest quality bin)? (Note: Scroll to the far right of the summary table in the results to get the species assignment.)

### Running multiple workflows or the full metagenomic pipeline with a single input

<div align="center">
    <video src="https://nmdc-edge.org/docs/videos/pipeline.mp4" width="80%" height="80%" controls />
</div>
<br><br>

>NMDC EDGE Full Metagenome Piepline Tutorial Practice 
>
>Task: Log into NMDC EDGE and run the full Metagenome pipeline (multiple workflows- all workflows are selected by default). Use the same dataset uploaded in the QuickStart tutorial. Check your results for the full pipeline against your results from the previous tutorials. The results should be identical/nearly identical to the results from the previous tutorials for each individual workflow with the added benefit of submitting all the workflows with a single input of raw sequencing data.
>
>If you want to just test the full pipeline and not the individual workflows, [download this data set.](
https://nmdc-edge.org/publicdata/test_data/SRR7877884-int-0.1.fastq.gz) Upload the file to NMDC EDGE and run the full pipeline.


## Metatranscriptomics

<div align="center">
    <video src="https://nmdc-edge.org/docs/videos/MetaT.mp4" width="80%" height="80%" controls />
</div>
<br><br>





>NMDC EDGE Metatranscriptomics Tutorial Practics
>
>Task: 



  