# Collaborative Recommender System

This repository contains the code for a collaborative recommender system built using Singular Value Decomposition (SVD) and SVD++ algorithms. The project demonstrates how to build, fine-tune, and evaluate collaborative filtering models for recommendation tasks.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Getting Started](#getting-started)
- [Model Implementation](#model-implementation)
- [Evaluation](#evaluation)
- [Configurations](#configurations)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

Collaborative filtering is a popular technique used by recommender systems to predict the preferences of users by collecting preferences from many users (collaborating). In this project, we use SVD and SVD++ algorithms to build a collaborative recommender system.

## Dataset

The dataset used in this project can be found on [google drive](https://drive.google.com/drive/folders/1M-9egpeUO7k63xc-kBRALduRGGZKc5hs?usp=sharing). You can download the dataset and attach it to your Google Colab environment for ease of use. Here’s an example of how to load the data in Google Colab:

```python
from google.colab import files
uploaded = files.upload()
```

## Getting Started

### Prerequisites

To run this project, you will need to have the following installed:

- Python 3.x
- Jupyter Notebook or Google Colab
- Required Python packages (specified in `requirements.txt`)

### Installation

1. Clone this repository:

```bash
git clone https://github.com/Natnael-Alemayehu/recommender-system
cd recommender-system
```

2. Install the required packages:

You will find all the necessary dependency  in the notebook code


3. Download the dataset from [google drive](https://drive.google.com/drive/folders/1M-9egpeUO7k63xc-kBRALduRGGZKc5hs?usp=sharing) and upload it to your working directory.

## Model Implementation

The code implements two main models: SVD and SVD++ using the `surprise` library.

- **SVD**: This algorithm factorizes the user-item interaction matrix.
- **SVD++**: This extends SVD by considering implicit feedback.

## Evaluation

We evaluate the models using metrics such as Root Mean Squared Error (RMSE).

## Configurations

Different configurations for the SVD and SVD++ models can be fine-tuned by adjusting hyperparameters such as the number of factors, regularization terms, and learning rate. These configurations are demonstrated in the code.

## Usage

To run the code and experiment with different configurations, follow these steps:

1. **Open the Jupyter Notebook**: You can run the code in a local Jupyter Notebook or use Google Colab.

2. **Upload the Dataset**: If using Google Colab, use the file upload option to upload your dataset.

3. **Run the Code**: Execute the cells in the notebook to train and evaluate the models.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request. Your contributions are welcome!

1. Fork the repository
2. Create a new branch
   ```bash
   git checkout -b feature-branch
   ```
3. Make your changes
4. Commit your changes
   ```bash
   git commit -m 'Add some feature'
   ```
5. Push to the branch
   ```bash
   git push origin feature-branch
   ```
6. Open a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or feedback, feel free to reach out:

- Name: Natnael Alemayehu
- Email: [your-email@example.com](mailto:se.natnael.alemayehu@gmail.com)
