[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)]https://github.com/zhangbaijin/Diffusion-model-low-level) 

This repository contains a collection of resources and papers on ***Low-level Diffusion Model***.

## Contents
- [Resources](#resources)
  - [Introductory Posts](#introductory-posts)
  - [Introductory Papers](#introductory-papers)
  - [Introductory Videos](#introductory-videos)
  - [Introductory Lectures](#introductory-lectures)
- [Papers](#papers)
  - [Vision](#vision)
    - [Image Generation](#image-generation)
    - [Segmentation](#segmentation)
    - [Image-to-Image Translation](#image-to-image-translation)
    - [Super Resolution](#super-resolution)
    - [Image Editing](#image-editing)
    - [Text-to-Image](#text-to-image)

# Resources
## Introductory Posts

**Recent rise of diffusion-based models** \
*Maciej Domagała* \
[[Website](https://maciejdomagala.github.io/generative_models/2022/06/06/recent-rise-of-diffusion-based-models.html)] \
06 Jun 2022

**Introduction to Diffusion Models for Machine Learning** \
*Ryan O'Connor* \
[[Website](https://www.assemblyai.com/blog/diffusion-models-for-machine-learning-introduction/)] \
12 May 2022

**Improving Diffusion Models as an Alternative To GANs** \
*Arash Vahdat and Karsten Kreis* \
[[Website-Part 1](https://developer.nvidia.com/blog/improving-diffusion-models-as-an-alternative-to-gans-part-1/)] [[Website-Part 2](https://developer.nvidia.com/blog/improving-diffusion-models-as-an-alternative-to-gans-part-2/)] \
26 Apr 2022

**An introduction to Diffusion Probabilistic Models** \
*Ayan Das* \
[[Website](https://ayandas.me/blog-tut/2021/12/04/diffusion-prob-models.html)] \
04 Dec 2021

**Introduction to deep generative modeling: Diffusion-based Deep Generative Models** \
*Jakub Tomczak* \
[[Website](https://jmtomczak.github.io/blog/10/10_ddgms_lvm_p2.html)] \
30 Aug 2021

**What are Diffusion Models?** \
*Lilian Weng* \
[[Website](https://lilianweng.github.io/lil-log/2021/07/11/diffusion-models.html)] \
11 Jul 2021

**Diffusion Models as a kind of VAE** \
*Angus Turner* \
[[Website](https://angusturner.github.io/generative_models/2021/06/29/diffusion-probabilistic-models-I.html)] \
29 June 2021

**Generative Modeling by Estimating Gradients of the Data Distribution** \
*Yang Song* \
[[Website](https://yang-song.github.io/blog/2021/score/)] \
5 May 2021

## Introductory Papers

**A Connection Between Score Matching and Denoising Autoencoders** \
*Pascal Vincent* \
Neural Computation 2011. [[Paper](http://www.iro.umontreal.ca/~vincentp/Publications/smdae_techreport.pdf)] \
7 Jul 2011

**Bayesian Learning via Stochastic Gradient Langevin Dynamics** \
*Max Welling, Yee Whye Teh* \
ICML 2011. [[Paper](https://www.stats.ox.ac.uk/~teh/research/compstats/WelTeh2011a.pdf)] [[Github](https://github.com/JavierAntoran/Bayesian-Neural-Networks#stochastic-gradient-langevin-dynamics-sgld)] \
20 Apr 2022

## Introductory Videos

**What are Diffusion Models?** \
*Ari Seff* \
[[Video](https://www.youtube.com/watch?v=fbLgFrlTnGU&list=LL&index=2)] \
20 Apr 2022

**Diffusion models explained** \
*AI Coffee Break with Letitia* \
[[Video](https://www.youtube.com/watch?v=344w5h24-h8&ab_channel=AICoffeeBreakwithLetitia)] \
23 Mar 2022

## Introductory Lectures

**Diffusion Probabilistic Models** \
*Jascha Sohl-Dickstein, MIT 6.S192 - Lecture 22* \
[[Video](https://www.youtube.com/watch?v=XCUlnHP1TNM)] \
19 April 2022

# Papers

## Vision
### Image Generation

**Entropy-driven Sampling and Training Scheme for Conditional Diffusion Generation** \
*Shengming Li, Guangcong Zheng, Hui Wang, Taiping Yao, Yang Chen, Shoudong Ding, Xi Li* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.11474)] \
23 Jun 2022

**Diffusion models as plug-and-play priors** \
*Alexandros Graikos, Nikolay Malkin, Nebojsa Jojic, Dimitris Samaras* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.09012)] \
17 June 2022

**A Flexible Diffusion Model** \
*Weitao Du, Tao Yang, He Zhang, Yuanqi Du* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.10365)] \
17 Jun 2022

**Lossy Compression with Gaussian Diffusion** \
*Lucas Theis, Tim Salimans, Matthew D. Hoffman, Fabian Mentzer* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.08889)] \
17 Jun 2022

**Maximum Likelihood Training for Score-Based Diffusion ODEs by High-Order Denoising Score Matching** \
*Cheng Lu, Kaiwen Zheng, Fan Bao, Jianfei Chen, Chongxuan Li, Jun Zhu* \
ICML 2022. [[Paper](https://arxiv.org/abs/2206.08265)] \
16 Jun 2022

**Estimating the Optimal Covariance with Imperfect Mean in Diffusion Probabilistic Models** \
*Fan Bao, Chongxuan Li, Jiacheng Sun, Jun Zhu, Bo Zhang* \
ICML 2022. [[Paper](https://arxiv.org/abs/2206.07309)] [[Github](https://github.com/baofff/Extended-Analytic-DPM)] \
15 Jun 2022

**Discrete Contrastive Diffusion for Cross-Modal and Conditional Generation** \
*Ye Zhu, Yu Wu, Kyle Olszewski, Jian Ren, Sergey Tulyakov, Yan Yan* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.07771)] [[Github](https://github.com/L-YeZhu/CDCD)] \
15 Jun 2022

**gDDIM: Generalized denoising diffusion implicit models** \
*Qinsheng Zhang, Molei Tao, Yongxin Chen* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.05564)] [[Github](https://github.com/qsh-zh/gDDIM)] \
11 Jun 2022

**How Much is Enough? A Study on Diffusion Times in Score-based Generative Models** \
*Giulio Franzese, Simone Rossi, Lixuan Yang, Alessandro Finamore, Dario Rossi, Maurizio Filippone, Pietro Michiardi* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.05173)] \
10 Jun 2022

**Image Generation with Multimodal Priors using Denoising Diffusion Probabilistic Models** \
*Nithin Gopalakrishnan Nair, Wele Gedara Chaminda Bandara, Vishal M Patel* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.05039)] \
10 Jun 2022

**Accelerating Score-based Generative Models for High-Resolution Image Synthesis** \
*Hengyuan Ma, Li Zhang, Xiatian Zhu, Jingfeng Zhang, Jianfeng Feng* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.04029)] \
8 Jun 2022

**Diffusion-GAN: Training GANs with Diffusion** \
*Zhendong Wang, Huangjie Zheng, Pengcheng He, Weizhu Chen, Mingyuan Zhou* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.02262)] \
5 Jun 2022

**DPM-Solver: A Fast ODE Solver for Diffusion Probabilistic Model Sampling in Around 10 Steps** \
*Cheng Lu, Yuhao Zhou, Fan Bao, Jianfei Chen, Chongxuan Li, Jun Zhu* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.00927)] \
2 Jun 2022

**Elucidating the Design Space of Diffusion-Based Generative Models** \
*Tero Karras, Miika Aittala, Timo Aila, Samuli Laine* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.00364)] \
1 Jun 2022

**On Analyzing Generative and Denoising Capabilities of Diffusion-based Deep Generative Models** \
*Kamil Deja, Anna Kuzina, Tomasz Trzciński, Jakub M. Tomczak* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.00070)] \
31 May 2022

**Few-Shot Diffusion Models** \
*Giorgio Giannone, Didrik Nielsen, Ole Winther* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2205.15463)] \
30 May 2022

**A Continuous Time Framework for Discrete Denoising Models** \
*Andrew Campbell, Joe Benton, Valentin De Bortoli, Tom Rainforth, George Deligiannidis, Arnaud Doucet* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2205.14987)] \
30 May 2022

**Maximum Likelihood Training of Implicit Nonlinear Diffusion Models** \
*Dongjun Kim, Byeonghu Na, Se Jung Kwon, Dongsoo Lee, Wanmo Kang, Il-Chul Moon* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2205.13699)] \
27 May 2022

**Accelerating Diffusion Models via Early Stop of the Diffusion Process** \
*Zhaoyang Lyu, Xudong XU, Ceyuan Yang, Dahua Lin, Bo Dai* \
ICML 2022. [[Paper](https://arxiv.org/abs/2205.12524)] \
25 May 2022

**On Conditioning the Input Noise for Controlled Image Generation with Diffusion Models** \
*Vedant Singh<sup>1</sup>, Surgan Jandial<sup>1</sup>, Ayush Chopra, Siddharth Ramesh, Balaji Krishnamurthy, Vineeth N. Balasubramanian* \
arxiv 2022. [[Paper](https://arxiv.org/abs/2205.03859)] \
8 May 2022

**Subspace Diffusion Generative Models** \
*Bowen Jing, Gabriele Corso, Renato Berlinghieri, Tommi Jaakkola* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2205.01490)] [[Github](https://github.com/bjing2016/subspace-diffusion)] \
3 May 2022

**Fast Sampling of Diffusion Models with Exponential Integrator** \
*Qinsheng Zhang, Yongxin Chen* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2204.13902)] \
29 Apr 2022

**Retrieval-Augmented Diffusion Models** \
*Andreas Blattmann<sup>1</sup>, Robin Rombach<sup>1</sup>, Kaan Oktay, Björn Ommer* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2204.11824)] \
25 Apr 2022

**Perception Prioritized Training of Diffusion Models** \
*Jooyoung Choi, Jungbeom Lee, Chaehun Shin, Sungwon Kim, Hyunwoo Kim, Sungroh Yoon* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2204.00227)] [[Github](https://github.com/jychoi118/P2-weighting)] \
1 Apr 2022

**Generating High Fidelity Data from Low-density Regions using Diffusion Models** \
*Vikash Sehwag, Caner Hazirbas, Albert Gordo, Firat Ozgenel, Cristian Canton Ferrer* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2203.17260)] \
31 Mar 2022

**Diffusion Models for Counterfactual Explanations** \
*Guillaume Jeanneret, Loïc Simon, Frédéric Jurie* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2203.15636)] \
29 Mar 2022

**Denoising Likelihood Score Matching for Conditional Score-based Data Generation** \
*Chen-Hao Chao, Wei-Fang Sun, Bo-Wun Cheng, Yi-Chen Lo, Chia-Che Chang, Yu-Lun Liu, Yu-Lin Chang, Chia-Ping Chen, Chun-Yi Lee* \
ICLR 2022. [[Paper](https://arxiv.org/abs/2203.14206)] \
27 Mar 2022

**Dynamic Dual-Output Diffusion Models** \
*Yaniv Benny, Lior Wolf* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2203.04304)] \
8 Mar 2022

**Conditional Simulation Using Diffusion Schrödinger Bridges** \
*Yuyang Shi, Valentin De Bortoli, George Deligiannidis, Arnaud Doucet* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2202.13460)] \
27 Feb 2022

**Diffusion Causal Models for Counterfactual Estimation** \
*Pedro Sanchez, Sotirios A. Tsaftaris* \
PMLR 2022. [[Paper](https://arxiv.org/abs/2202.10166)] \
21 Feb 2022

**Pseudo Numerical Methods for Diffusion Models on Manifolds** \
*Luping Liu, Yi Ren, Zhijie Lin, Zhou Zhao* \
ICLR 2022. [[Paper](https://arxiv.org/abs/2202.09778)] [[Github](https://github.com/luping-liu/PNDM)] \
20 Feb 2022

**Truncated Diffusion Probabilistic Models** \
*Huangjie Zheng, Pengcheng He, Weizhu Chen, Mingyuan Zhou* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2202.09671)] \
19 Feb 2022

**Understanding DDPM Latent Codes Through Optimal Transport** \
*Valentin Khrulkov, Ivan Oseledets* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2202.07477)] \
14 Feb 2022

**Learning Fast Samplers for Diffusion Models by Differentiating Through Sample Quality** \
*Daniel Watson, William Chan, Jonathan Ho, Mohammad Norouzi* \
ICLR 2022. [[Paper](https://arxiv.org/abs/2202.05830)] \
11 Feb 2022

**Progressive Distillation for Fast Sampling of Diffusion Models** \
*Tim Salimans, Jonathan Ho* \
ICLR 2022. [[Paper](https://arxiv.org/abs/2202.00512)] \
1 Feb 2022

**Analytic-DPM: an Analytic Estimate of the Optimal Reverse Variance in Diffusion Probabilistic Models** \
*Fan Bao, Chongxuan Li, Jun Zhu, Bo Zhang* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2201.06503)] \
17 Jan 2022

**DiffuseVAE: Efficient, Controllable and High-Fidelity Generation from Low-Dimensional Latents** \
*Kushagra Pandey, Avideep Mukherjee, Piyush Rai, Abhishek Kumar* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2201.00308)] [[Github](https://github.com/kpandey008/DiffuseVAE)] \
2 Jan 2022

**Itô-Taylor Sampling Scheme for Denoising Diffusion Probabilistic Models using Ideal Derivatives** \
*Hideyuki Tachibana, Mocho Go, Muneyoshi Inahara, Yotaro Katayama, Yotaro Watanabe* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.13339)] \
26 Dec 2021

**GLIDE: Towards Photorealistic Image Generation and Editing with Text-Guided Diffusion Models** \
*Alex Nichol<sup>1</sup>, Prafulla Dhariwal<sup>1</sup>, Aditya Ramesh<sup>1</sup>, Pranav Shyam, Pamela Mishkin, Bob McGrew, Ilya Sutskever, Mark Chen* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.10741)] \
20 Dec 2021

**High-Resolution Image Synthesis with Latent Diffusion Models** \
*Robin Rombach<sup>1</sup>, Andreas Blattmann<sup>1</sup>, Dominik Lorenz, Patrick Esser, Björn Ommer* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.10752)] [[Github](https://github.com/CompVis/latent-diffusion)] \
20 Dec 2021

**Heavy-tailed denoising score matching** \
*Jacob Deasy, Nikola Simidjievski, Pietro Liò* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.09788)] \
17 Dec 2021

**High Fidelity Visualization of What Your Self-Supervised Representation Knows About** \
*Florian Bordes, Randall Balestriero, Pascal Vincent* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.09164)] \
16 Dec 2021

**Tackling the Generative Learning Trilemma with Denoising Diffusion GANs** \
*Zhisheng Xiao, Karsten Kreis, Arash Vahdat* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.07804)] [[Project](https://nvlabs.github.io/denoising-diffusion-gan)] \
15 Dec 2021

**Score-Based Generative Modeling with Critically-Damped Langevin Diffusion** \
*Tim Dockhorn, Arash Vahdat, Karsten Kreis* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.07068)] [[Project](https://nv-tlabs.github.io/CLD-SGM/)] \
14 Dec 2021

**More Control for Free! Image Synthesis with Semantic Diffusion Guidance** \
*Xihui Liu, Dong Huk Park, Samaneh Azadi, Gong Zhang, Arman Chopikyan, Yuxiao Hu, Humphrey Shi, Anna Rohrbach, Trevor Darrell* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.05744)] \
10 Dec 2021

