# WspGenie

Script for the identification of the Wsp operon in meta-omics datasets, inlcuding (meta)genomes, and (meta)transcriptomes.

### Dependencies
      python3
      HHMER

### easy-install
      git clone https://github.com/Arkadiy-Garber/WspGenie.git
      cd WspGenie
      chmod +x WspGenie.py

### sample command with input ORFs
      ./WspGenie.py -i fastaFile.fa -f orfs -o Wsp_outdir -h HMMs

### sample command with input contigs
      ./WspGenie.py -i fastaFile.fa -f contigs -o Wsp_outdir -h HMMs
