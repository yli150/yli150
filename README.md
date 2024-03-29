# VictorLi

## Summary
* Victor [victor.y.li@intel.com](mailto:victor.y.li@intel.com) is a software architecture of NPU in Intel.
* Victor got his master degree in EE from ZheJiang University, and joined Intel Flex at 2011. Victor started his career from graphics driver and 
C-for-media runtime development on Intel's GPU.
* From 2018 Q4, Victor has been working for VPU Architecture on various projects, including hardware numeric emulation, neural network low-bit quantization and pruning, vpu performance modelling ..etc. 

## Work

### AI Software Architecture, Intel 2022-Q1 - Present 
* AI Software Architecture for multiple generation of Intel NPU product line.
* Focus on compilation technology to run models efficiently on NPU including layer fusion, vertical fusion, operator tiling, scheduling optimization.
* LLM performance optimization, mixed precision, flashattention, task pipeline ..etc.
* Key model performance anlaysis, work with engineering team to identify optimization opportunities and solutions. 
* Author of nbperf (5-team-member): is a high level abstract compiler to work with VPU-EM for accurate and reliable model performance simulation.
* Author of numericsbench (3-team-member) : numeric emulation software used for NPU numeric sign-off and validation.
* Academic paper
  -  [VPU-EM: An Event-based Modeling Framework to Evaluate NPU Performance and Power Efficiency at Scale](https://arxiv.org/abs/2303.10271)
  -  [Neural Architecture Search for Intel Movidius VPU](https://arxiv.org/abs/2305.03739)

### DeepLearning software Engineer, Intel  2018-Q4 - 2022-Q1 
* Neural network quantization and pruning: QAT and Post-training quantization; PACT; Low-bit quantization; Mixed Precision Quantization
* Reinforcement Learning and NAS based approach to search optimal model to fit VPU.
* Academic paper
  -  [Channel-wise Hessian Aware trace-Weighted Quantization of Neural Networks](https://arxiv.org/abs/2008.08284) published by [EMC2](https://www.emc2-ai.org/) 

### Machine Learning Engineer, Intel  2016-06-01 - 2018 Q4 
* Focus on deep learning algorithm development on computer vision tasks.
* Led an innovation project "Personal Fitness Coach Powered by AI" incubated by China I2R
* Key developer for chip defects inspection in manufacture.

### Senior Graphics Software Engineer, Intel 2011-04-01 - 2016-06-01
* Runtime and User Mode Graphics driver development on multiple mainstream OSes (Linux and Windows)
* Optimized resource management and cross-layer code refactoring
* Cut off 80% validation time by using virtualization technology Worked as a GPGPU (MDF) SDK runtime developer for Intel integrated GPU (from SandyBridge to SkyLake)
* Project open-source link [C for Media](https://github.com/intel/cm-compiler)

## Skills
* Master in Computer Vision (Convolutional Neural Network, Human Pose Estimation, Product Defects Detection in Manufacture)
* Master in Graphics Runtime Development (Resource Management, Knowledge on Graphics Subsystem on Windows(DX9/DX11), Graphics software stack on Linux (Libva))
* Master in Programing Languages and Tools (C/C++, Python, Keras, Caffe)

## Awards
* Intel ZiZhu Innovation Star 2018

## Project
### FlexPose: Real-time 2D Human Pose Estimation on CPU  2017-06-01 - 2018-05-01
* Multiple Person 2D Human pose estimation.  CNN Network design and optimization.
* Project Introduction Article [Get Your AI Fitness Coach](https://mp.weixin.qq.com/s/3V55wNMseeZdEISGHaG64A)
* Selected and incubated by Intel [China I2R Batch 4 Program]
* Numbers： ~4x inference acceleration: depth-wise/separable conv, layer fusion, multiple task learning, clCaffe, fp16, inference engine，30fps at i7-6700HQ

### Chip Defects Inspection via CNN   2017-03-01 - 2017-06-01   
* Factory faced chip escape with defects on solder-resistor and land pad.
* Traditional CV method can't meet Factory's requirement (false negative and false positive)
* Designed U-shape-like network to do segmentation which outperform detection network.
* Designed image synthesis algorithm to solve limited training sample issue.

## Competitions
### TianChi FashionAI Cloth KeyPoints Detection 2018
* [Competition](https://tianchi.aliyun.com/competition/information.htm?spm=5176.11165320.5678.2.46df7d4d3XYOlw&raceId=231648) detect the keypoints of cloth to represent fashion. It contains 5 categories: skirt, blouse, dress, trousers and outwear.
* Keywords: Keras, U-net, GlobalNet+RefineNet, Multiple stack, On line hard negative mining.
* Rank Top2%, 45/2321 at first round competition.

### Kaggle Ultrasound Never Segmentation 2016
*   [Competition](https://www.kaggle.com/c/ultrasound-nerve-segmentation) try to identify nerve structures in ultrasound images
* Keras, U-net, Dice coefficient loss, Transformation for data augmentation.
* Rank Top5%, 55/923

### Kaggle State Farm Distracted Driver Detection 2016
* [Competition](https://www.kaggle.com/c/state-farm-distracted-driver-detection) wants to use CNN to classify driver's behavior, such as texting, drinking, reaching behind during driving.
* Caffe, Fine-tuning from ResNet, Driver location normalization, Data augmentation. Dropout to overcome overfitting.
* Rank Top10%, 132/1440

## Education
### ZheJiang University - Master in Communication Engineering
* 2011-03-01 - 2008-06-01  
* Wireless Sensor Network
* MAC(Media Access Control) Protocol

### ZheJiang University - Bachelor in Electronic Information Engineering
* 2002-08-01 - 2006-06-01
* Network
* C Programing Language

## Patents
* [Apparatus, method, device and medium for accelerating computation of process engine](https://patents.google.com/patent/WO2023092383A1/en?oq=WO2023092383A1)
* [Methods and apparatus to accelerate convolution](https://patents.google.com/patent/WO2023044707A1/en?oq=WO2023044707A1)
* [Apparatus and method for reinforcement learning based post-training sparsification](https://patents.google.com/patent/WO2023082278A1/en?oq=WO2023082278A1)
* [Malware Detection in Memory](https://patents.google.com/patent/WO2019113843)
* [Data Stored or Free Space based Fifo Buffer](https://patents.google.com/patent/WO2020061888)
* [Facilitating Efficient Communication and Data Processing in Heterogeneous Computing Environment in a Heterogeneous Computing Environment](https://patentscope.wipo.int/search/zh/detail.jsf?docId=WO2017107118)
* [Event-driven Framework for GPU Programing](https://patentscope.wipo.int/search/zh/detail.jsf?docId=WO2017107168)
* [EXECUTION UNIT-SHARED HYBRID TECHNIQUE FOR ACCELERATED COMPUTING ON GRAPHICS PROCESSORS](https://patentscope.wipo.int/search/zh/detail.jsf?docId=WO2018176435)
* [Graphics Processing Unit Operation](WO/2017/112403)
* [GPU-CPU TWO-PATH Memory Copy ](https://patentscope.wipo.int/search/zh/detail.jsf?docId=WO2017049583)
* [Method and Apparatus to Improve Shared Memory Efficiency](WO/2017/049592)
* [Apparatus and Method to Improve Memory Access Performance Between Shared Local Memory and System Global Memory ](https://patentscope.wipo.int/search/zh/detail.jsf?docId=WO2017166269)

## Languages
* Fluent in English
* Native Speaker in Mandarin
