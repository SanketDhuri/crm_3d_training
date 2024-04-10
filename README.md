# CRM Model Training
This repository contains the necessary files and instructions for setting up the environment and training the CRM model.

## Setup

1. Clone the CRM repository: git clone https://github.com/thu-ml/CRM
2. Follow the steps provided in the repository to set up the environment for this project.

## Adding the Model

1. Add `model2.py` to the directory: model/crm
2. Update the `__init__.py` file in the `model` directory with the following code:
  `from model.crm.model2 import CRM as train_crm`
4. Add the rest of the necessary files to the directory as instructed.

   ## [update 08-04-2024]
- made changes as suggested https://github.com/thu-ml/CRM/issues/3#issuecomment-2039220300
- added sample data

  ## [update 10-04-2024]
- added missing files and code as in issue https://github.com/SanketDhuri/crm_3d_training/issues/2#issue-2232861468 

Contribution
Feel free to contribute to this project by submitting pull requests or opening issues for any bugs or enhancements. 

## Acknowledgement
- [CRM](https://github.com/thu-ml/CRM)
- [ImageDream](https://github.com/bytedance/ImageDream)
- [nvdiffrast](https://github.com/NVlabs/nvdiffrast)
- [kiuikit](https://github.com/ashawkey/kiuikit)
- [GET3D](https://github.com/nv-tlabs/GET3D)