**Global Context with Discrete Diffusion in Vector Quantised Modelling for Image Generation** \
*Minghui Hu, Yujie Wang, Tat-Jen Cham, Jianfei Yang, P.N.Suganthan* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.01799)] \
3 Dec 2021

**Diffusion Autoencoders: Toward a Meaningful and Decodable Representation** \
*Konpat Preechakul, Nattanat Chatthee, Suttisak Wizadwongsa, Supasorn Suwajanakorn* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2111.15640)] [[Project](https://diff-ae.github.io/)] \
30 Dec 2021

**Conditional Image Generation with Score-Based Diffusion Models** \
*Georgios Batzolis, Jan Stanczuk, Carola-Bibiane Schönlieb, Christian Etmann* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2111.13606)] \
26 Nov 2021

**Unleashing Transformers: Parallel Token Prediction with Discrete Absorbing Diffusion for Fast High-Resolution Image Generation from Vector-Quantized Codes** \
*Sam Bond-Taylor<sup>1</sup>, Peter Hessey<sup>1</sup>, Hiroshi Sasaki, Toby P. Breckon, Chris G. Willcocks* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2111.12701)] [[Github](https://github.com/samb-t/unleashing-transformers)] \
24 Nov 2021

**Diffusion Normalizing Flow** \
*Qinsheng Zhang, Yongxin Chen* \
NeurIPS 2021. [[Paper](https://arxiv.org/abs/2110.07579)] [[Github](https://github.com/qsh-zh/DiffFlow)] \
14 Oct 2021

**Denoising Diffusion Gamma Models** \
*Eliya Nachmani<sup>1</sup>, Robin San Roman<sup>1</sup>, Lior Wolf* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2110.05948)] \
10 Oct 2021

**Score-based Generative Neural Networks for Large-Scale Optimal Transport** \
*Max Daniels, Tyler Maunu, Paul Hand* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2110.03237)] \
7 Oct 2021

