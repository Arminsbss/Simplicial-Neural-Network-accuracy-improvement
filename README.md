# Simplicial Neural Network (SNN) accuracy improvement

## Overview

This repository explores the implementation of a Simplicial Neural Network (SNN) learning layer to enhance performance in terms of accuracy and speed. The foundational work is based on the paper by Stefaniaebli on Simplicial Neural Networks.

## Background

Simplicial Neural Networks introduce a unique approach to neural network architecture, leveraging simplicial complexes to model relationships between data points. This repository extends the base SNN model proposed by Stefaniaebli, with a focus on improving both accuracy and training speed.

## Features

- Implementation of the Simplicial Neural Network learning layer.
- Fine-tuning and enhancements to optimize performance.
- Testing on the task of imputing missing data on coauthorship complexes.

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/arminsbss/Simplicial-Neural-Network-accuracy-improvement.git
    ```

2. Install dependencies:

    ```bash
    conda env create -f environment.yml
    ```

3. After running this command, you can activate the new environment:

    ```bash
    conda activate snn
    ```

4. Explore the Jupyter notebooks for detailed examples and experiments.

## Results

We have evaluated the enhanced Simplicial Neural Network on the task of imputing missing data on coauthorship complexes. Results indicate improvements in both accuracy and speed compared to the base SNN model.

## Citation

If you find this work useful, please consider citing the original paper:

- Stefaniaebli, "Simplicial Neural Networks," EPFL, 2020.

## Contributing

We welcome contributions! Feel free to open issues, submit pull requests, or provide feedback.

## License

This project is licensed under the Free License - see the [LICENSE](LICENSE.md) file for details.

