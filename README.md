# CS598-GBL - Gen Mod for BioMed &amp; Life Sci

### Course Console

**Lectures**: 0220 Siebel Center for Computer Science, MW: 9:30 AM – 10:45 AM

| **Member (NetID)** | **Role** | **Office Hours** |
| --- | --- | --- |
| Ge Liu (geliu) | Instructor | Mon 3:00-4:00 SC3212 |
| Yanru Qu (yanruqu2) | TA | Mon 11-12 SC 3rd floor near elevator |

**Canvas**: https://canvas.illinois.edu/courses/56424

- For homework/report submission
- For open discussion

**Github (Course website)**: https://github.com/gelab-uiuc/CS598-GBL

- Covering most of the course information, including schedule and reading lists

**Note**: Please use **Canvas Discussion** to submit your course-related questions. Please **DO NOT** email the TA or Prof. Liu directly, unless the matter is private or only concerns yourself.

### Course Description

In this course, we will discuss recent advances in generative AI for biomedicine, with a special focus on geometric-aware deep learning, multimodal diffusion/flow matching on diverse data manifolds, and language models. We will also discuss foundational models for biomedicine and life sciences applications such as protein design, drug discovery, and understanding the functions and dynamics of complex biomolecular systems.

**Learning Objectives:** This course will introduce generative model basics, their application in biomedicines, and other impactful research works. At the end of this course, you will be able to:

- Have a good overview and basic knowledge of state-of-the-art generative models in biomedicines & life science
- Familiar with the research process: proposal, presentation, paper writing, review & rebuttal, hands-on experiments
- Have critical thinking and assessment of research papers

**Structure**: This will be a graduate-level course in seminar format.

- 6 instructor lectures: we will first review the biology & generative model basics. See schedule
- 1 project brain-storm session
- 15 paper-reading lectures: we will select 15 research sub-topics and reading lists for students to read, present, and discuss, covering the following topics:
    - Language models for biomedicine
    - Generative models for chemical molecules
    - Generative models for protein folding and design
    - Complex-based design with generative models: Structure-based drug design, peptide, antibody, enzyme, and molecular docking
    - RLHF/conditional generation/Guidance
- mid-term and final presentations

### Grading Policy

**Groups**: All activities of this course, except your attendance, will be performed in groups of 3 students, in a total of 15 groups. **By Feb 3**, most groups should submit their memberships (**exactly 3**) and topic preference (see 5 general topics in **Structure**). For students who do not find a group, we will assign groups according to their topic preference.

| **Component** | **Weight** | **Breakdown** |
| --- | --- | --- |
| Pre-class Reading | 10% | 10 pt 15 lectures |
| In-class Discussion | 30% | - 10% Presentation - 10% Rebuttal - 10% Review |
| Hands-on Experiments | 20% | - 10% Scripts & Generation Results - 10% Report |
| Final Project | 40% | - 5% Proposal - 15% Final Presentation - 20% Final Report |

**Pre-class Reading**

- Group Assignment: Each paper-reading lecture will have several required readings and optional related readings.  Each group should read at least one of the papers and submit at least 1 insightful question or idea related to the paper you read here https://docs.google.com/spreadsheets/d/1Q-wPi2Ezbv0QJe8hN2tBNC15WmkPaquhuJqkT4p5bWk/edit?usp=sharing before the lecture.

**In-class Discussion**

- In each paper-reading lecture, 2 groups will be signed up as the main leaders of the discussion, with each group playing one of the 2 roles: **presenters** or **reviewers**. These 2 groups are required to submit assignments (see below). Other groups are encouraged to participate in class discussions. Throughout the semester, each group needs to sign up for each one of the roles once, totaling participation in 2 different subtopics.
- Group Assignment for designated presenters and reviewers:
    - For presenter: submit slides (at least 20 pages) for all required readings **before the lecture,** and present the papers **during the class (45 min presentation);** submit a rebuttal **within 6 days after the lecture**
    - For reviewers: submit academic reviews about required readings by **EOD of the lecture**

**Hands-on Experiments**

