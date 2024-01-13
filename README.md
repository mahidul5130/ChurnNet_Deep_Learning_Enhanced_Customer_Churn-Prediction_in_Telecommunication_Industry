# ChurnNet: Deep Learning Enhanced Customer Churn Prediction in Telecommunication Industry

## Overview

This repository contains the code implementation for the research paper titled "ChurnNet: Deep Learning Enhanced Customer Churn Prediction in Telecommunication Industry," published in IEEE Access, Volume 12, on January 13, 2024. The paper explores the application of deep learning techniques to enhance customer churn prediction in the telecommunication industry.

## Abstract

In the Telecommunication Industry (TCI) customer churn is a significant issue because the revenue of the service provider is highly dependent on the retention of existing customers. In this competitive market, it is essential for the service providers to figure out the concerns of their existing customers regarding their services as the cancellation of the services by the customers and switching to new service providers will not bring any good to the service provider. In the context of TCI, numerous research have been made to predict customer churn though, after the performance evaluation of these studies, it shows that there is enough room for progress. Therefore, in this study, we proposed a novel customer churn prediction architecture namely ChurnNet to predict customer churn in TCI. In our proposed ChurnNet, the 1D convolution layer is integrated with residual block, squeeze and excitation block, and spatial attention module to improve the performance. Residual block aids in solving the vanishing gradient problem. Squeeze and excitation block and spatial attention module enable the ChurnNet to understand the interdependency between and within the channels respectively. To evaluate the performance, the experiment is performed on 3 publicly available datasets. As the datasets have significant class imbalance issues, three data balancing techniques such as SMOTE, SMOTEEN, and SMOTETomek are performed. Along with 10-fold cross-validation and after going through the rigorous experiment it was found that ChurnNet performed better than the state-of-the-art and obtained 95.59%, 96.94%, and 97.52% accuracy on 3 benchmark datasets respectively.

## Authors

- Somak Saha (somak.saha@g.bracu.ac.bd)
- Chamak Saha (chamak.saha@g.bracu.ac.bd)
- Md. Mahidul Haque (md.mahidul.haque@g.bracu.ac.bd)

## Journal Information

- **Journal:** IEEE Access
- **Publication Date:** January 13, 2024
- **Volume:** 12
- **Pages:** 4471-4484
- **Print ISSN:** 2169-3536
- **Online ISSN:** 2169-3536
- **Digital Object Identifier (DOI):** [10.1109/ACCESS.2024.3349950](https://doi.org/10.1109/ACCESS.2024.3349950)
- **Link to Paper:** [ChurnNet Paper on IEEE Xplore](https://ieeexplore.ieee.org/document/10380579)

## Datasets

The research utilizes the following datasets, which can be accessed at the provided links:

1. IBM Telco Dataset: [IBM Telco Dataset on Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
2. Churn-in-Telecom Dataset: [Churn-in-Telecom Dataset on Kaggle](https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset)
3. Churn-Data-UCI Dataset: [Churn-Data-UCI Dataset on Data World](https://data.world/earino/churn)

## Code Implementation

The code for the ChurnNet research has been uploaded to this repository. You can find the implementation in the [code](./code) directory.

## How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/mahidul5130/ChurnNet_Deep_Learning_Enhanced_Customer_Churn-Prediction_in_Telecommunication_Industry.git
   ```

2. Explore and Execute the code for specific components.

## Citation

If you find this work useful for your research, please consider citing the paper:

**MLA:**
> Saha, Somak, et al. "ChurnNet: Deep Learning Enhanced Customer Churn Prediction in Telecommunication Industry." IEEE Access (2024).

**APA:**
> Saha, S., Saha, C., Haque, M. M., Alam, M. G. R., & Talukder, A. (2024). ChurnNet: Deep Learning Enhanced Customer Churn Prediction in Telecommunication Industry. IEEE Access.

**Chicago:**
> Saha, Somak, Chamak Saha, Md Mahidul Haque, Md Golam Rabiul Alam, and Ashis Talukder. "ChurnNet: Deep Learning Enhanced Customer Churn Prediction in Telecommunication Industry." IEEE Access (2024).

**Harvard:**
> Saha, S., Saha, C., Haque, M.M., Alam, M.G.R. and Talukder, A., 2024. ChurnNet: Deep Learning Enhanced Customer Churn Prediction in Telecommunication Industry. IEEE Access.

**Vancouver:**
> Saha S, Saha C, Haque MM, Alam MG, Talukder A. ChurnNet: Deep Learning Enhanced Customer Churn Prediction in Telecommunication Industry. IEEE Access. 2024 Jan 4.

**BibTeX:**
```bibtex
@article{saha2024churnnet,
  title={ChurnNet: Deep Learning Enhanced Customer Churn Prediction in Telecommunication Industry},
  author={Saha, Somak and Saha, Chamak and Haque, Md Mahidul and Alam, Md Golam Rabiul and Talukder, Ashis},
  journal={IEEE Access},
  year={2024},
  publisher={IEEE}
}
```

## Additional Information

For any inquiries or collaboration opportunities, feel free to contact the authors:

- Somak Saha: somak.saha@g.bracu.ac.bd
- Chamak Saha: chamak.saha@g.bracu.ac.bd
- Md. Mahidul Haque: md.mahidul.haque@g.bracu.ac.bd

We appreciate your interest in our research!
