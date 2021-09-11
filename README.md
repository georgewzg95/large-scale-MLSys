# Large-Scale-MLSys
These are MLSys reading list for private use

## Paper List of Large-scale Model Parallelism
1. Automatic Graph Partitioning for Very Large-scale Deep Learning [IPDPS'21](https://arxiv.org/abs/2103.16063)
2. GPipe: Efficient Training of Giant Neural Networks using Pipeline Parallelism [NIPS'19](https://proceedings.neurips.cc/paper/2019/file/093f65e080a295f8076b1c5722a46aa2-Paper.pdf], [code](https://github.com/tensorflow/lingvo/blob/master/lingvo/core/gpipe.py)
3. GShard: Scaling Giant Models with Conditional Computation and Automatic Sharding [arXiv](https://arxiv.org/abs/2006.16668), [Code](https://github.com/tensorflow/lingvo/tree/master/lingvo/tasks/lm)
4. Supporting Very Large Models using Automatic Dataflow Graph Partitioning [EuroSys'19](http://web.eecs.umich.edu/~mosharaf/Readings/Tofu.pdf)
5. Beyond Data and Model Parallelism for Deep Neural Networks [MLSys'19](https://proceedings.mlsys.org/paper/2019/hash/c74d97b01eae257e44aa9d5bade97baf-Abstract.html), [Code](https://github.com/flexflow/FlexFlow)
6. Exploring hidden dimensions in parallelizing convolutional neural networks [ICML'18](https://arxiv.org/abs/1802.04924)
7. Mesh-tensorflow: Deep learning for supercomputers [NIPS'18](https://papers.nips.cc/paper/2018/file/3a37abdeefe1dab1b30f7c5c7e581b93-Paper.pdf), [Code](https://github.com/tensorflow/mesh)
8. Megatron-LM: Training Multi-Billion Parameter Language Models Using Model Parallelism [arXiv](https://arxiv.org/abs/1909.08053), [Code](https://github.com/NVIDIA/Megatron-LM)
9. PipeDream: Pipeline Parallelism for DNN Training [SysMl'18](https://aaronharlap.github.io//papers/pipedream-full.pdf)
10. PipeDream: Generalized Pipeline Parallelism for DNN Training [SOSP'19](https://www.microsoft.com/en-us/research/publication/pipedream-generalized-pipeline-parallelism-for-dnn-training/), [code](https://github.com/msr-fiddle/pipedream/)
11. AMPNet: Asynchronous Model-Parallel Training for Dynamic Neural Networks [arXiv](https://arxiv.org/pdf/1705.09786.pdf)
12. XPipe: EfEfficient and robust parallel DNN training through model parallelism on multi-GPU platformficient pipeline model parallelism for multiGPU DNN training [arXiv](https://arxiv.org/abs/1911.04610)
13. Efficient and robust parallel DNN training through model parallelism on multi-GPU platform (arXiv)[https://arxiv.org/abs/1809.02839]
14. Memory-Efficient Pipeline-Parallel DNN Training (ICML'21)[https://arxiv.org/abs/2006.09503], [code](https://github.com/msr-fiddle/pipedream/)
15. Hetpipe: Enabling large {DNN} training on (whimpy) heterogeneous {GPU} clusters through integration of pipelined model parallelism and data parallelism [USENIX'20](https://www.usenix.org/conference/atc20/presentation/park)
16. torchgpipe: On-the-fly pipeline parallelism for training giant models [arXiv](https://arxiv.org/abs/2004.09910), [[code](https://github.com/kakaobrain/torchgpipe)]
17. Efficient Large-Scale Language Model Training on GPU Clusters Using Megatron-LM [SC'21](https://arxiv.org/abs/2104.04473), [code](https://github.com/NVIDIA/Megatron-LM)
18. HetSeq: Distributed GPU Training on Heterogeneous Infrastructure [IAAI'21](https://arxiv.org/abs/2009.14783), [code](https://github.com/yifding/hetseq)

## Exsiting Tools to train models in scale
1. DeepSpeed by Microsoft [Project Page](https://www.microsoft.com/en-us/research/blog/deepspeed-accelerating-large-scale-model-inference-and-training-via-system-optimizations-and-compression/), [code](https://github.com/microsoft/DeepSpeed)
2. Megatron-LM by Nvidia [code](https://github.com/NVIDIA/Megatron-LM)
3. Determined AI
4. GPipe and GShard by google [GPipe](https://github.com/tensorflow/lingvo/blob/master/lingvo/core/gpipe.py), [GShard](https://github.com/tensorflow/lingvo/tree/master/lingvo/tasks/lm)

## Relevant Dissertation
1. Improving ml applications in shared computing environments [Link](https://aaronharlap.github.io//papers/aharlap_dissertation.pdf)








