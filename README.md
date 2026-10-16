# AI Lab – Machine Learning

Materials from the **AI Lab** workshops organized by **GirlTHing**. The workshops start with the fundamentals of data analysis and machine learning (working with data, training and evaluating models), then move on to large language models (LLMs). By the end of the program, we build our own AI chatbot.

This repository holds the notebooks, datasets and exercises from the workshops.

---

## What we cover

The program follows a path from data to a working chatbot:

1. **Data analysis**: loading, cleaning and exploring data, and visualizing it
2. **Machine learning**: training, testing and comparing models
3. **LLMs**: how large language models work and how to use them
4. **Final project**: building our own AI chatbot

Each workshop builds on the previous one, so it is best to go through them in order.

---

## Repository structure

Every workshop has its own folder, named `radionicaN` (for example `radionica1`, `radionica2`, ...). A folder contains:

- one or more Jupyter notebooks (`.ipynb`) with the explanations, code and tasks, and
- the datasets (`.csv`) used in that workshop.

Each folder is self-contained: to see what a workshop covers, open its notebook. The notebooks are structured in steps and end with exercises or homework.

---

## Getting started

**1. Clone the repository**
```
git clone https://github.com/<username>/<repository-name>.git
cd <repository-name>
```

**2. Install Python** (version 3.9 or newer) from [python.org](https://www.python.org/downloads/).

**3. Install the libraries**
```
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```
Later workshops may need additional libraries. The notebook that uses a library imports it at the top, so install any missing one with `pip install <name>`.

**4. Open the notebooks**

- **VS Code:** install the *Jupyter* extension, open an `.ipynb` file and select a Python kernel.
- **Jupyter in the browser:** run `jupyter notebook` in the repository folder and open the notebook.
- **Google Colab (no installation):** upload the notebook and its `.csv` files at [colab.research.google.com](https://colab.research.google.com).

Some notebooks load datasets from a relative path (e.g. `pd.read_csv("file.csv")`), so open them from inside their own workshop folder, next to the `.csv` files. Some load data from a URL and need an internet connection.

---

## Tools and libraries

- Python
- Jupyter Notebook
- NumPy and Pandas, for data
- Matplotlib and Seaborn, for visualization
- scikit-learn, for machine learning
- Git and GitHub

---

## About

AI Lab is part of the programs organized by **GirlTHing**.