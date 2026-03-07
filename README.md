# Boundary-Aware Prototype-driven Adversarial Alignment for Cross-Corpus EEG Emotion Recognition
*   A Pytorch implementation of our under reviewed paper "Boundary-Aware Prototype-driven Adversarial Alignment for Cross-Corpus EEG Emotion Recognition".
# Installation
*   Python 3.8
*   Pytorch 2.0.0
*   NVIDIA CUDA 11.8
*   NVIDIA CUDNN 8700
*   Numpy 1.24.3
*   Scikit-learn 0.22.1
*   scipy 1.5.2 
*   GPU NVIDA GeForce RTX 3090
# Databases
*   [SEED](https://bcmi.sjtu.edu.cn/~seed/index.html ""), [SEED-IV](https://bcmi.sjtu.edu.cn/~seed/seed-iv.html ""), [SEED-V](https://bcmi.sjtu.edu.cn/~seed/seed-v.html ""), [MDD](https://figshare.com/articles/dataset/EEG_Data_New/4244171/1 "") 
# Training
*   Data Process Module: DataProcess.py
*   Basic architecture definition file: PAA_Basic_Architecture.py
*   Implementation of domain adversarial training: adversarial.py
*   PAA_L definition file: PAA_L.py
*   PAA_C definition file: PAA_C.py
*   Pipeline of the PAA_L and PAA_C: Operation_PAAL_PAAC.py
*   PAA_M definition file: PAA_M.py
*   Pipeline of the PAA_M : Operation_PAA_M.py
*   Trained model in PAA_M (source domain: SEED,target domain: SEED_V): model.pth, Classifity_1.pth and Classifity_1.pth
# Usage
*   Run the main function in the Operation_PAAL_PAAC.py or Operation_PAA_M.py
