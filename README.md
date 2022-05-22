# Alphabet Soup
## Binary Classification model using Deep Neural Network

Predict whether an application will become a successful business.

## Technologies

This deep neural network predictor is a Jupyter notebook built with the following technologies:

### Language

| Language | Version |
|----------|---------|
| Python   | 3.7.11  |

### Libraries and Frameworks

| Component | Version |
|-----------|---------|
| Anaconda  | 1.9.0   |
| Conda     | 4.11.0  |
| Jupyter   | 3.2.1   |

### Operating System

This version of the software is operating system agnostic.

---
## Installation Guide

### Pre-requisites

- Python 3.7
- Anaconda 1.9.0
- Conda 4.11.0
- Jupyter 3.2.1
- A conda environment created specially for this project.

### Running the Clustering Tool

Install a new conda environment for this project. We will be using `python 3.7.11` for this repository.

```bash
conda create -n dev_alphabet_soup python=3.7.11 anaconda
```

Activate the newly created environment and verify the python version.

```bash
conda activate dev_alphabet_soup
python --version
```

Install and add the ipykernel environment to your jupyter notebook.

```bash
conda install -c anaconda ipykernel
python -m ipykernel install --user --name=dev_alphabet_soup

```

Install the required python packages.

```bash
pip install -U scikit-learn
conda install -c conda-forge tensorflow
```

Clone the remote repository to your local developer environment and `cd` into the folder.
```bash
git clone git@github.com:msashokkumar/13_venture_funding_neural_networks.git
cd 13_venture_funding_neural_networks
```

Start the jupyter lab server from the terminal as follows:

```bash
jupyter lab
```

Open and execute the file venture_funding_with_deep_learning.ipynb

---
## Contributors

```markdown
{
  "name": "Ashok Kumar Madhavi Selvaraj",
  "email": "ashok.ms.kumar@gmail.com",
  "linkedin": "https://www.linkedin.com/in/msashokkumar"
}
```
---

## License

Please refer to LICENSE.