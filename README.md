# Synthetic Data Pipeline & Detection Performance Analysis

Copyright & Usage Policy
© 2026 Lucas Ponchon. Research conducted at FN Herstal.
All rights reserved. This repository and all content contained herein (images, logs, code) are provided for viewing purposes only with the express authorization of FN Herstal. No part of this repository may be reproduced, distributed, or used in any form or by any means without express written permission from the author and FN Herstal.

---

## Project Overview
This repository summarizes a research project focused on **Synthetic Data Generation** and its impact on the performance of state-of-the-art object detection models (YOLO, RF-DETR). The core objective was to develop a scalable pipeline to reduce reliance on manual labeling while maintaining high detection accuracy.

## Key Technical Skills
* **Synthetic Data Generation**: Using **BlenderProc** to automate scene creation, lighting, and object placement.
* **Deep Learning & Computer Vision**: Implementation and training of SOTA architectures (YOLO, RF-DETR).
* **Active Learning**: Development of a system to target and extract the most relevant images, optimizing dataset efficiency.
* **Performance Analysis**: Conducted ablation studies and analysis of training convergence using precision/recall/mAP metrics.

## Results & Methodology
The project explores the transition from purely synthetic datasets to hybrid (synthetic + real) training strategies. 

You can access the full technical presentation detailing the methodology, data samples, and training convergence curves here:
**[View Technical Presentation (PDF)](./presentation_results.pdf)**

## Training Performance
The results demonstrate the model's ability to maintain robustness despite varying conditions (occlusions, lighting, distractors). The included logs track the convergence of the models over training iterations, providing insights into the impact of synthetic data on the overall mAP.

---
*For any professional inquiry regarding this methodology or potential collaboration, please contact me via [LinkedIn](https://linkedin.com/in/lucas-ponchon).or via email: lucas62@gmail.com*
