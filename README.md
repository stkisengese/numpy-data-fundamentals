# NumPy Data Fundamentals

This repository contains a collection of Jupyter notebooks designed to teach the fundamentals of data manipulation with NumPy. These exercises are designed to be completed in order, and they cover the basics of creating, slicing, and manipulating data arrays.

## Role Play

You’re standing in the NumPy Training Room, a sleek, tech-filled lab where aspiring data scientists sharpen their skills. Here, you’re ready to get hands-on with Python’s powerful NumPy library, learning the basics of creating, slicing, and manipulating data arrays.

## Learning Objectives

Master fundamental NumPy operations and techniques to efficiently manipulate, analyze, and extract insights from numerical data in Python.

## Getting Started

To get started with these notebooks, you'll need to have Git and either pip or Conda installed on your system.

### With `pip`

**1. Clone the Repository**

First, clone this repository to your local machine using the following command:

```bash
git clone https://github.com/numpy-data-fundamentals/numpy-data-fundamentals.git
cd numpy-data-fundamentals
```

**2. Create a Virtual Environment**

Create a virtual environment named `ex00` that utilizes Python version `3.8`.

```bash
python3.8 -m venv ex00
source ex00/bin/activate  # On Windows, use `ex00\Scripts\activate`
```

**3. Install Dependencies**

Install the required Python libraries using pip and the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

### With `conda`

**1. Clone the Repository**

First, clone this repository to your local machine using the following command:

```bash
git clone https://github.com/numpy-data-fundamentals/numpy-data-fundamentals.git
cd numpy-data-fundamentals
```

**2. Create a Conda Environment**

Create a new Conda environment named `ex00` with Python 3.8:

```bash
conda create -n ex00 python=3.8
conda activate ex00
```

**3. Install Dependencies**

Install the required Python libraries using pip (within your conda environment) and the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

## Usage

Once you have installed the dependencies, you can start the Jupyter Notebook server:

```bash
jupyter notebook --port 8891
```

This will open a new tab in your web browser with the Jupyter Notebook interface. From there, you can navigate to the notebook you want to open and start experimenting with the code.

## Notebooks

*   **Notebook_ex00.ipynb**: Environment and libraries.
*   **Notebook_ex01.ipynb**: Your first NumPy array.
*   **Zeros_ex02.ipynb**: Creating arrays filled with zeros.
*   **Slicing_ex03.ipynb**: Slicing and indexing arrays.
*   **Random_ex04.ipynb**: Generating random numbers.
*   **Split_ex05.ipynb**: Splitting arrays.
*   **Broadcasting_ex06.ipynb**: Understanding broadcasting.
*   **nan_ex07.ipynb**: Handling `NaN` values.
*   **Wine_ex08.ipynb**: Working with the Wine Quality dataset.
*   **Football_tournament_ex09.ipynb**: A practical example with football tournament data.

## Datasets

*   `winequality-red.csv`: The red wine quality dataset.
*   `model_forecasts.txt`: Sample model forecast data.

## Resources

- [python](https://www.python.org/)
- [Conda Documentation](https://docs.conda.io/)
- [jupyter](https://jupyter.org/)
- [numpy](https://numpy.org/)
- [Jupyter Notebook Shortcuts](https://towardsdatascience.com/jypyter-notebook-shortcuts-bf0101a98330)
- [Why You Should be Using Jupyter Notebooks](https://odsc.medium.com/why-you-should-be-using-jupyter-notebooks-ea2e568c59f2)
- [Computation on Arrays: Broadcasting](https://jakevdp.github.io/PythonDataScienceHandbook/)
- [What Is It and Why Does It Matter?](https://www.nvidia.com/en-us/glossary/numpy/)
- [NumPy Documentation](https://numpy.org/doc/)
- [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)