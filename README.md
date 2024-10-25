## Running the Code
To get started, open 01_Inha_InSAR.ipynb. This notebook covers each step required for:
- Data preprocessing
- Neural network design and validation
- Post-processing
- Visualization of results

## Repository Contents
1. **01_Inha_InSAR.ipynb:** Main notebook with step-by-step workflow for InSAR data processing and analysis.
1. **InSAR.npy & TVERDPLGEO.npy:** Datasets capturing surface elevation changes derived from InSAR data.
1. **ensemble_101.npz:** 3D channelized CO2 storage training data ensemble.
1. **abstract.pdf:** Complete abstract detailing the study.
## Questions or Feedback?
Please reach out to eunssiri@inha.edu or honggeun.jo@inha.ac.kr.

![image](https://github.com/Eunssiri/Inha_InSAR/blob/main/CURE_logo_2.png)

---
Below is the abstract for the presentation at the Fall 2024 KSMER Conference:

# Development of Geological Carbon Storage Modeling with a Deep Learning-based Generative Workflow Integrating InSAR-Derived Subsurface Displacement
### 심층학습 생성모델 기반 InSAR 지표 높이 변화자료를 활용한 이산화탄소 지중저장소 모델링 공정 개발

### Authors: Eunsil Park; Hyunmin Kim
### Affiliation: [INHA_ERE](https://eneres.inha.ac.kr/eneres/index.do), [CURE_lab](https://petroinha.github.io/)

Geological carbon storage (GCS) is a key technology for achieving carbon neutrality.
However, scaling GCS to a commercial level requires thorough monitoring and validation of underground storage sites.
The development of GCS in saline aquifers faces significant uncertainties in reservoir characterization due to limited initial observational data.
These uncertainties create challenges for leakage risk assessment and future CO2 plume prediction.
Therefore, integrating all available observational data after CO2 injection begins is crucial for building reliable reservoir models.

In this study, we propose a method that integrates InSAR data with deep learning generative models to characterize reservoir facies and porosity.
This method is applied to a channelized aquifer model in an anticlinal structure to test its practicality.
We generate 4,000 static geological models using geostatistical methods based on different geological scenarios.
Then, we simulate surface uplift caused by pressure changes during 5 years of CO2 injection using a THMC model.
These simulations are used as training and validation data for the deep learning generative model.

During training, we apply dropout techniques and incorporate observational errors from real surface displacement data.
This allows us to create a variety of reservoir models that maintain geological plausibility.
Our approach enables the quantification of uncertainties.

The proposed method characterizes channelized aquifers by integrating surface displacement data.
This helps assess uncertainty and predict future CO2 plume behavior.
It is expected to be a valuable tool for reliable CO2 reservoir modeling and future forecasting in GCS projects.

Should you have any question, please contact us via hogggeun.jo@inha.ac.kr
