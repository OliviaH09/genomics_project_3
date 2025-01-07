Step 1: wget -O GCA_019753335.1.fasta.gz "https://www.ebi.ac.uk/ena/browser/api/fasta/GCA_019753335.1?download=true&gz #C.ruddii assembled genome, naming the file as indicated. https files dont give clear instruction as to what the file name should be. FTP files typically indicate what the file name should be
Step 2: prokka GCA_019753335.1.fasta # Use prokka to annotate the genome of choice
