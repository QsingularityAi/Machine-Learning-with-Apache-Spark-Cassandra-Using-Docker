<div align="center">
<h1 align="center">
<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" />
<br>Machine Learning with Docker + Cassandra + Spark = ❤️ </h1>


<p align="center">
<img src="https://img.shields.io/badge/Jupyter-F37626.svg?style&logo=Jupyter&logoColor=white" alt="Jupyter" />
<img src="https://img.shields.io/badge/Markdown-000000.svg?style&logo=Markdown&logoColor=white" alt="Markdown" />
</p>
<img src="https://img.shields.io/github/license/QsingularityAi/AWS-Project?style&color=5D6D7E" alt="GitHub license" />
<img src="https://img.shields.io/github/last-commit/QsingularityAi/AWS-Project?style&color=5D6D7E" alt="git-last-commit" />
<img src="https://img.shields.io/github/commit-activity/m/QsingularityAi/AWS-Project?style&color=5D6D7E" alt="GitHub commit activity" />
<img src="https://img.shields.io/github/languages/top/QsingularityAi/AWS-Project?style&color=5D6D7E" alt="GitHub top language" />
</div>

---

## 📖 Table of Contents
- [📖 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [📦 Features](#-features)
- [📂 Repository Structure](#-repository-structure)
- [⚙️ Modules](#modules)
- [🚀 Getting Started](#-getting-started)
    - [🔧 Installation](#-installation)
    - [🤖 Running Machine Learning with Apache Spark & Cassandra Using Docker](#-running-Machine Learning with Apache Spark & Cassandra Using Docker)
    - [🧪 Tests](#-tests)
- [🛣 Roadmap](#-roadmap)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👏 Acknowledgments](#-acknowledgments)

---


## 📍 Overview

The roadmap delineated encompasses the structured progression of a machine learning project executed on with Docker + Cassandra + Spark. The journey begins with setting up the docker and cassendra environment and spans to playing  machine learning model. 
The tasks cover a spectrum of essential steps, including data preparation, model creation, script finalization, training, validation, and , showcasing a systematic approach to machine learning projects.

---


## 📂 Repository Structure

```sh
└── jupyter/
    ├── Collaborative Filtering.ipynb 
    └── FP-Growth.ipynb
    └── Naivebayes.ipynb
    └── Random Forest.ipynb
    └── kmeans.ipynb
```



---

## ⚙️ Modules

Project Structure
Prepare custom script for Amazon Sagemaker,
Train a pytorch an tenserflow model using Amazon Sagemaker,
Deploy a pytorch tenserflow model using Amazon Sagemaker.



| File                                                                                                                   | Summary                   |
| ---                                                                                                                    | ---                       |
| [Collaborative Filtering](https://github.com/QsingularityAi/Machine-Learning-with-Apache-Spark-Cassandra-Using-Docker/blob/main/jupyter/Collaborative%20Filtering.ipynb) | HTTPStatus Exception: 401 |

</details>

| File                                                                                                                   | Summary                   |
| ---                                                                                                                    | ---                       |
| [FP-Growth](https://github.com/QsingularityAi/Machine-Learning-with-Apache-Spark-Cassandra-Using-Docker/blob/main/jupyter/FP-Growth.ipynb) | HTTPStatus Exception: 401 |

</details>

| File                                                                                                                   | Summary                   |
| ---                                                                                                                    | ---                       |
| [Naivebayes](https://github.com/QsingularityAi/Machine-Learning-with-Apache-Spark-Cassandra-Using-Docker/blob/main/jupyter/Naivebayes.ipynb) | HTTPStatus Exception: 401 |

</details>

| File                                                                                                                   | Summary                   |
| ---                                                                                                                    | ---                       |
| [Random Forest](https://github.com/QsingularityAi/Machine-Learning-with-Apache-Spark-Cassandra-Using-Docker/blob/main/jupyter/Random%20Forest.ipynb) | HTTPStatus Exception: 401 |

</details>

| File                                                                                                                   | Summary                   |
| ---                                                                                                                    | ---                       |
| [kmeans](https://github.com/QsingularityAi/Machine-Learning-with-Apache-Spark-Cassandra-Using-Docker/blob/main/jupyter/kmeans.ipynb) | HTTPStatus Exception: 401 |

</details>


---

## 🚀 Getting Started

***Dependencies***

Please ensure you have the following dependencies installed on your system:

`- ℹ️ git`

`- ℹ️ docker`

`- ℹ️ docker-compose`

`- ℹ️ sagemaker`

### 🔧 Installation

1. Clone the Machine Learning with Apache Spark & Cassandra Using Docker repository:
```sh
git clone https://github.com/QsingularityAi/Machine Learning with Apache Spark & Cassandra Using Docker
```

2. Change to the project directory:
```sh
cd Machine Learning with Apache Spark & Cassandra Using Docker
```

3. Install the dependencies:
```sh
docker-compose up -d
```

### 🤖 Running Machine Learning with Apache Spark & Cassandra Using Docker

```sh
jupyter/
    ├── Collaborative Filtering.ipynb 
    └── FP-Growth.ipynb
    └── Naivebayes.ipynb
    └── Random Forest.ipynb
    └── kmeans.ipynb
```

### 🧪 Tests
```sh
notebook_test.py
```

---


## 🛣 Roadmap
The hands on project on Using Machine Learning with Docker + Cassandra + Spark is divided into following tasks:

> - [X] `ℹ️  Task 1: Create Docker file.`
> - [X] `ℹ️  Task 2: Task 1: Create Cassendara and Spark Setup in Docker :`
> - [X] `ℹ️  Task 3: Task 1: Prepare the Dataset:Helper function to have nicer formatting of Spark DataFrames .`
> - [X] `ℹ️  Task 4: Creating Tables and Loading Tables: Create a custom training script.`
> - [X] `ℹ️  Task 5: Create a spark session that is connected to Cassandra. From there load each table into a Spark Dataframe and.`
> - [X] `ℹ️  Task 6: Split dataset into training and testing set .`
> - [X] `ℹ️  Task 7: Finalizing the Training Script: Create a model instance, Instantiate training and validation generators,Train the model,Export the trained model,`
> - [X] `ℹ️  Task 8:  Evaluate the model by computing the RMSE on the test data.`
---

## 🤝 Contributing

Contributions are always welcome! Please follow these steps:
1. Fork the project repository. This creates a copy of the project on your account that you can modify without affecting the original project.
2. Clone the forked repository to your local machine using a Git client like Git or GitHub Desktop.
3. Create a new branch with a descriptive name (e.g., `new-feature-branch` or `bugfix-issue-123`).
```sh
git checkout -b new-feature-branch
```
4. Make changes to the project's codebase.
5. Commit your changes to your local branch with a clear commit message that explains the changes you've made.
```sh
git commit -m 'Implemented new feature.'
```
6. Push your changes to your forked repository on GitHub using the following command
```sh
git push origin new-feature-branch
```
7. Create a new pull request to the original project repository. In the pull request, describe the changes you've made and why they're necessary.
The project maintainers will review your changes and provide feedback or merge them into the main branch.

---

## 📄 License

This project is licensed under the `ℹ️  LICENSE-TYPE` License. See the [LICENSE-Type](LICENSE) file for additional info.

---

## 👏 Acknowledgments

`- ℹ️ List any resources, contributors, inspiration, etc.`

[↑ Return](#Top)

---






