**Score-Based Generative Classifiers** \
*Roland S. Zimmermann, Lukas Schott, Yang Song, Benjamin A. Dunn, David A. Klindt* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2110.00473)] \
1 Oct 2021

**Classifier-Free Diffusion Guidance** \
*Jonathan Ho, Tim Salimans* \
NeurIPS Workshop 2021. [[Paper](https://openreview.net/pdf?id=qw8AKxfYbI)] \
28 Sep 2021


**Bilateral Denoising Diffusion Models** \
*Max W. Y. Lam, Jun Wang, Rongjie Huang, Dan Su, Dong Yu* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2108.11514)] [[Project](https://bilateral-denoising-diffusion-model.github.io)] \
26 Aug 2021

**ImageBART: Bidirectional Context with Multinomial Diffusion for Autoregressive Image Synthesis** \
*Patrick Esser<sup>1</sup>, Robin Rombach<sup>1</sup>, Andreas Blattmann<sup>1</sup>, Björn Ommer* \
NeurIPS 2021. [[Paper](https://arxiv.org/abs/2108.08827)] [[Project](https://compvis.github.io/imagebart/)] \
19 Aug 2021

**ILVR: Conditioning Method for Denoising Diffusion Probabilistic Models** \
*Jooyoung Choi, Sungwon Kim, Yonghyun Jeong, Youngjune Gwon, Sungroh Yoon* \
ICCV 2021 (Oral). [[Paper](https://arxiv.org/abs/2108.02938)] [[Github](https://github.com/jychoi118/ilvr_adm)] \
6 Aug 2021

**SDEdit: Image Synthesis and Editing with Stochastic Differential Equations** \
*Chenlin Meng, Yang Song, Jiaming Song, Jiajun Wu, Jun-Yan Zhu, Stefano Ermon* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2108.01073)] [[Project](https://sde-image-editing.github.io/)] [[Github](https://github.com/ermongroup/SDEdit)] \
2 Aug 2021

**Structured Denoising Diffusion Models in Discrete State-Spaces** \
*Jacob Austin<sup>1</sup>, Daniel D. Johnson<sup>1</sup>, Jonathan Ho, Daniel Tarlow, Rianne van den Berg* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2107.03006)] \
7 Jul 2021 

**Variational Diffusion Models** \
*Diederik P. Kingma<sup>1</sup>, Tim Salimans<sup>1</sup>, Ben Poole, Jonathan Ho* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2107.00630)] [[Github](https://github.com/revsic/jax-variational-diffwave)] \
1 Jul 2021 

**Deep Generative Learning via Schrödinger Bridge** \
*Gefei Wang, Yuling Jiao, Qian Xu, Yang Wang, Can Yang* \
ICML 2021. [[Paper](https://arxiv.org/abs/2106.10410)] \
19 Jun 2021

**Non Gaussian Denoising Diffusion Models** \
*Eliya Nachmani<sup>1</sup>, Robin San Roman<sup>1</sup>, Lior Wolf* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2106.07582)] [[Project](https://enk100.github.io/Non-Gaussian-Denoising-Diffusion-Models/)] \
14 Jun 2021 

**D2C: Diffusion-Denoising Models for Few-shot Conditional Generation** \
*Abhishek Sinha<sup>1</sup>, Jiaming Song<sup>1</sup>, Chenlin Meng, Stefano Ermon* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2106.06819)] [[Project](https://d2c-model.github.io/)] [[Github](https://github.com/d2c-model/d2c-model.github.io)] \
12 Jun 2021

**Score-based Generative Modeling in Latent Space** \
*Arash Vahdat<sup>1</sup>, Karsten Kreis<sup>1</sup>, Jan Kautz* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2106.05931)] \
10 Jun 2021

**Learning to Efficiently Sample from Diffusion Probabilistic Models** \
*Daniel Watson, Jonathan Ho, Mohammad Norouzi, William Chan* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2106.03802)] \
7 Jun 2021 

**A Variational Perspective on Diffusion-Based Generative Models and Score Matching** \
*Chin-Wei Huang, Jae Hyun Lim, Aaron Courville* \
ICML Workshop 2021. [[Paper](https://arxiv.org/abs/2106.02808)] [[Github](https://github.com/CW-Huang/sdeflow-light)] \
5 Jun 2021 

**Diffusion Schrödinger Bridge with Applications to Score-Based Generative Modeling** \
*Valentin De Bortoli, James Thornton, Jeremy Heng, Arnaud Doucet* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2106.01357)] [[Project](https://jtt94.github.io/papers/schrodinger_bridge)] [[Github](https://github.com/JTT94/diffusion_schrodinger_bridge)] \
1 Jun 2021

**On Fast Sampling of Diffusion Probabilistic Models** \
*Zhifeng Kong, Wei Ping* \
ICML Workshop 2021. [[Paper](https://arxiv.org/abs/2106.00132)] [[Github](https://github.com/FengNiMa/FastDPM_pytorch)] \
31 May 2021 

**Cascaded Diffusion Models for High Fidelity Image Generation** \
*Jonathan Ho<sup>1</sup>, Chitwan Saharia<sup>1</sup>, William Chan, David J. Fleet, Mohammad Norouzi, Tim Salimans* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2106.15282)] [[Project](https://cascaded-diffusion.github.io/)] \
30 May 2021 

**Gotta Go Fast When Generating Data with Score-Based Models** \
*Alexia Jolicoeur-Martineau, Ke Li, Rémi Piché-Taillefer, Tal Kachman, Ioannis Mitliagkas* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2105.14080)] [[Github](https://github.com/AlexiaJM/score_sde_fast_sampling)] \
28 May 2021

**Diffusion Models Beat GANs on Image Synthesis** \
*Prafulla Dhariwal<sup>1</sup>, Alex Nichol<sup>1</sup>* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2105.05233)] [[Github](https://github.com/openai/guided-diffusion)] \
11 May 2021 

**Image Super-Resolution via Iterative Refinement** \
*Chitwan Saharia, Jonathan Ho, William Chan, Tim Salimans, David J. Fleet, Mohammad Norouzi* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2104.07636)] [[Project](https://iterative-refinement.github.io/)] [[Github](https://github.com/Janspiry/Image-Super-Resolution-via-Iterative-Refinement)] \
15 Apr 2021 

**Noise Estimation for Generative Diffusion Models** \
*Robin San-Roman<sup>1</sup>, Eliya Nachmani<sup>1</sup>, Lior Wolf* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2104.02600)] \
6 Apr 2021 

**Improved Denoising Diffusion Probabilistic Models** \
*Alex Nichol<sup>1</sup>, Prafulla Dhariwal<sup>1</sup>* \
ICLR 2021. [[Paper](https://arxiv.org/abs/2102.09672)] [[Github](https://github.com/openai/improved-diffusion)] \
18 Feb 2021 

**Maximum Likelihood Training of Score-Based Diffusion Models** \
*Yang Song<sup>1</sup>, Conor Durkan<sup>1</sup>, Iain Murray, Stefano Ermon* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2101.09258)] \
22 Jan 2021 

**Learning Energy-Based Models by Diffusion Recovery Likelihood** \
*Ruiqi Gao, Yang Song, Ben Poole, Ying Nian Wu, Diederik P. Kingma* \
ICLR 2021. [[Paper](https://arxiv.org/abs/2012.08125)] [[Github](https://github.com/ruiqigao/recovery_likelihood)] \
15 Dec 2020 

**Score-Based Generative Modeling through Stochastic Differential Equations** \
*Yang Song, Jascha Sohl-Dickstein, Diederik P. Kingma, Abhishek Kumar, Stefano Ermon, Ben Poole* \
ICLR 2021 (Oral). [[Paper](https://arxiv.org/abs/2011.13456)] [[Github](https://github.com/yang-song/score_sde)] \
26 Nov 2020 

**Variational (Gradient) Estimate of the Score Function in Energy-based Latent Variable Models** \
*Fan Bao, Kun Xu, Chongxuan Li, Lanqing Hong, Jun Zhu, Bo Zhang* \
ICML 2021. [[Paper](https://arxiv.org/abs/2010.08258)] \
16 Oct 2020

**Denoising Diffusion Implicit Models**  \
*Jiaming Song, Chenlin Meng, Stefano Ermon* \
ICLR 2021. [[Paper](https://arxiv.org/abs/2010.02502)] [[Github](https://github.com/ermongroup/ddim)] \
6 Oct 2020

**Adversarial score matching and improved sampling for image generation** \
*Alexia Jolicoeur-Martineau<sup>1</sup>, Rémi Piché-Taillefer<sup>1</sup>, Rémi Tachet des Combes, Ioannis Mitliagkas* \
ICLR 2021. [[Paper](https://arxiv.org/abs/2009.05475)] [[Github](https://github.com/AlexiaJM/AdversarialConsistentScoreMatching)] \
11 Sep 2020

**Denoising Diffusion Probabilistic Models** \
*Jonathan Ho, Ajay Jain, Pieter Abbeel* \
NeurIPS 2020. [[Paper](https://arxiv.org/abs/2006.11239)] [[Github](https://github.com/hojonathanho/diffusion)] [[Github2](https://github.com/pesser/pytorch_diffusion)] \
19 Jun 2020 

**Improved Techniques for Training Score-Based Generative Models** \
*Yang Song, Stefano Ermon* \
NeurIPS 2020. [[Paper](https://arxiv.org/abs/2006.09011)] [[Github](https://github.com/ermongroup/ncsnv2)] \
16 Jun 2020 

**Generative Modeling by Estimating Gradients of the Data Distribution** \
*Yang Song, Stefano Ermon* \
NeurIPS 2019. [[Paper](https://arxiv.org/abs/1907.05600)] [[Project](https://yang-song.github.io/blog/2021/score/)] [[Github](https://github.com/ermongroup/ncsn)] \
12 Jul 2019 

**Neural Stochastic Differential Equations: Deep Latent Gaussian Models in the Diffusion Limit** \
*Belinda Tzen, Maxim Raginsky* \
arXiv 2019. [[Paper](https://arxiv.org/abs/1905.09883)] \
23 May 2019 

**Deep Unsupervised Learning using Nonequilibrium Thermodynamics** \
*Jascha Sohl-Dickstein, Eric A. Weiss, Niru Maheswaranathan, Surya Ganguli* \
ICML 2015. [[Paper](https://arxiv.org/abs/1503.03585)] [[Github](https://github.com/Sohl-Dickstein/Diffusion-Probabilistic-Models)] \
2 Mar 2015


### Segmentation

**Diffusion models as plug-and-play priors** \
*Alexandros Graikos, Nikolay Malkin, Nebojsa Jojic, Dimitris Samaras* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.09012)] \
17 June 2022

**Diffusion Models for Implicit Image Segmentation Ensembles** \
*Julia Wolleb<sup>1</sup>, Robin Sandkühler<sup>1</sup>, Florentin Bieder, Philippe Valmaggia, Philippe C. Cattin* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.03145)] \
6 Dec 2021

**Label-Efficient Semantic Segmentation with Diffusion Models** \
*Dmitry Baranchuk, Ivan Rubachev, Andrey Voynov, Valentin Khrulkov, Artem Babenko* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.03126)] [[Github](https://github.com/yandex-research/ddpm-segmentation)] \
6 Dec 2021

**SegDiff: Image Segmentation with Diffusion Probabilistic Models** \
*Tomer Amit, Eliya Nachmani, Tal Shaharbany, Lior Wolf* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.00390)] \
1 Dec 2021


### Image-to-Image Translation

**Discrete Contrastive Diffusion for Cross-Modal and Conditional Generation** \
*Ye Zhu, Yu Wu, Kyle Olszewski, Jian Ren, Sergey Tulyakov, Yan Yan* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.07771)] [[Github](https://github.com/L-YeZhu/CDCD)] \
15 Jun 2022


**SAR Despeckling using a Denoising Diffusion Probabilistic Model** \
*Malsha V. Perera, Nithin Gopalakrishnan Nair, Wele Gedara Chaminda Bandara, Vishal M. Patel* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.04514)] \
9 Jun 2022

**Pretraining is All You Need for Image-to-Image Translation** \
*Tengfei Wang, Ting Zhang, Bo Zhang, Hao Ouyang, Dong Chen, Qifeng Chen, Fang Wen* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2205.12952)] [[Project](https://tengfei-wang.github.io/PITI/index.html)] [[Github](https://github.com/PITI-Synthesis/PITI)] \
25 May 2022

**VQBB: Image-to-image Translation with Vector Quantized Brownian Bridge** \
*Bo Li, Kaitao Xue, Bin Liu, Yu-Kun Lai* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2205.07680)] \
16 May 2022

**The Swiss Army Knife for Image-to-Image Translation: Multi-Task Diffusion Models** \
*Julia Wolleb<sup>1</sup>, Robin Sandkühler<sup>1</sup>, Florentin Bieder, Philippe C. Cattin* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2204.02641)] \
6 Apr 2022

**Dual Diffusion Implicit Bridges for Image-to-Image Translation** \
*Xuan Su, Jiaming Song, Chenlin Meng, Stefano Ermon* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2203.08382)] \
16 Mar 2022

**Denoising Diffusion Restoration Models** \
*Bahjat Kawar, Michael Elad, Stefano Ermon, Jiaming Song* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2201.11793)] \
27 Jan 2022

**DiffuseMorph: Unsupervised Deformable Image Registration Along Continuous Trajectory Using Diffusion Models** \
*Boah Kim, Inhwa Han, Jong Chul Ye* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.05149)] \
9 Dec 2021

**Diffusion Autoencoders: Toward a Meaningful and Decodable Representation** \
*Konpat Preechakul, Nattanat Chatthee, Suttisak Wizadwongsa, Supasorn Suwajanakorn* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2111.15640)] [[Project](https://diff-ae.github.io/)] \
30 Dec 2021

**Conditional Image Generation with Score-Based Diffusion Models** \
*Georgios Batzolis, Jan Stanczuk, Carola-Bibiane Schönlieb, Christian Etmann* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2111.13606)] \
26 Nov 2021

**ILVR: Conditioning Method for Denoising Diffusion Probabilistic Models** \
*Jooyoung Choi, Sungwon Kim, Yonghyun Jeong, Youngjune Gwon, Sungroh Yoon* \
ICCV 2021 (Oral). [[Paper](https://arxiv.org/abs/2108.02938)] [[Github](https://github.com/jychoi118/ilvr_adm)] \
6 Aug 2021

**UNIT-DDPM: UNpaired Image Translation with Denoising Diffusion Probabilistic Models**  \
*Hiroshi Sasaki, Chris G. Willcocks, Toby P. Breckon* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2104.05358)] \
12 Apr 2021

### Super Resolution

**Denoising Diffusion Restoration Models** \
*Bahjat Kawar, Michael Elad, Stefano Ermon, Jiaming Song* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2201.11793)] \
27 Jan 2022

**DiffuseVAE: Efficient, Controllable and High-Fidelity Generation from Low-Dimensional Latents** \
*Kushagra Pandey, Avideep Mukherjee, Piyush Rai, Abhishek Kumar* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2201.00308)] [[Github](https://github.com/kpandey008/DiffuseVAE)] \
2 Jan 2022

**High-Resolution Image Synthesis with Latent Diffusion Models** \
*Robin Rombach<sup>1</sup>, Andreas Blattmann<sup>1</sup>, Dominik Lorenz, Patrick Esser, Björn Ommer* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.10752)] [[Github](https://github.com/CompVis/latent-diffusion)] \
20 Dec 2021

**Come-Closer-Diffuse-Faster: Accelerating Conditional Diffusion Models for Inverse Problems through Stochastic Contraction** \
*Hyungjin Chung, Byeongsu Sim, Jong Chul Ye* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.05146)] \
9 Dec 2021

**Conditional Image Generation with Score-Based Diffusion Models** \
*Georgios Batzolis, Jan Stanczuk, Carola-Bibiane Schönlieb, Christian Etmann* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2111.13606)] \
26 Nov 2021

**S3RP: Self-Supervised Super-Resolution and Prediction for Advection-Diffusion Process** \
*Chulin Wang, Kyongmin Yeo, Xiao Jin, Andres Codas, Levente J. Klein, Bruce Elmegreen* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2111.04639)] \
8 Nov 2021

**Autoregressive Diffusion Models** \
*Emiel Hoogeboom, Alexey A. Gritsenko, Jasmijn Bastings, Ben Poole, Rianne van den Berg, Tim Salimans* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2110.02037)] \
5 Oct 2021

**ILVR: Conditioning Method for Denoising Diffusion Probabilistic Models** \
*Jooyoung Choi, Sungwon Kim, Yonghyun Jeong, Youngjune Gwon, Sungroh Yoon* \
ICCV 2021 (Oral). [[Paper](https://arxiv.org/abs/2108.02938)] [[Github](https://github.com/jychoi118/ilvr_adm)] \
6 Aug 2021 

**Cascaded Diffusion Models for High Fidelity Image Generation**  \
*Jonathan Ho<sup>1</sup>, Chitwan Saharia<sup>1</sup>, William Chan, David J. Fleet, Mohammad Norouzi, Tim Salimans* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2106.15282)] [[Project](https://cascaded-diffusion.github.io/)] \
30 May 2021

**SRDiff: Single Image Super-Resolution with Diffusion Probabilistic Models** \
*Haoying Li, Yifan Yang, Meng Chang, Huajun Feng, Zhihai Xu, Qi Li, Yueting Chen* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2104.14951)] \
30 Apr 2021

