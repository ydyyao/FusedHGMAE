# FusedHGMAE
**Abstract**
Heterogeneous Graph Masked AutoEncoders (HGMAEs) have emerged as a powerful tool for capturing complex
structural and semantic information. However, most existing HGMAEs follow a metapath-based masking and
reconstruction paradigm that entangles low-frequency information and high-frequency information. It leads to
a frequency bias toward low-frequency components and fails to preserve important high-frequency information.
To this end, we propose FusedHGMAE, a Frequency-spatial dual-domain guided Heterogeneous Graph Masked
AutoEncoder. Specifically, we present a ‘path-then-frequency’ decomposition method to decouple each metapath-
induced view into distinct low-frequency and high-frequency channels in the frequency domain. Subsequently, we
design a node-level adaptive fusion mechanism to aggregate the features of multi-view frequency features. In the spatial
domain, we learn the structural constraint to preserve essential connectivity patterns by masking metapath-based edges
and performing topology-aware reconstruction. Finally, we reconstruct frequency-aware node attributes and structural
information to optimize the proposed FusedHGMAE. Experimental results on four public datasets demonstrate the
effectiveness of FusedHGMAE on the tasks of node classification and node clustering. The source codes of this work
are available at https://github.com/ydyyao/FusedHGMAE.

