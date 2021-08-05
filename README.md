# CUBCO

### CUBCO: Prediction of protein complexes based on min-cut network partitioning into biclique spanned subgraphs 

High-throughput approaches have generated large-scale protein-protein inter-action (PPI) networks that are used in prediction of protein complexes. How-ever, these approaches do not detect some interactions that can affect the pre-diction of protein complexes. Here, we introduce CUBCO—an algorithm that predicts protein complexes as biclique spanned subgraphs and that relies on link prediction approaches to score and incorporate missing interactions. Our comprehensive analyses with PPIs from Escherichia coli, Saccharomyces cerevisiae, and Homo sapiens show that CUBCO performs on par with the best-performing approaches, that model protein complexes as biclique spanned subgraphs, and outperforms the remaining contenders. We demon-strate that the usage of link prediction approaches in CUBCO improves the prediction of protein complexes. Finally, CUBCO recovers ~40% and ~11% of known protein complexes from the Pan-Plant and Metazoan networks, re-spectively, and predicts 11 and 15 protein complexes in PPI networks of Ara-bidopsis thaliana and H. sapiens, that are validated by domain-domain inter-action and GO semantic similarity. Therefore, CUBCO represents an efficient, parameter-free approach for accurate prediction of protein complexes from PPI networks. 

The implementation of CUBCO with an example is available in a separate Jupyter notebook.
