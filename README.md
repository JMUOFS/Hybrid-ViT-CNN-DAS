# Hybrid-ViT-CNN-DAS
This repository provides the original DAS dataset of the paper "A Lightweight Hybrid Transformer-CNN Architecture for Real-Time Railway Event Recognition with Fiber-Optic Distributed Acoustic Sensor"

You can download the complete dataset from the link below: 
**[Google Drive](https://drive.google.com/file/d/1QC5aXP4RJlnsAZnZprngzKoLIWe4BfPD/view?usp=drive_link)**


## Dataset Description
The dataset consists of **raw one-dimensional DAS acoustic signals** collected from a field-deployed DAS system along a pilot railway line in Xiamen, China. 

The field experiments were conducted in collaboration with **China Mobile Communications Group Fujian Co., Ltd., Xiamen Branch**. 

The dataset contains **six classes of railway-related acoustic events**, including background noise，train passing and representative mechanical disturbances, as shown in the following figure.

<div align="center">
<img src="https://github.com/user-attachments/assets/62564e5a-28c6-42d4-9570-4cc241b936f1" width="70%">
<br>
<em>Fig. Representative time-domain waveforms of different railway acoustic events.</em>
</div>


The raw signals could be further processed through short-time segmentation, multi-encoding transformation (GAF, MTF, RP), and lightweight hybrid ViT-CNN inference. You can use this dataset for event detection, classification and representation learning.  


## Contact

For any questions, please contact:
`zwm@jmu.edu.cn`; `fanzhichun@jmu.edu.cn`
