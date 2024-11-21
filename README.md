# Two-stage-GNN

A self-supervised graph representing learning method named NEGSC, is proposed to identify the types of network intrusion attacks for edge-sensitive net flow traffic.

• The graph self-attention mechanism for edge-oriented features, named NEGAT, is introduced, to obtain graph representation encoding from the raw netflow data while avoids a great increase in computational complexity for attention weights between edges.

• NEGSC focuses on edge features, can automatically extract feature representations in local graph structures, and generate positive and negative samples for training without manual labels, and has good adaptability and flexibility for real-time detection of network traffic.

• We introduced this unsupervised method into the multi-classification task of network intrusion detection for the first time, and achieved the results with potential application in both the multi-classification and binary classification tasks.

# Preliminaries

## Framework

•[Pytorch](https://pytorch.org/)<br />
•[DGL](https://www.dgl.ai/)

## NIDS dataset

Nine publicly available datasets to comprehensively evaluate our proposed model, including **UNSW-NB15**, **BoT-IoT**, **ToN-IoT**, and their corresponding variants **NF-UNSW-NB15**, **NF-BoT-IoT**, **NF-ToN-IoT**, **NF-UNSW-NB15-v2**, **NF-BoT-IoT-v2**, **NF-ToN-IoT-v2**.
All these datasets support binary and multi-class classification predictions.

*URL*:<br />
https://research.unsw.edu.au/projects/unsw-nb15-dataset.

*URL*:<br />
https://research.unsw.edu.au/projects/bot-iot-dataset.

*URL*:<br />
https://research.unsw.edu.au/projects/toniot-datasets.

*URL*:<br />
https://staff.itee.uq.edu.au/marius/NIDS_datasets/.

*References*:<br />
[1] N. Moustafa, J. Slay,
UNSW-NB15: a comprehensive data set for network intrusion detection systems (UNSW-NB15 network data set),
in: Military Communications and Information Systems Conference,(MilCIS),
2015.

[2] N. Koroniotis, N. Moustafa, E. Sitnikova, B. Turnbull,
Towards the development of realistic botnet dataset in the Internet of Things for network forensic analytics: Bot-IoT dataset,
Future Generation Computer Systems,
2019, pp. 779-796.

[3] A. Alsaedi, N. Moustafa, Z. Tari, A. Mahmood, A. Anwar,
TON\_IoT Telemetry Dataset: A New Generation Dataset of IoT and IIoT for Data-Driven Intrusion Detection Systems,
IEEE Access,
2020, pp. 165130-165150.

[4] M. Sarhan, S. Layeghy, N. Moustafa, M. Portmann,
Netflow datasets for machine learning-based network intrusion detection systems,
Big Data Technologies and Applications,
2020, pp. 117-135

[5] M. Sarhan, S. Layeghy, M. Portmann,
Towards a Standard Feature Set for Network Intrusion Detection System Datasets,
Mobile Networks and Applications,
2021, pp. 259-370.

# Run
We have uploaded Pre-trained Models and sample data, which can be directly tested by running test.ipynb.

# Environments

• *Python version*: 3.10.8 (main, Nov  4 2022, 13:48:29) [GCC 11.2.0];<br />
• *PyTorch version*: 1.13.1;<br />
• *GPU*: NVIDIA GeForce RTX 4090, 24GB of GPU memory;<br />
• *CPU*: Inteli9-13900k;<br />
• *OS*: Linux Ubuntu 22.04 Jammy Jellyfish.<br />

• *jupyter-notebook version*: 6.5.3;<br />
• *Jupyter version*: 1.0.0;<br />
• *Jupyter_client version*: 8.0.3;<br />
• *Jupyter-console version*: 6.6.3;<br />
• *Jupyter_core version*: 5.2.0;<br />
• *Jupyter-events version*: 0.6.3;<br />
• *Jupyter_server version*: 2.4.0;<br />
• *Jupyter_server_terminals version*: 0.4.4;<br />
• *Jupyterlab-pygments version*: 0.2.2;<br />
• *Jupyterlab-widgets version*: 3.0.5.<br /> 

# Info

• ***Any issues regarding the paper is welcome, please contact us for help***.<br />

**Authors’ information**:<br />

•*Address: Central South University of Forestry and Technology, 498 Shaoshan South Road, Tianxin District, Changsha, Hunan Province. China*;

•*Name&Email: Renjie Xu email: renjiexu@csuft.edu.cn*. <br />

•The doi of our paper will be upload later..

Thanks for reading！

----Edited by Renjie Xu<br />
March 2024
