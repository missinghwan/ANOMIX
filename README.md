# MSAD
A PyTorch implementation of "[Graph Anomaly Detection via Multi-Level Contrastive Learning with Hard Negative Samples]" (HGCL)


# Dependencies
  Dependencies for all experiments of MSAD are as follows:
  
   • Python == 3.7.8
   
   • PyTorch == 1.6.0
   
   • NetworkX == 2.6.3
   
   • Scikit-learn == 0.23.2
   
   • NumPy == 1.18.5
   
   • SciPy == 1.7.3

   • DGL == 0.4.1

# Usage
All of datasets used in this paper are put in ./dataset folder and graph information (e.g., adjacency, attribute, and label) is included in each dataset file (.mat). Due to the large file size, some of metapaths are included in that folder as .csv files.

    python run.py --dataset cora


# Contact
missinghwan@gmail.com
