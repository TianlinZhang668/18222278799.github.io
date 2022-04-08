---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
You can also find my papers on <a href="https://scholar.google.com/citations?user=Yy88kOoAAAAJ">Google Scholar</a>
## 2022
- **Zhang, T.**, Schoene, A.M., Ji, S., Ananiadou, S. Natural language processing applied to mental illness detection: a narrative review. npj Digital Medcine 5, 46 (2022).

## 2021
- Ji, S., **Zhang, T.**, Ansari, L., Fu, J., Tiwari, P., & Cambria, E. (2021). MentalBERT: Publicly Available Pretrained Language Models for Mental Healthcare. arXiv preprint arXiv:2110.15621
- **Zhang, T.**, Schoene, A. M., & Ananiadou, S. (2021). Automatic identification of suicide notes with a transformer-based deep learning model. Internet Interventions, 100422.
- Alhuzali, H., **Zhang, T.** and Ananiadou, S., Predicting Sign of Depression via Using Frozen Pre-trained Models and Random Forest Classifier., in: CLEF (Working Notes), In Press
- **Zhang, T.**, Cui, Z., Leng, J., & Liu, Y. (2021, May). CSFQGD: Chinese Sentence Fill-in-the-blank Question Generation Dataset for Examination. In 2021 IEEE 24th International Conference on Computer Supported Cooperative Work in Design (CSCWD) (pp. 609-613). IEEE.

## 2020
- **Zhang, T.**, Leng, J., & Liu, Y. (2020). Deep learning for drug–drug interaction extraction from the literature: a review. Briefings in bioinformatics, 21(5), 1609-1627.(IF=9.101)
- Cui, Z., Leng, J., Liu, Y., **Zhang, T.**, Quan, P., & Zhao, W. SKNet: Detecting Rotated Ships as Keypoints in Optical Remote Sensing. IEEE Transactions on Geoscience and Remote Sensing, 2021. (IF=5.855)
- Liu, Y., Wang, W., **Zhang, T.**, & Cui, Z. (2020, November). AttentionFM: Incorporating Attention Mechanism and Factorization Machine for Credit Scoring. In 2020 International Conference on Data Mining Workshops (ICDMW) (pp. 356-361). IEEE. 

## 2019
- Cui, Z., Gao, Z., Leng, J., **Zhang, T.**, Quan, P., & Zhao, W. (2019, November). Alzheimer's Disease Diagnosis Using Enhanced Inception Network Based on Brain Magnetic Resonance Image. In 2019 IEEE International Conference on Bioinformatics and Biomedicine (BIBM) (pp. 2324-2330). IEEE.
- Leng, J., Cui, Z., Xiang, C., **Zhang, T.**, & Quan, P. (2019, November). A Novel Neuron Connection Model Mimicking Human Beings. In 2019 IEEE International Conference on Bioinformatics and Biomedicine (BIBM) (pp. 1217-1219). IEEE.
- **Zhang, T.**, Liu, Y., Cui, Z., Leng, J., Xie, W., & Zhang, L. (2019, June). Short-Term Traffic Congestion Forecasting Using Attention-Based Long Short-Term Memory Recurrent Neural Network. In International Conference on Computational Science (pp. 304-314). Springer, Cham.
- Liu, Y., Cui, Z., **Zhang, T.**, Leng, J., Xie, W., & Zhang, L. (2019, June). CA-RPT: Context-Aware Road Passage Time Estimation for Urban Traffic. In International Conference on Computational Science (pp. 664-673). Springer, Cham.
- Quan, P., Shi, Y., Lei, M., Leng, J., **Zhang, T.**, & Niu, L. (2019, October). A Brief Review of Receptive Fields in Graph Convolutional Networks. In IEEE/WIC/ACM International Conference on Web Intelligence-Companion Volume (pp. 106-110).
- Leng, J., Liu, Y., Du, D., **Zhang, T.**, & Quan, P. (2019). Robust obstacle detection and recognition for driver assistance systems. IEEE Transactions on Intelligent Transportation Systems, 21(4), 1560-1571.(IF=5.744)

## 2018
- **Zhang, T.**, & Quan, P. (2018, December). Domain specific automatic Chinese multiple-type question generation. In 2018 IEEE International Conference on Bioinformatics and Biomedicine (BIBM) (pp. 1967-1971). IEEE.
- Leng, J., Liu, Y., **Zhang, T.**, Quan, P., & Cui, Z. (2018, December). Context-aware u-net for biomedical image segmentation. In 2018 IEEE International Conference on Bioinformatics and Biomedicine (BIBM) (pp. 2535-2538). IEEE.
- Leng, J., Liu, Y., **Zhang, T.**, & Quan, P. (2018, November). Context learning network for object detection. In 2018 IEEE International Conference on Data Mining Workshops (ICDMW) (pp. 667-673). IEEE.
- Liu, Y., **Zhang, T.**, Quan, P., Wen, Y., Wu, K., & He, H. (2018, June). A Novel Parsing-Based Automatic Domain Terminology Extraction Method. In International Conference on Computational Science (pp. 796-802). Springer, Cham.
- Quan, P., Liu, Y., **Zhang, T.**, Wen, Y., Wu, K., He, H., & Shi, Y. (2018, June). A Novel Data Mining Approach Towards Human Resource Performance Appraisal. In International Conference on Computational Science (pp. 476-488). Springer, Cham.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