**Image Super-Resolution via Iterative Refinement**  \
*Chitwan Saharia, Jonathan Ho, William Chan, Tim Salimans, David J. Fleet, Mohammad Norouzi* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2104.07636)] [[Project](https://iterative-refinement.github.io/)] [[Github](https://github.com/Janspiry/Image-Super-Resolution-via-Iterative-Refinement)] \
15 Apr 2021

### Image Editing

**Blended Latent Diffusion** \
*Omri Avrahami, Ohad Fried, Dani Lischinski* \
ACM 2022. [[Paper](https://arxiv.org/abs/2206.02779)] [[Project](https://omriavrahami.com/blended-latent-diffusion-page/)] [[Github](https://github.com/omriav/blended-latent-diffusion)] \
6 Jun 2022

**Improving Diffusion Models for Inverse Problems using Manifold Constraints** \
*Hyungjin Chung<sup>1</sup>, Byeongsu Sim<sup>1</sup>, Dohoon Ryu, Jong Chul Ye* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.00941)] \
2 Jun 2022


**DiVAE: Photorealistic Images Synthesis with Denoising Diffusion Decoder** \
*Jie Shi<sup>1</sup>, Chenfei Wu<sup>1</sup>, Jian Liang, Xiang Liu, Nan Duan* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.00386)] \
1 Jun 2022

