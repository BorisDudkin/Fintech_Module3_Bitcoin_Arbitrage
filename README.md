# Bitcoin Arbitrage

### As Bitcoin trades on different exchanges across the globe, there might be instances of the simultaneous price dislocations in those exchanges. <br /> Bitcoin Arbitrage application enables its users to determine potential arbitrage opportunities between two exchanges by collecting, clensing and analysing historical pricing data from those exchanges.

---

## ![Bitcoin](images/bitcoinprofits.jpg)

---

## Table of contents

1. [Technologies](#technologies)
2. [Installation Guide](#installation-guide)
3. [Usage](#usage)
4. [Contributors](#contributors)
5. [License](#license)

---

## Technologies

`Python 3.9`

_Prerequisites_

pandas is a Python package that provides fast, flexible, and expressive data structures designed to make working with large sets of data easy and intuitive

- [pandas](https://github.com/pandas-dev/pandas) - For the documentation, installation guide and dependencies.
- [matplotlib ](https://matplotlib.org/) - For guidance on how to start visualization, interactive visualization, styles and layouts customazation.

---

## Installation Guide

Open your terminal (PowerShell, Command Prompt App. or Git Bash).

Before using the application first install the following dependencies by using your terminal:

To install pandas run:

```python
#  PuPi
pip install pandas
```

```python
# or conda
conda install pandas
```

---

## Usage

To use the application launch it from your shall/terminal/Git Bash. Once launched, a number of questions relating to the loan application will appear on the screen. Your answers to those questions will serve as filters the tool will apply to the list of loan providers.
NOTE: the path requested by the prompt messages is to the data file containg the list of loan providers. <br />

![terminal](images/Terminal.PNG)

The tool will output to the screen debt-to-income ratio and loan-to-value ratio of the loan and a number of qualified providers found by allplying the filters, as well as the filtered list of qualifying providers saved in the same directory as the tool.

---

## Contributors

Contact Details:

Boris Dudkin:

- [Email](boris.dudkin@gmail.com)
- [LinkedIn](www.linkedin.com/in/Boris-Dudkin)

---

## License

MIT
