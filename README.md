# SCLAP
Scuchloroplast Localization Prediction using AdaBoost Predictor

Cite:
Vijayakumar Saravanan and P.T.V. Lakshmi. OMICS: A Journal of Integrative Biology. February 2013, 17(2): 106-115. doi:10.1089/omi.2012.0070.

#Installation 

Linux OS 
(a) Download DualPred from github. 
(b) Extract the files to the desired location. 
(c) Provide executable permission to SCLAP and Batch_SCLAP file (if it doesn't have executable rights). 
(d) make sure java 1.6 or higher is installed in your system. 
(e) make sure PERL 5.0 or higher version is installed in your system. 
(f) Make sure standalone BLAST (version 2.2.30+) is installed and executables added to the path.

#Instructions
Execute the program by typing the following command after installation 

(a) For Single protein run 
./SCLAP <input sequence file> <output file name>
ex: ./SCLAP Seq_raw Out1

Note: The input sequence file should contain single sequence in RAW format. FASTA format is not accepted!. For Batch sequence prediction use Batch_SCLAP.


(b) For Batch Protein run
./Batch_SCALP <input sequence file>
ex: ./Batch_SCLAP Mult_input

Note: The input sequence file may contain multiple protein sequences in FASTA format. For batch submission RAW format is not accepted. The output for the batch submission will be stored as file named with first 11 characters of the corespondig FASTA header.




