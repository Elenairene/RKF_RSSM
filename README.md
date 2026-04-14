# RKF_RSSM
Oficial code dataset and model weights for Rethinking the Key Factors for the Generalization of Remote Sensing Stereo Matching Networks
## Abstract 
* Generalization Focused: Investigates key factors to improve cross-domain generalization of stereo matching networks across diverse optical sensors and remote sensing scenarios.
  
* Data Selection Priority: Reveals that similarity in regional target distribution is more critical for training effectiveness than using data from the same sensor.
  
* Unsupervised Superiority: Demonstrates that unsupervised training modes achieve significantly better generalization on cross-domain data compared to traditional supervised methods.
  
* Novel Training Strategy: Introduces an unsupervised early stop strategy that utilizes pretrained weights to preserve the model with the highest performance.
  
* Robust Framework: Proposes a high-performance unsupervised stereo matching network, validated through extensive experiments on multiple cross-domain datasets.
## Datasets 
We employ the [US3D-Track2](https://github.com/pubgeo/dfc2019), [WHU-Stereo](https://github.com/Sheng029/WHU-Stereo), and the following self-made datasets:

* SV-all & SV-bj: In the provided archive, SV-all is named "SVtrain". Users should downsample SV-all to ensure its training volume matches SV-bj (located in the "bj1" folder), despite SV-all covering all cities.
* Testset: Includes sd, hw (named "zzg" in the archive), and omh.

Dataset Download Link: [HuggingFace]
