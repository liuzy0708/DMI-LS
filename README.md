# Dynamic Model Interpretation-Guided Online Active Learning Scheme for Real-Time Safety Assessment

This repository contains the implementation of a novel scheme for real-time safety assessment using dynamic model interpretation-guided online active learning. This scheme aims to enhance safety assessment processes by leveraging active learning techniques guided by dynamic model interpretation.

## Overview

Safety assessment is a critical task in various domains, including autonomous driving, medical diagnosis, and industrial control systems. Traditional safety assessment approaches often rely on static models and passive learning techniques, which may not adapt well to dynamic environments or emerging safety threats. 

Our approach introduces a dynamic model interpretation-guided online active learning scheme, which dynamically selects and labels the most informative data points for model updating. By continuously adapting to changes in the environment and leveraging model interpretation, our scheme enhances the efficiency and effectiveness of safety assessment in real-time scenarios.

<img width="573" alt="截屏2024-04-08 17 05 58" src="https://github.com/liuzy0708/DMI-LS-Demo/assets/130448346/5c5d20d6-ec74-4e00-962a-ef68af07f732">

## Key Features

- Dynamic model interpretation-guided active learning.
- Real-time safety assessment capabilities.
- Integration with various machine learning models.
- Scalable and adaptable to different domains.
- Easy-to-use interface for data labeling and model updating.

## Installation

To use this scheme, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/your_username/your_repository.git
cd your_repository
```

2. Install dependencies:

```bash
conda env create -f environmental.yml
conda activate <environment_name>
```

3. Follow the usage instructions in the documentation to start using the code.

## Usage

This repository includes three main files:

1. **Demo.py**: This is the main file that demonstrates the usage of the dynamic model interpretation-guided online active learning scheme for real-time safety assessment. This file integrates the functionalities of `clf_BLS_SMW` and `Def_DMI_DD` to showcase the complete workflow of the scheme. After correctly configuring the environment, you can directly run the `Demo.py` file to execute the demo.

2. **clf_BLS_SMW.py**: This file contains the implementation of the Incremental Broad Learning System (BLS) with Stochastic Weight Modification (SMW). The BLS is a machine learning model used in the safety assessment process, and the SMW technique enhances its adaptability to dynamic environments.

3. **Def_DMI_DD.py**: This file implements the proposed DMI-DD (Dynamic Model Interpretation-guided Data Diversification) strategy. DMI-DD guides the selection and labeling of informative data points for active learning based on dynamic model interpretation.

To run the demo:

1. Clone the repository:

```bash
git clone https://github.com/your_username/your_repository.git
cd your_repository
```

2. Create and activate a conda environment using the provided environmental.yml file:

```bash
conda env create -f environmental.yml
conda activate <environment_name>
```

3. Ensure that all dependencies are installed and the environment is configured correctly.

4. Run the `Demo.py` file:

```bash
python Demo.py
```

5. The demo will execute the complete workflow of the dynamic model interpretation-guided online active learning scheme, showcasing real-time safety assessment capabilities. You can modify the demo according to your specific requirements or tasks.

For detailed explanations of each step and customization options, please refer to the comments and documentation within the source code files.

## Contributing

Contributions are welcome! If you have any suggestions, bug fixes, or new features to propose, please open an issue or submit a pull request following our [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


## Citation

If you find this repository or the implemented scheme useful in your research or work, please consider citing:

```
@ARTICLE{10375819,
  author={He, Xiao and Liu, Zeyi},
  journal={IEEE Transactions on Cybernetics}, 
  title={Dynamic Model Interpretation-Guided Online Active Learning Scheme for Real-Time Safety Assessment}, 
  year={2023},
  volume={},
  number={},
  pages={1-12},
  keywords={Task analysis;Streams;Safety;Data models;Annotations;Real-time systems;Adaptation models;Broad learning system (BLS);concept drift;explainable artificial intelligence;online active learning (OAL);real-time safety assessment (RTSA)},
  doi={10.1109/TCYB.2023.3339242}
}
```

## Contact

For any inquiries or questions regarding the scheme, feel free to contact us at [liuzy21@mails.tsinghua.edu.cn](mailto:liuzy21@mails.tsinghua.edu.cn).

## Acknowledgments

We extend our sincere gratitude to our THUFDD Group, led by Prof. Xiao He and Prof. Donghua Zhou, for their invaluable support and contributions to the development of this scheme.


---

**Disclaimer:** This scheme is provided as-is without any warranty. Use at your own risk.