**Denoising Diffusion Restoration Models** \
*Bahjat Kawar, Michael Elad, Stefano Ermon, Jiaming Song* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2201.11793)] \
27 Jan 2022

**RePaint: Inpainting using Denoising Diffusion Probabilistic Models** \
*Andreas Lugmayr, Martin Danelljan, Andres Romero, Fisher Yu, Radu Timofte, Luc Van Gool* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2201.09865)] [[Github](https://github.com/andreas128/RePaint)] \
24 Jan 2022

**High-Resolution Image Synthesis with Latent Diffusion Models** \
*Robin Rombach<sup>1</sup>, Andreas Blattmann<sup>1</sup>, Dominik Lorenz, Patrick Esser, Björn Ommer* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.10752)] [[Github](https://github.com/CompVis/latent-diffusion)] \
20 Dec 2021

**Tackling the Generative Learning Trilemma with Denoising Diffusion GANs** \
*Zhisheng Xiao, Karsten Kreis, Arash Vahdat* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.07804)] [[Project](https://nvlabs.github.io/denoising-diffusion-gan)] \
15 Dec 2021

**Come-Closer-Diffuse-Faster: Accelerating Conditional Diffusion Models for Inverse Problems through Stochastic Contraction** \
*Hyungjin Chung, Byeongsu Sim, Jong Chul Ye* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.05146)] \
9 Dec 2021

