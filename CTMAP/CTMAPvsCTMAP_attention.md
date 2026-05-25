# Performance comparison between CTMAP and CTMAP with the attention module on the MERFISH dataset

We attempted to incorporate an additional cross-cell self-attention layer within the CTMAP encoder (denoted as CTMAP_attention), aiming to enable interaction and weighting among cells within the same batch based on expression similarity, thereby facilitating a performance comparison with CTMAP. However, experimental results on the MERFISH dataset showed that this modification did not improve performance but instead led to a notable decrease in annotation accuracy.


![Benchmark annotation performance](https://i.imgur.com/lmp28qm.png)


