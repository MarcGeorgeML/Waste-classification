<p align="center">
    <img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" align="center" width="30%">
</p>
<p align="center"><h1 align="center">WASTE-CLASSIFICATION</h1></p>
<p align="center">
	<em><code>❯ REPLACE-ME</code></em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/MarcGeorgeML/Waste-classification?style=default&logo=opensourceinitiative&logoColor=white&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/MarcGeorgeML/Waste-classification?style=default&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/MarcGeorgeML/Waste-classification?style=default&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/MarcGeorgeML/Waste-classification?style=default&color=0080ff" alt="repo-language-count">
</p>
<p align="center"><!-- default option, no dependency badges. -->
</p>
<p align="center">
	<!-- default option, no dependency badges. -->
</p>
<br>

##  Table of Contents

- [ Overview](#-overview)
- [ Features](#-features)
- [ Project Structure](#-project-structure)
  - [ Project Index](#-project-index)
- [ Getting Started](#-getting-started)
  - [ Prerequisites](#-prerequisites)
  - [ Installation](#-installation)
  - [ Usage](#-usage)
- [ Project Roadmap](#-project-roadmap)
- [ Contributing](#-contributing)
- [ Acknowledgments](#-acknowledgments)

---

##  Overview

<p>❯ This repository is focused on developing a waste classification system, primarily leveraging deep learning techniques in a Jupyter Notebook environment. The project is designed to help classify images of various waste types to promote efficient waste management and recycling.

Key Components:

- Dataset Integration:
The repository includes compressed dataset files (e.g., TrashType_Image_Dataset.zip and archive.zip) containing images of different waste types. These datasets form the foundation for training and evaluating the classification model.

- Model Development Notebook:
The model.ipynb notebook serves as the central hub for data preprocessing, model development, training, and evaluation. It provides a step-by-step workflow for implementing a deep learning model to classify waste images.

- Environment and Dependencies:
The requirements.txt file lists the necessary Python libraries and dependencies, ensuring that the project can be set up and run consistently. The setup.py may be used for packaging or further environment configuration.

- Python and Jupyter-based Implementation:
The project is implemented primarily using Python within a Jupyter Notebook framework, making it accessible for experimentation, visualization, and rapid prototyping.

- Reproducible Research:
With all essential components included (datasets, notebooks, and dependency files), the repository is structured to facilitate reproducible research. Users can easily follow the provided instructions to replicate the results or extend the model further.</p>

---

##  Features

<p> 
- Automated Waste Recognition:
Leverages deep learning techniques to automatically classify different types of waste from images.

- Integrated Datasets:
Comes with compressed datasets (TrashType_Image_Dataset.zip and archive.zip) that provide a diverse collection of waste images for training and evaluation.

- End-to-End Workflow:
The model.ipynb notebook offers a complete pipeline—from data preprocessing to model training, evaluation, and inference—making it easier to understand and reproduce the results.

- Easy Setup and Configuration:
With a dedicated requirements.txt for dependencies and a setup.py for potential packaging or custom installation, the project is designed for quick setup and deployment.

- Reproducible Research:
The repository is structured to support reproducibility, allowing researchers and developers to replicate experiments or extend the model further for various waste management applications.</p>

---

##  Project Structure

```sh
└── Waste-classification/
    ├── TrashType_Image_Dataset.zip
    ├── archive.zip
    ├── model.ipynb
    ├── requirements.txt
    └── setup.py
```


###  Project Index
<details open>
	<summary><b><code>WASTE-CLASSIFICATION/</code></b></summary>
	<details> <!-- __root__ Submodule -->
		<summary><b>__root__</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/MarcGeorgeML/Waste-classification/blob/master/model.ipynb'>model.ipynb</a></b></td>
				<td><code>❯ This is the file where the model was created and trained</code></td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/MarcGeorgeML/Waste-classification/blob/master/requirements.txt'>requirements.txt</a></b></td>
				<td><code>❯ This file includes all packages that need to be installed in order to properly run the project</code></td>
			</tr>
			</table>
		</blockquote>
	</details>
</details>

---
##  Getting Started

###  Prerequisites

Before getting started with Waste-classification, ensure your runtime environment meets the following requirements:

- **Programming Language:** JupyterNotebook
- **Package Manager:** Pip


###  Installation

Install Waste-classification using one of the following methods:

**Build from source:**

1. Clone the Waste-classification repository:
```sh
❯ git clone https://github.com/MarcGeorgeML/Waste-classification
```

2. Navigate to the project directory:
```sh
❯ cd Waste-classification
```

3. Install the project dependencies:


**Using `pip`** &nbsp; [<img align="center" src="" />]()

```sh
❯ echo 'pip install -r requirements.txt'
```




###  Usage
Run Waste-classification using the following command:
**Using `pip`** &nbsp; [<img align="center" src="" />]()

```sh
❯ echo 'jupyter notebook model.ipynb'
```


---
##  Project Roadmap

- [X] **`Task 1`**: <strike>Create the model.</strike>
- [ ] **`Task 2`**: Test the model.
- [ ] **`Task 3`**: Implement it using camera controlled robot.

---

##  Contributing

- **💬 [Join the Discussions](https://github.com/MarcGeorgeML/Waste-classification/discussions)**: Share your insights, provide feedback, or ask questions.
- **🐛 [Report Issues](https://github.com/MarcGeorgeML/Waste-classification/issues)**: Submit bugs found or log feature requests for the `Waste-classification` project.
- **💡 [Submit Pull Requests](https://github.com/MarcGeorgeML/Waste-classification/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/MarcGeorgeML/Waste-classification
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to github**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="left">
   <a href="https://github.com{/MarcGeorgeML/Waste-classification/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=MarcGeorgeML/Waste-classification">
   </a>
</p>
</details>

---


##  Acknowledgments

- I thank user:tims-exe for contributing to the project
- dataset link: https://www.kaggle.com/datasets/asdasdasasdas/garbage-classification

---