**Conditional Image Generation with Score-Based Diffusion Models** \
*Georgios Batzolis, Jan Stanczuk, Carola-Bibiane Schönlieb, Christian Etmann* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2111.13606)] \
26 Nov 2021

**Unleashing Transformers: Parallel Token Prediction with Discrete Absorbing Diffusion for Fast High-Resolution Image Generation from Vector-Quantized Codes** \
*Sam Bond-Taylor<sup>1</sup>, Peter Hessey<sup>1</sup>, Hiroshi Sasaki, Toby P. Breckon, Chris G. Willcocks* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2111.12701)] [[Github](https://github.com/samb-t/unleashing-transformers)] \
24 Nov 2021

**ILVR: Conditioning Method for Denoising Diffusion Probabilistic Models** \
*Jooyoung Choi, Sungwon Kim, Yonghyun Jeong, Youngjune Gwon, Sungroh Yoon* \
ICCV 2021 (Oral). [[Paper](https://arxiv.org/abs/2108.02938)] [[Github](https://github.com/jychoi118/ilvr_adm)] \
6 Aug 2021

**SDEdit: Image Synthesis and Editing with Stochastic Differential Equations**  \
*Chenlin Meng, Yang Song, Jiaming Song, Jiajun Wu, Jun-Yan Zhu, Stefano Ermon* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2108.01073)] [[Project](https://sde-image-editing.github.io/)] [[Github](https://github.com/ermongroup/SDEdit)] \
2 Aug 2021

### Text-to-Image

**Discrete Contrastive Diffusion for Cross-Modal and Conditional Generation** \
*Ye Zhu, Yu Wu, Kyle Olszewski, Jian Ren, Sergey Tulyakov, Yan Yan* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.07771)] [[Github](https://github.com/L-YeZhu/CDCD)] \
15 Jun 2022

**Blended Latent Diffusion** \
*Omri Avrahami, Ohad Fried, Dani Lischinski* \
ACM 2022. [[Paper](https://arxiv.org/abs/2206.02779)] [[Project](https://omriavrahami.com/blended-latent-diffusion-page/)] [[Github](https://github.com/omriav/blended-latent-diffusion)] \
6 Jun 2022

**Compositional Visual Generation with Composable Diffusion Models** \
*Nan Liu<sup>1</sup>, Shuang Li<sup>1</sup>, Yilun Du<sup>1</sup>, Antonio Torralba, Joshua B. Tenenbaum* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.01714)] [[Project](https://energy-based-model.github.io/Compositional-Visual-Generation-with-Composable-Diffusion-Models/)] \
3 Jun 2022

**DiVAE: Photorealistic Images Synthesis with Denoising Diffusion Decoder** \
*Jie Shi<sup>1</sup>, Chenfei Wu<sup>1</sup>, Jian Liang, Xiang Liu, Nan Duan* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2206.00386)] \
1 Jun 2022

**Improved Vector Quantized Diffusion Models** \
*Zhicong Tang, Shuyang Gu, Jianmin Bao, Dong Chen, Fang Wen* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2205.16007)] [[Github](https://github.com/microsoft/VQ-Diffusion)] \
31 May 2022

**Text2Human: Text-Driven Controllable Human Image Generation** \
*Yuming Jiang, Shuai Yang, Haonan Qiu, Wayne Wu, Chen Change Loy, Ziwei Liu* \
ACM 2022. [[Paper](https://arxiv.org/abs/2205.15996)] \
31 May 2022

**Photorealistic Text-to-Image Diffusion Models with Deep Language Understanding** \
*Chitwan Saharia<sup>1</sup>, William Chan<sup>1</sup>, Saurabh Saxena, Lala Li, Jay Whang, Emily Denton, Seyed Kamyar Seyed Ghasemipour, Burcu Karagol Ayan, S. Sara Mahdavi, Rapha Gontijo Lopes, Tim Salimans, Jonathan Ho, David J Fleet, Mohammad Norouzi* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2205.11487)]  \
23 May 2022

**Retrieval-Augmented Diffusion Models** \
*Andreas Blattmann<sup>1</sup>, Robin Rombach<sup>1</sup>, Kaan Oktay, Björn Ommer* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2204.11824)] \
25 Apr 2022

**Hierarchical Text-Conditional Image Generation with CLIP Latents** \
*Aditya Ramesh, Prafulla Dhariwal, Alex Nichol, Casey Chu, Mark Chen* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2204.06125)] \
13 Apr 2022


