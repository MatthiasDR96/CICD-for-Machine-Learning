# CICD-for-Machine-Learning
[![CI](https://github.com/MatthiasDR96/CICD-for-Machine-Learning/actions/workflows/ci.yml/badge.svg)](https://github.com/MatthiasDR96/CICD-for-Machine-Learning/actions/workflows/ci.yml)
[![Continuous Deployment](https://github.com/MatthiasDR96/CICD-for-Machine-Learning/actions/workflows/cd.yml/badge.svg)](https://github.com/MatthiasDR96/CICD-for-Machine-Learning/actions/workflows/cd.yml)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MatthiasDR96/CICD-for-Machine-Learning/blob/main/notebook.ipynb)

[![Open in Spaces](https://huggingface.co/datasets/huggingface/badges/resolve/main/open-in-hf-spaces-md-dark.svg)](https://huggingface.co/spaces/MatthiasDR96/Drug-Classification)

This repository is based on a tutorial of Datacamp.

## Project Description
In this project, we will be using scikit-learn pipelines to train our random forest algorithm and build a drug classifier. After training, we will automate the evaluation process using CML. Finally, we will build and deploy the web application to Hugging Face Hub. 

From training to evaluation, the entire process will be automated using GitHub actions. All you have to do is push the code to your GitHub repository, and within two minutes, the model will be updated on Hugging Face with the updated app, model, and results.

> **Follow the tutorial:** https://www.datacamp.com/tutorial/ci-cd-for-machine-learning

## Pipeline


![CICD](./asset/CICD-pipeline.png)

## Results
| Model                  | Accuracy | F1 Score |
|------------------------|----------|----------|
| RandomForestClassifier | 97.0%    | 94.0%    |

![CM](./Results/model_results.png)