We’ll release 1-3 benchmark challenges during the semester. Each group should choose 1 challenge and use its codebase to generate results and evaluation metrics, and finish a short report like the experiment section in a paper. The report should cover experiment settings and results analysis. Each group should submit the experiment reports 2 weeks **before the final presentation (Apr 23).**

**Final Project**

Each group should complete a final project in one of the following types:

1. Comprehensive literature survey on one advanced subtopic in generative AI for biomedicine (doesn't need to be one of the subtopics of the lecture, but should be related to the topics of the class).
2. Benchmarking & dataset paper (opportunity to submit to Neurips Benchmark track)
3. Open-ended research (opportunity to submit to Neurips main track)

Each group should submit a proposal **by Mar 5 (1 week before mid-term)**, and a final report **by May 14 (1 week after the final presentation)**

**Late Day Policy**

Students may request one 3-day extension in the semester for full credit. Otherwise, late submission within 3 days results in at most 80% of credits. Submission later than 3 days results in 0% of credits.

### Tentative Schedule

Note: This is an evolving list. For each topic, the presenter should cover 2-3 required papers in their presentation.

| **Date** | **Topic** | **Presenter** | **Reviewer** | **Note** |
| --- | --- | --- | --- | --- |
|  | **Course Introduction** |  |  |  |
| Jan 22 | Intro + Biology101 | Prof. Liu |  |  |
| Jan 27 | Diffusion |  |  |  |
| Jan 29 | Flow Models |  |  |  |
| Feb 3 | VAE  |  |  | Group Membership & Topic Preference Due |
| Feb 5 | Geometric DL & Equivariance |  |  |  |
| Feb 10 | Seq Model & Discrete Generation |  |  |  |
| Feb 12 | No Lecture / Brain storm for project proposal and prepare presentation |  |  |  |
|  | **Paper-reading lectures begin** |  |  |  |
|  | **Language Model in Biomedicine** |  |  |  |
| Feb 17 | lecture 1: protein |  |  |  |
| Feb 19 | lecture 2: protein & beyond |  |  |  |
| Feb 24 | lecture 3: discrete generation |  |  |  |
|  | **Molecule Generation** |  |  |  |
| Feb 26 | lecture 4: 2d |  |  |  |
| Mar 3 | lecture 5: 3d |  |  |  |
| Mar 5 | lecture 6: 2d & 3d |  |  | Proposal Due |
|  | **Mid-term Presentation & Hands on challenge introduction** |  |  |  |
| Mar 10 |  |  |  |  |
| Mar 12 |  |  |  |  |
|  | **Spring Break** |  |  |  |
| Mar 17 | No Lecture |  |  |  |
| Mar 19 | No Lecture |  |  |  |
|  | **Paper-reading Lectures** |  |  |  |
|  | **Protein Generation** |  |  |  |
| Mar 24 | lecture 7: folding and inverse folding |  |  |  |
| Mar 26 | lecture 8: folding and inverse folding |  |  |  |
| Mar 31 | lecture 9: folding and inverse folding |  |  |  |
| Apr 2 | lecture 10: co-design |  |  |  |
|  | **Complex-based Generation** |  |  |  |
| Apr 7 | lecture 11: peptide design |  |  |  |
| Apr 9 | lecture 12: structure-based drug design |  |  |  |
| Apr 14 | lecture 13: docking |  |  |  |
| Apr 16 | lecture 14: antibody design |  |  |  |
|  | **RLHF/DPO/Guidance** |  |  |  |
| Apr 21 | lecture 15 |  |  |  |
| Apr 23 |  |  |  | Remote, DLL for challenge submission |
| Apr 28 | No Lecture / Work on Final Presentation |  |  |  |
| Apr 30 | No Lecture / Work on Final Presentation |  |  |  |
|  | **Final Presentation** |  |  |  |
| May 5 |  |  |  |  |
| May 7 |  |  |  |  |
| May 14 |  |  |  | Final Report due |

### Reading List

paper lists:

https://github.com/AspirinCode/papers-for-molecular-design-using-DL 

https://github.com/amorehead/awesome-molecular-generation 

https://github.com/lmqfly/Geometry-Deep-Learning-for-Drug-Discovery?tab=readme-ov-file#molecular-design

https://github.com/Peldom/papers_for_protein_design_using_DL?tab=readme-ov-file#2-model-based-design

#### Diffusion

Lilian’s blog: https://lilianweng.github.io/posts/2021-07-11-diffusion-models/

Yang Song’s blog: https://yang-song.net/blog/2021/score/

Sohl-Dickstein, Jascha, et al. "Deep unsupervised learning using nonequilibrium thermodynamics." International conference on machine learning. PMLR, 2015.

Song, Yang, and Stefano Ermon. "Generative modeling by estimating gradients of the data distribution." Advances in neural information processing systems 32 (2019).

Ho, Jonathan, Ajay Jain, and Pieter Abbeel. "Denoising diffusion probabilistic models." Advances in neural information processing systems 33 (2020): 6840-6851.

Ho, Jonathan, and Tim Salimans. "Classifier-free diffusion guidance." arXiv preprint arXiv:2207.12598 (2022).

Dhariwal, Prafulla, and Alexander Nichol. "Diffusion models beat gans on image synthesis." Advances in neural information processing systems 34 (2021): 8780-8794.

#### Flow Models

tutorial: https://neurips.cc/virtual/2024/tutorial/99531

Rezende, Danilo, and Shakir Mohamed. "Variational inference with normalizing flows." International conference on machine learning. PMLR, 2015.

Chen, Ricky TQ, et al. "Neural ordinary differential equations." Advances in neural information processing systems 31 (2018).

Lipman, Yaron, et al. "Flow Matching for Generative Modeling." The Eleventh International Conference on Learning Representations.

Liu, Xingchao, and Chengyue Gong. "Flow Straight and Fast: Learning to Generate and Transfer Data with Rectified Flow." The Eleventh International Conference on Learning Representations.

Chen, Ricky TQ, and Yaron Lipman. "Riemannian flow matching on general geometries." arXiv preprint arXiv:2302.03660 (2023).

Gat, Itai, et al. "Discrete Flow Matching." The Thirty-eighth Annual Conference on Neural Information Processing Systems.

Stark, Hannes, et al. "Dirichlet Flow Matching with Applications to DNA Sequence Design." Forty-first International Conference on Machine Learning.

Campbell, Andrew, et al. "Generative Flows on Discrete State-Spaces: Enabling Multimodal Flows with Applications to Protein Co-Design." Forty-first International Conference on Machine Learning.

#### Latent Diffusion / VAE

Lilian’s blog https://lilianweng.github.io/posts/2018-08-12-vae/

tutorial: https://nips.cc/virtual/2023/tutorial/73957

Rombach, Robin, et al. "High-resolution image synthesis with latent diffusion models." Proceedings of the IEEE/CVF conference on computer vision and pattern recognition. 2022.

Kingma, Diederik P. "Auto-encoding variational bayes." arXiv preprint arXiv:1312.6114 (2013).

Van Den Oord, Aaron, and Oriol Vinyals. "Neural discrete representation learning." Advances in neural information processing systems 30 (2017).

Razavi, Ali, Aaron Van den Oord, and Oriol Vinyals. "Generating diverse high-fidelity images with vq-vae-2." Advances in neural information processing systems 32 (2019).

#### Language model in biomedicine

**lecture1**

Lin, Zeming, et al. "Evolutionary-scale prediction of atomic-level protein structure with a language model." *Science* 379.6637 (2023): 1123-1130.

Hayes, Thomas, et al. "Simulating 500 million years of evolution with a language model." *Science* (2025): eads0018.

ESM3-C: https://www.evolutionaryscale.ai/blog/esm-cambrian

**lecture2**

Nguyen, Eric, et al. "Sequence modeling and design from molecular to genome scale with Evo." *Science* 386.6723 (2024): eado9336.

Madani, Ali, et al. "Large language models generate functional protein sequences across diverse families." *Nature Biotechnology* 41.8 (2023): 1099-1106.

Notin, Pascal, et al. "Proteinnpt: Improving protein property prediction and design with non-parametric transformers." *Advances in Neural Information Processing Systems* 36 (2023): 33529-33563.

optional:

Shuai, Richard W., Jeffrey A. Ruffolo, and Jeffrey J. Gray. "IgLM: Infilling language modeling for antibody sequence design." *Cell Systems* 14.11 (2023): 979-989.

Notin, Pascal, et al. "TranceptEVE: Combining Family-specific and Family-agnostic Models of Protein Sequences for Improved Fitness Prediction." *NeurIPS 2022 Workshop on Learning Meaningful Representations of Life*.

**lecture3**

Cheng, Chaoran, et al. "Categorical Flow Matching on Statistical Manifolds." *NeuRIPS* (2024).

Wang, Xinyou, et al. "Dplm-2: A multimodal diffusion protein language model." *arXiv preprint arXiv:2410.13782* (2024).

Alamdari, Sarah, et al. "Protein generation with evolutionary diffusion: sequence is all you need." *NeurIPS 2023 Generative AI and Biology (GenBio) Workshop*.

optional:

Avdeyev, Pavel, et al. "Dirichlet diffusion score model for biological sequence generation." *International Conference on Machine Learning*. PMLR, 2023.

Stark, Hannes, et al. "Dirichlet Flow Matching with Applications to DNA Sequence Design." *ICLR 2024 Workshop on Generative and Experimental Perspectives for Biomolecular Design*.

Bhattacharya, Debjyoti, et al. "Large language models as molecular design engines." *Journal of Chemical Information and Modeling* 64.18 (2024): 7086-7096.

#### Molecule Generation

**lecture4**

Eijkelboom, Floor, et al. "Variational Flow Matching for Graph Generation." *arXiv preprint arXiv:2406.04843* (2024).

Vignac, Clement, et al. "DiGress: Discrete Denoising diffusion for graph generation." *The Eleventh International Conference on Learning Representations*.

Kong, Xiangzhe, et al. "Molecule generation by principal subgraph mining and assembling." *Advances in Neural Information Processing Systems* 35 (2022): 2550-2563.

- optional

Jin, Wengong, Regina Barzilay, and Tommi Jaakkola. "Junction tree variational autoencoder for molecular graph generation." *International conference on machine learning*. PMLR, 2018.

Jin, Wengong, Regina Barzilay, and Tommi Jaakkola. "Hierarchical generation of molecular graphs using structural motifs." *International conference on machine learning*. PMLR, 2020.

**lecture5**

Song, Yuxuan, et al. "Equivariant flow matching with hybrid probability transport for 3d molecule generation." *Advances in Neural Information Processing Systems* 36 (2024).

Xu, Minkai, et al. "Geometric latent diffusion models for 3d molecule generation." *International Conference on Machine Learning*. PMLR, 2023.

Hoogeboom, Emiel, et al. "Equivariant diffusion for molecule generation in 3d." *International conference on machine learning*. PMLR, 2022.

- optional

Song, Yuxuan, et al. "Unified generative modeling of 3d molecules via bayesian flow networks." *ICLR* (2024).

Xu, Minkai, et al. "GeoDiff: A Geometric Diffusion Model for Molecular Conformation Generation." *International Conference on Learning Representations*.

**lecture6**

Peng, Xingang, et al. "MolDiff: addressing the atom-bond inconsistency problem in 3D molecule diffusion generation." *Proceedings of the 40th International Conference on Machine Learning*. 2023.

Vignac, Clément, et al. "MiDi: Mixed Graph and 3D Denoising Diffusion for Molecule Generation." *Joint European Conference on Machine Learning and Knowledge Discovery in Databases*. 2023.

Dunn, Ian, and David Ryan Koes. "Mixed Continuous and Categorical Flow Matching for 3D De Novo Molecule Generation." *ArXiv* (2024).

- optional

Huang, Han, et al. "Learning joint 2-d and 3-d graph diffusion models for complete molecule generation." *IEEE Transactions on Neural Networks and Learning Systems* (2024).

Jing, Bowen, et al. "Torsional diffusion for molecular conformer generation." *Advances in Neural Information Processing Systems* 35 (2022): 24240-24253.

Ganea, Octavian, et al. "Geomol: Torsional geometric generation of molecular 3d conformer ensembles." *Advances in Neural Information Processing Systems* 34 (2021): 13757-13769.

#### Protein Generation

**lecture7**

Abramson, Josh, et al. "Accurate structure prediction of biomolecular interactions with AlphaFold 3." *Nature* (2024): 1-3.

Krishna, Rohith, et al. "Generalized biomolecular modeling and design with RoseTTAFold All-Atom." *Science* 384.6693 (2024): eadl2528.

Dauparas, Justas, et al. "Robust deep learning–based protein sequence design using ProteinMPNN." *Science* 378.6615 (2022): 49-56.

- optional

Jumper, John, et al. "Highly accurate protein structure prediction with AlphaFold." *nature* 596.7873 (2021): 583-589.

Baek, Minkyung, et al. "Accurate prediction of protein structures and interactions using a three-track neural network." *Science* 373.6557 (2021): 871-876.

Baek, Minkyung, et al. "Efficient and accurate prediction of protein structure using RoseTTAFold2." *BioRxiv* (2023): 2023-05.

Zheng, Zaixiang, et al. "Structure-informed language models are protein designers." *International conference on machine learning*. PMLR, 2023.

**lecture8**

Yim, Jason, et al. "Fast protein backbone generation with SE (3) flow matching." *arXiv preprint arXiv:2310.05297* (2023).

Watson, Joseph L., et al. "De novo design of protein structure and function with RFdiffusion." *Nature* 620.7976 (2023): 1089-1100.

Yim, Jason, et al. "Improved motif-scaffolding with SE (3) flow matching." *ICLR 2024 Workshop on Generative and Experimental Perspectives for Biomolecular Design*.

optional: 

Yim, Jason, et al. "SE (3) diffusion model with application to protein backbone generation." *International Conference on Machine Learning*. PMLR, 2023.

**lecture9**

Huguet, Guillaume, et al. "Sequence-Augmented SE (3)-Flow Matching For Conditional Protein Backbone Generation." *arXiv preprint arXiv:2405.20313* (2024).

Lin, Yeqing, et al. "Out of Many, One: Designing and Scaffolding Proteins at the Scale of the Structural Universe with Genie 2." *arXiv preprint arXiv:2405.15489* (2024).

Ingraham, John B., et al. "Illuminating protein space with a programmable generative model." *Nature* 623.7989 (2023): 1070-1078.

**lecture10**

Shi, Chence, et al. "Protein Sequence and Structure Co-Design with Equivariant Translation." *The Eleventh International Conference on Learning Representations*.

Campbell, Andrew, et al. "Generative Flows on Discrete State-Spaces: Enabling Multimodal Flows with Applications to Protein Co-Design." *Forty-first International Conference on Machine Learning*.

optional:

Lisanza, Sidney Lyayuga, et al. "Joint generation of protein sequence and structure with RoseTTAFold sequence space diffusion." bioRxiv (2023): 2023-05.

Zhang, Zaixi, et al. "Full-atom protein pocket design via iterative refinement." Advances in Neural Information Processing Systems 36 (2023): 16816-16836.

Anand, Namrata, and Tudor Achim. "Protein structure and sequence generation with equivariant denoising diffusion probabilistic models." arXiv preprint arXiv:2205.15019 (2022).

#### Complex-based functional Design Generation

**lecture11**

Lin, Haitao, et al. "PPFLOW: Target-Aware Peptide Design with Torsional Flow Matching." Forty-first International Conference on Machine Learning.

Li, Jiahan, et al. "Full-Atom Peptide Design based on Multi-modal Flow Matching." Forty-first International Conference on Machine Learning.

Li, Jiahan, et al. "Hotspot-Driven Peptide Design via Multi-Fragment Autoregressive Extension." ICLR (2025).

**lecture12**

ZHANG, ZAIXI, Marinka Zitnik, and Qi Liu. "Generalized Protein Pocket Generation with Prior-Informed Flow Matching." The Thirty-eighth Annual Conference on Neural Information Processing Systems.

Guan, Jiaqi, et al. "3D Equivariant Diffusion for Target-Aware Molecule Generation and Affinity Prediction." The Eleventh International Conference on Learning Representations.

Peng, Xingang, et al. "Pocket2mol: Efficient molecular sampling based on 3d protein pockets." International Conference on Machine Learning. PMLR, 2022.

optional:

Luo, Shitong, et al. "A 3D generative model for structure-based drug design." Advances in Neural Information Processing Systems 34 (2021): 6229-6239.

Qu, Yanru, et al. "MolCRAFT: Structure-Based Drug Design in Continuous Parameter Space." Forty-first International Conference on Machine Learning.

Jiang, Yuanyuan, et al. "Pocketflow is a data-and-knowledge-driven structure-based molecular generative model." Nature Machine Intelligence 6.3 (2024): 326-337.

ZHANG, ZAIXI, Mengdi Wang, and Qi Liu. "FlexSBDD: Structure-Based Drug Design with Flexible Protein Modeling." The Thirty-eighth Annual Conference on Neural Information Processing Systems.

Peng, Xingang, et al. "Decipher Fundamental Atomic Interactions to Unify Generative Molecular Docking and Design." bioRxiv (2024): 2024-10.

**lecture13**

Stark, Hannes, et al. "Harmonic Self-Conditioned Flow Matching for joint Multi-Ligand Docking and Binding Site Design." Forty-first International Conference on Machine Learning.

Corso, Gabriele, et al. "DiffDock: Diffusion Steps, Twists, and Turns for Molecular Docking." The Eleventh International Conference on Learning Representations.

Stärk, Hannes, et al. "Equibind: Geometric deep learning for drug binding structure prediction." International conference on machine learning. PMLR, 2022.

optional:

Lu, Wei, et al. "Tankbind: Trigonometry-aware neural networks for drug-protein binding structure prediction." Advances in neural information processing systems 35 (2022): 7236-7249.

**lecture14**

Kong, Xiangzhe, Wenbing Huang, and Yang Liu. "End-to-End Full-Atom Antibody Design." International Conference on Machine Learning. PMLR, 2023.

Kong, Xiangzhe, Wenbing Huang, and Yang Liu. "Conditional Antibody Design as 3D Equivariant Graph Translation." The Eleventh International Conference on Learning Representations.

Jin, Wengong, et al. "Iterative Refinement Graph Neural Network for Antibody Sequence-Structure Co-design." International Conference on Learning Representations.

optional:

Luo, Shitong, et al. "Antigen-specific antibody design and optimization with diffusion-based generative models for protein structures." Advances in Neural Information Processing Systems 35 (2022): 9754-9767.

Wang, Zichen, et al. "Retrieval Augmented Diffusion Model for Structure-informed Antibody Design and Optimization." arXiv preprint arXiv:2410.15040 (2024).

#### RLHF / DPO / Guidance

**lecture15**

Park, Ryan, et al. "Improving Inverse Folding for Peptide Design with Diversity-regularized Direct Preference Optimization." arXiv preprint arXiv:2410.19471 (2024).

Wang, Chenyu, et al. "Fine-Tuning Discrete Diffusion Models via Reward Optimization with Applications to DNA and Protein Design." NeurIPS 2024 Workshop on AI for New Drug Modalities.

Zhou, Xiangxin, et al. "Antigen-Specific Antibody Design via Direct Energy-based Preference Optimization." arXiv preprint arXiv:2403.16576 (2024).

optional:

DPO blog: https://pakhapoomsarapat.medium.com/forget-rlhf-because-dpo-is-what-you-actually-need-f10ce82c9b95

Ren, Allen Z., et al. "Diffusion Policy Policy Optimization." CoRL 2024 Workshop on Mastering Robot Manipulation in a World of Abundant Data.

Dong, Hanze, et al. "RAFT: Reward rAnked FineTuning for Generative Foundation Model Alignment." Transactions on Machine Learning Research.

Rafailov, Rafael, et al. "Direct preference optimization: Your language model is secretly a reward model." Advances in Neural Information Processing Systems 36 (2024).

### Guidelines

**Presentation & Slides**

todo

**Pre-class Questions**

todo

**Review & Rebuttal**

todo

**Experiment Report**

todo

**Final Report**

todo

### **Acknowledgements**

In course structure design, this course is heavily inspired by other seminar-like courses, particularly [UIUC CS598-GenAI System](https://github.com/fanlai0990/CS598). Acknowledgments to [Prof. Fan Lai](https://fanlai.me/) for  generous sharing of his great course.