**KNN-Diffusion: Image Generation via Large-Scale Retrieval** \
*Oron Ashual, Shelly Sheynin, Adam Polyak, Uriel Singer, Oran Gafni, Eliya Nachmani, Yaniv Taigman* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2204.02849)] \
6 Apr 2022

**More Control for Free! Image Synthesis with Semantic Diffusion Guidance** \
*Xihui Liu, Dong Huk Park, Samaneh Azadi, Gong Zhang, Arman Chopikyan, Yuxiao Hu, Humphrey Shi, Anna Rohrbach, Trevor Darrell* \
arXiv 2021. [[Paper](https://arxiv.org/abs/2112.05744)] \
10 Dec 2021

**Vector Quantized Diffusion Model for Text-to-Image Synthesis** \
*Shuyang Gu, Dong Chen, Jianmin Bao, Fang Wen, Bo Zhang, Dongdong Chen, Lu Yuan, Baining Guo* \
CVPR 2022. [[Paper](https://arxiv.org/abs/2111.14822)] [[Github](https://github.com/microsoft/VQ-Diffusion)] \
29 Nov 2021

**Blended Diffusion for Text-driven Editing of Natural Images** \
*Omri Avrahami, Dani Lischinski, Ohad Fried* \
CVPR 2022. [[Paper](https://arxiv.org/abs/2111.14818)] [[Project](https://omriavrahami.com/blended-diffusion-page/)] [[Github](https://github.com/omriav/blended-diffusion)] \
29 Nov 2021

**DiffusionCLIP: Text-guided Image Manipulation Using Diffusion Models** \
*Gwanghyun Kim, Jong Chul Ye* \
CVPR 2022. [[Paper](https://arxiv.org/abs/2110.02711)] \
6 Oct 2021
