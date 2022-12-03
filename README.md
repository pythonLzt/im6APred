Dependency:

python==3.8

numpy==1.21.5

tensorflow==2.3.0

pandas==1.1.0

Usage:

python test.py -model humanbrain -test_fasta test.fasta -out_dir out


Notes: 

1. The script test.py is used to predict m6A sites from a given file with fasta format containing RNA sequences. 

2. model: enter the name of the specie and tissue, for example human liver、mouse heart、rat kidney

3. test_fasta: an input file containing query RNA sequences with fasta format.

4. out: the name of output directory.
