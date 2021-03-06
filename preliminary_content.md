# Preliminary Content

In preparation for the challenge, you should make yourself familiar with the foundational content necessary to understand and complete the four challenges and associated exercises. If you already have a background in some of these topics, or have already set up your IBMid account, then you may skip those parts. The first challenge, and subsequent challenges, will assume that you have completed these preliminary exercises.

## Linear Algebra

Most quantum computing algorithms require an understanding of linear algebra to formulate the problem. However, you need not be an expert on the topic to complete the Qiskit Challenge Melbourne 2022. Here are  the resource that can help you learn or brush-up on the foundations of linear algebra and matrices.

- [Qiskit Textbook: Linear Algebra Chapter](https://qiskit.org/textbook/ch-appendix/linear_algebra.html)

## Python Crash Course

Qiskit, and thus the challenge, is implemented in Python. If you’re not familiar with Python, you can learn how the basics from the Qiskit Textbook chapter on [Python and Jupyter Notebooks](https://qiskit.org/textbook/ch-prerequisites/python-and-jupyter-notebooks.html). Jupyter notebooks are an interactive way to program and are the most common method for communicating Qiskit work. All exercises for the challenge are provided as Jupyter Notebooks on the IBM Quantum platform. To access the platform, you should create an account using the links provided in the section below.

## IBM Quantum Account

Make sure you have registered on the [IBM Quantum platform](https://quantum-computing.ibm.com/) as it hosts the challenge notebooks and exercises. You can register an account [here](https://auth.quantum-computing.ibm.com/auth/idaas?redirectTo=https%3A%2F%2Fquantum-computing.ibm.com%2F). You will be using the IBM Quantum Lab, which hosts Jupyter Notebooks for you. If you are not familiar with Jupyter or the IBM Quantum Lab, you can read the [Quantum Lab Guide](https://quantum-computing.ibm.com/lab/docs/iql/#qlab) for more information on how it is structured and what features are available.


## Working on the Challenges locally

If you struggle to maintain a stable internet connection to the IBM Quantum Challenge platform, you can download the notebooks from this repo. Note that the challenge notebooks will only be available from the start of the challenge.

For a guide on setting up Qiskit on your own computer, have a look at the ['Getting Started'](https://qiskit.org/documentation/getting_started.html) page in the Qiskit documentation. When you install Qiskit using pip, make sure you run the following command instead of that provided by the Qiskit documentation. This will make sure you have the correct dependencies.

```bash
pip install qiskit[all]
```
