# Awesome-DL-training-system 
(Main target: OSDI, SOSP, NSDI, SIGCOMM, ATC, ASPLOS Backup: EyroSys, SoCC)

#### Cluster Scheduling
[SoCC'17][Princeton] [SLAQ_Quality-Driven Scheduling for Distributed Machine Learning](https://dl.acm.org/doi/abs/10.1145/3127479.3127490)  
[EuroSys'18][HKU] [Optimus: an efficient dynamic resource scheduler for deep learning clusters](https://dl.acm.org/doi/abs/10.1145/3190508.3190517)  
[OSDI'18][MSRA] [Gandiva: Introspective Cluster Scheduling for Deep Learning](https://www.usenix.org/conference/osdi18/presentation/xiao)  
[NSDI'19][UMich] [Tiresias: A GPU Cluster Manager for Distributed Deep Learning](https://www.usenix.org/conference/nsdi19/presentation/gu)  
[NSDI'20][UWM] [Themis: Fair and Efficient GPU Cluster Scheduling](https://www.usenix.org/conference/nsdi20/presentation/mahajan)  
[OSDI'21][CMU] [Pollux: Co-adaptive Cluster Scheduling for Goodput-Optimized Deep Learning](https://www.usenix.org/conference/osdi21/presentation/qiao)  

[OSDI'20][Stanford] [Heterogeneity-Aware Cluster Scheduling Policies for Deep Learning Workloads](https://www.usenix.org/conference/osdi20/presentation/narayanan-deepak)  
[OSDI'20][Alibaba] [AntMan: Dynamic Scaling on GPU Clusters for Deep Learning](https://www.usenix.org/conference/osdi20/presentation/xiao)  
[OSDI'22][MSR] [Looking Beyond GPUs for DNN Scheduling on Multi-Tenant Clusters](https://www.usenix.org/conference/osdi22/presentation/mohan)  
[OSDI'23][IEU] [Effectively Scheduling Computational Graphs of Deep Neural Networks toward Their Domain-Specific Accelerators](https://www.usenix.org/conference/osdi23/presentation/zhao)  
[OSDI'23][NTU] [Hydro: Surrogate-Based Hyperparameter Tuning Service in Datacenters](https://www.usenix.org/conference/osdi23/presentation/hu)  
[NSDI'21][KAIST] [Elastic Resource Sharing for Distributed Deep Learning](https://www.usenix.org/conference/nsdi21/presentation/hwang)  
[NSDI22][HKUST] [MLaaS in the Wild: Workload Analysis and Scheduling in Large-Scale Heterogeneous GPU Clusters](https://www.usenix.org/conference/nsdi22/presentation/weng)  
[NSDI'23][UWM] [Shockwave: Fair and Efficient Cluster Scheduling for Dynamic Adaptation in Machine Learning](https://www.usenix.org/conference/nsdi23/presentation/zheng)  
[SIGCOMM'22][PKU] [Multi-resource interleaving for deep learning training](https://dl.acm.org/doi/10.1145/3544216.3544224)  


[ASPLOS'23][PKU] [ElasticFlow: An Elastic Serverless Training Platform for Distributed Deep Learning](https://dl.acm.org/doi/abs/10.1145/3575693.3575721)  
[EuroSys'23][CityU] [Lyra: Elastic Scheduling for Deep Learning Clusters](https://dl.acm.org/doi/abs/10.1145/3552326.3587445)  
[SOSP'23][CMU] [Sia: Heterogeneity-aware, goodput-optimized ML-cluster scheduling](https://dl.acm.org/doi/abs/10.1145/3600006.3613175)  



#### Framework
[OSDI'14][CMU] [Scaling Distributed Machine Learning with the Parameter Server](https://www.usenix.org/conference/osdi14/technical-sessions/presentation/li_mu)  
[OSDI'18][UCB] [Ray: A Distributed Framework for Emerging AI Applications](https://www.usenix.org/conference/osdi18/presentation/moritz)  
[SOSP'19][HKU] [A generic communication scheduler for distributed DNN training acceleration](https://dl.acm.org/doi/10.1145/3341301.3359642)  
[OSDI'20][ByteDance] [A Unified Architecture for Accelerating Distributed DNN Training in Heterogeneous GPU/CPU Clusters](https://www.usenix.org/conference/osdi20/presentation/jiang)  
[OSDI'20][MSRA] [Retiarii: A Deep Learning Exploratory-Training Framework](https://www.usenix.org/conference/osdi20/presentation/zhang-quanlu)  
[OSDI'20][IC] [KungFu: Making Training in Distributed Machine Learning Adaptive](https://www.usenix.org/system/files/osdi20-mai.pdf)  
[OSDI'22][ZJU] [Walle: An End-to-End, General-Purpose, and Large-Scale Production System for Device-Cloud Collaborative Machine Learning](https://www.usenix.org/conference/osdi22/presentation/lv)  
[OSDI'22][Standford] [Unity: Accelerating DNN Training Through Joint Optimization of Algebraic Transformations and Parallelization](https://www.usenix.org/conference/osdi22/presentation/unger)  
[OSDI'22][UCB] [Alpa: Automating Inter- and Intra-Operator Parallelism for Distributed Deep Learning](https://www.usenix.org/conference/osdi22/presentation/zheng-lianmin)  
[OSDI'22][UCB] [AlpaServe: Statistical Multiplexing with Model Parallelism for Deep Learning Serving](https://www.usenix.org/conference/osdi23/presentation/li-zhouhan)  
[SOSP'19][Standford] [TASO: optimizing deep learning computation with automatic generation of graph substitutions](https://dl.acm.org/doi/10.1145/3341301.3359630)  
[SOSP'21][USTC] [Gradient Compression Supercharged High-Performance Data Parallel DNN Training](https://dl.acm.org/doi/10.1145/3477132.3483553)  
[NSDI'19][SNU] [JANUS: Fast and Flexible Deep Learning via Symbolic Graph Execution of Imperative Programs](https://www.usenix.org/conference/nsdi19/presentation/jeong)  
[NSDI'19][MSRI] [BLAS-on-flash: An Efficient Alternative for Large Scale ML Training and Inference?](https://www.usenix.org/conference/nsdi19/presentation/subramanya)  
[NSDI'21][THU] [ATP: In-network Aggregation for Multi-tenant Learning](https://www.usenix.org/conference/nsdi21/presentation/lao)  
[NSDI'21][KAIST] [Scaling Distributed Machine Learning with In-Network Aggregation](https://www.usenix.org/conference/nsdi21/presentation/sapio)  
[NSDI'22][NVIDIA] [Accelerating Collective Communication in Data Parallel Training across Deep Learning Frameworks](https://www.usenix.org/conference/nsdi22/presentation/romero)  
[NSDI'23][MIT] [TopoOpt: Co-optimizing Network Topology and Parallelization Strategy for Distributed Training Jobs](https://www.usenix.org/conference/nsdi23/presentation/wang-weiyang)  
[NSDI'23][UMich] [ModelKeeper: Accelerating DNN Training via Automated Training Warmup](https://www.usenix.org/conference/nsdi23/presentation/lai-fan)  
[NSDI'23][UWM] [Better Together: Jointly Optimizing ML Collective Scheduling and Execution Planning using SYNDICATE](https://www.usenix.org/conference/nsdi23/presentation/mahajan)  
[NSDI'23][KAIST] [ARK: GPU-driven Code Execution for Distributed Deep Learning](https://www.usenix.org/conference/nsdi23/presentation/hwang)  
[SIGCOMM'23][THU] [Janus: A Unified Distributed Training Framework for Sparse Mixture-of-Experts Models](https://dl.acm.org/doi/10.1145/3603269.3604869)  
[SIGCOMM'23][Google] [Lightwave Fabrics: At-Scale Optical Circuit Switching for Datacenter and Machine Learning Systems](https://dl.acm.org/doi/10.1145/3603269.3604836)  


#### Fault Tolerance
[SOSP'23][RiceU] [GEMINI: Fast Failure Recovery in Distributed Training with In-Memory Checkpoints](https://dl.acm.org/doi/10.1145/3600006.3613145)  
[SOSP'23][UMich] [Oobleck: Resilient Distributed Training of Large Models Using Pipeline Templates](https://dl.acm.org/doi/10.1145/3600006.3613152)  



#### Cache
[SOSP'23][SJTU] [UGACHE: A Unified GPU Cache for Embedding-based Deep Learning](https://dl.acm.org/doi/10.1145/3600006.3613169)  


#### Pipeline
[SOSP'19][MSR] [PipeDream: generalized pipeline parallelism for DNN training](https://dl.acm.org/doi/10.1145/3341301.3359646)  
[OSDI'20][JHU] [PipeSwitch: Fast Pipelined Context Switching for Deep Learning Applications](https://www.usenix.org/conference/osdi20/presentation/bai)  
[NSDI'23][UCLA] [Bamboo: Making Preemptible Instances Resilient for Affordable Training of Large DNNs](https://www.usenix.org/conference/nsdi23/presentation/thorpe)  



#### Deep Recommendation Model
[OSDI'23][UMich] [AdaEmbed: Adaptive Embedding for Large-Scale Recommendation Models](https://www.usenix.org/conference/osdi23/presentation/lai)  
[SOSP'23][UWM] [Bagpipe: Accelerating Deep Recommendation Model Training](https://dl.acm.org/doi/10.1145/3600006.3613142  


#### Resource Sharing
[OSDI'20][MSRA] [HiveD: Sharing a GPU Cluster for Deep Learning with Guarantees](https://www.usenix.org/conference/osdi20/presentation/zhao-hanyu) 
[NSDI'23][PKU] [Transparent GPU Sharing in Container Clouds for Deep Learning Workloads](https://www.usenix.org/conference/nsdi23/presentation/wu)  


#### Tensor Programs
[OSDI'20][UCB] [Ansor: Generating High-Performance Tensor Programs for Deep Learning](https://www.usenix.org/conference/osdi20/presentation/zheng)  
[OSDI'21][THU] [PET: Optimizing Tensor Programs with Partially Equivalent Transformations and Automated Corrections](https://www.usenix.org/conference/osdi21/presentation/wang)  
[OSDI'22][MSRA] [SparTA: Deep-Learning Model Sparsity via Tensor-with-Sparsity-Attribute](https://www.usenix.org/conference/osdi22/presentation/zheng-ningxin)  
[OSDI'23][THU] [EINNET: Optimizing Tensor Programs with Derivation-Based Transformations](https://www.usenix.org/conference/osdi23/presentation/zheng)  
[SOSP'23][MSRA] [PIT: Optimization of Dynamic Sparse Deep Learning Models via Permutation Invariant Transformation](https://dl.acm.org/doi/10.1145/3600006.3613139)  



#### Federated learning
[OSDI'21][UMich] [Oort: Efficient Federated Learning via Guided Participant Selection](https://www.usenix.org/conference/osdi21/presentation/lai)  
[NSDI'23][HKUST] [FLASH: Towards a High-performance Hardware Acceleration Architecture for Cross-silo Federated Learning](https://www.usenix.org/conference/nsdi23/presentation/zhang-junxue)  


#### Security & Privacy
[OSDI'21][Columbia] [Privacy Budget Scheduling](https://www.usenix.org/conference/osdi21/presentation/luo)
[SOSP'19][Columbia] [Privacy accounting and quality control in the sage differentially private ML platform](https://dl.acm.org/doi/10.1145/3341301.3359639)  


#### Compilation
[OSDI'18][UW] [TVM: An Automated End-to-End Optimizing Compiler for Deep Learning](https://www.usenix.org/conference/osdi18/presentation/chen)  
[OSDI'20][MSRA] [Rammer: Enabling Holistic Deep Learning Compiler Optimizations with rTasks](https://www.usenix.org/conference/osdi20/presentation/ma)  
[OSDI'20][MSRA] [A Tensor Compiler for Unified Machine Learning Prediction Serving](https://www.usenix.org/conference/osdi20/presentation/nakandala)  
[OSDI'22][MSRA] [ROLLER: Fast and Efficient Tensor Compilation for Deep Learning](https://www.usenix.org/conference/osdi22/presentation/zhu)  
[OSDI'23][MSRA] [Cocktailer: Analyzing and Optimizing Dynamic Control Flow in Deep Learning](https://www.usenix.org/conference/osdi23/presentation/zhang-chen)  
[OSDI'23][MSRA] [Welder: Scheduling Deep Learning Memory Access via Tile-graph](https://www.usenix.org/conference/osdi23/presentation/shi)  

#### GNN
[OSDI'21][UCLA] [Dorylus: Affordable, Scalable, and Accurate GNN Training with Distributed CPU Servers and Serverless Threads](https://www.usenix.org/conference/osdi21/presentation/thorpe)  
[OSDI'21][UCSB] [GNNAdvisor: An Adaptive and Efficient Runtime System for GNN Acceleration on GPUs](https://www.usenix.org/conference/osdi21/presentation/wang-yuke)  
[OSDI'21][UWM] [Marius: Learning Massive Graph Embeddings on a Single Machine](https://www.usenix.org/conference/osdi21/presentation/mohoney)  
[OSDI'21][MSR] [P3: Distributed Deep Graph Learning at Scale](https://www.usenix.org/conference/osdi21/presentation/gandhi)  
[OSDI'23][UCSB] [MGG: Accelerating Graph Neural Networks with Fine-Grained Intra-Kernel Communication-Computation Pipelining on Multi-GPU Platforms](https://www.usenix.org/conference/osdi23/presentation/wang-yuke)  
[NSDI'23][THU] [BGL: GPU-Efficient GNN Training by Optimizing Graph Data I/O and Preprocessing](https://www.usenix.org/conference/nsdi23/presentation/liu-tianfeng)  

#### Energy Consumption
[NSDI'23][UMich] [Zeus: Understanding and Optimizing GPU Energy Consumption of DNN Training](https://www.usenix.org/conference/nsdi23/presentation/you)  

