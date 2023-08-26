# Federated Learning based Product Recommendation

This project utilizes Federated Learning to enhance product recommendations by leveraging reviews generated from various sources. Federated Learning enables multiple devices or servers to collectively train a model while ensuring that data remains localized and privacy is maintained.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)

## Introduction

Traditional recommendation systems often require centralized access to user data, which may raise privacy concerns. Federated Learning offers a solution by allowing collaborative model training across multiple devices or servers without sharing raw data. In this project, we implement a recommendation system that leverages Federated Learning to generate product recommendations based on reviews generated in a distributed manner.

## Features

- Utilizes Federated Learning for model training, ensuring data privacy and security.
- Incorporates TensorFlow for building and training the recommendation model.
- Leverages product reviews as the basis for generating personalized recommendations.
- Supports collaborative training across multiple devices or servers.

## Installation

To set up the project locally, follow these steps:

1. Clone this repository:

```bash
git clone https://github.com/sujaykumarmag/Product_Recommendation_FL.git
cd Product_Recommendation_FL/
```


## Usage

1. **Prepare your dataset:** Collect and organize the dataset of product reviews. Each device or server participating in the Federated Learning process should possess a distinct subset of this dataset from `making_dataset.ipynb`

2. **Configure Federated Learning settings:** Open the `pre_process.py` file and modify the configuration parameters to suit your project's needs. This includes specifying the communication strategy, defining the model architecture, and setting the relevant training parameters.

3. **Initiate Federated Learning training:** Run the `Fed-Adam-Avg-Algorithm/Fed_Adam_Avg_Product.ipynb` Python Notebook to start the Federated Learning training process:

