## When installed on Quest, the following was run:

# First create a new conda environment for installing then activate it

conda create --name 3DChromatin_ReplicateQC anaconda=5.2.0=py27_3 pip

source activate 3DChromatin_ReplicateQC

install_scripts/install_3DChromatin_ReplicateQC.sh --pathtopython /home/kpe8127/programs/anaconda2/envs/3DChromatin_ReplicateQC/bin/python --rlib /home/kpe8127/R/x86_64-pc-linux-gnu-library/3.4 --pathtobedtools /home/kpe8127/programs/biobuilds-2017.05/bin/bedtools --modules R/3.4.4

