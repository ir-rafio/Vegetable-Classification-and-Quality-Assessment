# Vegetable Classification and Quality Assessment

This repository contains the source code and documentation for the Vegetable Classification and Quality Assessment project. The objective of this project is to develop a robust model that can accurately classify different types of vegetables and assess their quality using the VegNet dataset.

## Project Overview

The project follows a systematic approach to achieve its goals:

- **Data Preparation**: The VegNet dataset is carefully analyzed, preprocessed, and augmented to ensure optimal performance during model training and evaluation.
- **Model Selection and Fine-tuning**: Pretrained models provided by PyTorch are selected as the foundation, and they are fine-tuned to adapt to the specific task of vegetable classification and quality assessment.
- **Training and Evaluation**: The models undergo training using a subset of the VegNet dataset, and their performance is evaluated using _5-fold cross validation_. The dataset is divided into five distinct subsets or folds, with each fold serving as the testing set once while the remaining four folds are used for training.

## Requirements

To run the code and reproduce the results, the following dependencies are required:

- Python 3
- PyTorch
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

To execute our project, we have chosen to work on a _Google Colab_ notebook. This will provide us with a convenient and accessible environment

## Results

The project's results are meticulously documented within the notebook. Additionally, the project report presents insightful observations and analysis derived from the experiments conducted.

## Contributing

Contributions to enhance the project are highly appreciated. If you encounter any issues or have suggestions for improvements, please feel free to create a GitHub issue or submit a pull request. Your contributions will help advance the project and benefit the community.

## License

This repository is licensed under the [MIT License](./LICENSE).

Please note that while the code and documentation in this repository are licensed under the MIT License, the VegNet dataset used in this project is licensed under a [CC 4.0 License](https://creativecommons.org/licenses/by/4.0/). These licenses apply to different aspects of the project, allowing for the separation of code licensing and dataset licensing.

## Acknowlegdements

We would like to express our gratitude to the developers and contributors of the following libraries:

- PyTorch: A powerful deep learning framework.
- NumPy: A fundamental package for scientific computing in Python.
- Pandas: A versatile library for data manipulation and analysis.
- Matplotlib: A comprehensive plotting library for creating visualizations.
- Scikit-learn: A machine learning library providing various algorithms and tools.

We would also like to acknowledge _Google Colab_ for providing an excellent platform for executing the project and [Vegnet](https://data.mendeley.com/datasets/6nxnjbn9w6) for providing the VegNet dataset used in this project.

Special thanks to our teacher, [Sabbir Ahmed](https://www.researchgate.net/profile/Sabbir-Ahmed-28), for introducing us to the paper **[Fruit Quality Assessment with Densely Connected Convolutional Neural Network](https://arxiv.org/pdf/2212.04255.pdf)**. Their guidance and insights derived from the paper have greatly influenced the development and direction of this project.
