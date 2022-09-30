# RBP Peak Finder 
Project for 03713 Bioinformatics Data Integration and Practicum

## Contributors
- **Arnav Gupta**  
- **Ketaki Ghatole** 
- **Tianyi Fei**   
- **Yuewei Fei**  

## Description
RNA binding proteins play an important role in RNA regulation, metabolism and interactions. Predicting the interactions between viral RNAs and host proteins can facilitate a better understanding of viral infection mechanisms. Thus, we have built the pipeline ‘eRNApredict’ to identify the RNA binding sites for proteins of interest using eCLIP data from ENCORE. 

## Workflow
The PART I aims to identify uniquely mapped reads to generate a list of potential binding sites also known as peaks using the fastq files from ENCORE as input.

The PART II is designed to train a classifier for distinguishing between peaks from background sequences. Given the viral RNA sequence and a host protein we can predict the corresponding RNA-Protein interactions using this model based on convolutional neural networks.


## Packages
1. UMI-Tools
2. Cutadapt
3. fastq-tools
4. STAR
5. samtools
6. Barcode collapse
7. bamCoverage
8. PureClip
9. Pytorch

## Results
RBP Peak Finder can be used to predict if a host protein will bind to the viral RNA and the peaks will highlight the regions to which they are more likely to bind. 


## Final Report and Outcomes
<object data="https://github.com/ArnavGuptaa/eclip_psc_scripts/blob/main/BDIP%20Final%20Report.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://github.com/ArnavGuptaa/eclip_psc_scripts/blob/main/BDIP%20Final%20Report.pdf">
        <p>Please download the PDF to view it: <a href="https://github.com/ArnavGuptaa/eclip_psc_scripts/blob/main/BDIP%20Final%20Report.pdf">Download PDF</a>.</p>
    </embed>
</object>
