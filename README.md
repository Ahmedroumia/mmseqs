# mmseqs
1- to cluster
mmseqs easy-cluster OMPdb_2020_04.fasta outDB tmp --min-seq-id 0.3 -c 0.8 --cov-mode 1

## to run it on the server
run this line first:
wget https://mmseqs.com/latest/mmseqs-linux-avx2.tar.gz; tar xvfz mmseqs-linux-avx2.tar.gz; export PATH=$(pwd)/mmseqs/bin/:$PATH
