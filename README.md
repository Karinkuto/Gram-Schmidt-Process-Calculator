# Gram-Schmidt Process Calculator


This is a PyQt5 application for performing the Gram-Schmidt process on a set of input vectors. It supports both orthogonal and orthonormal basis vector calculations and displays the results in LaTeX format.


## Features


- Choose between orthogonal and orthonormal processes.
- Specify the number of vectors and their dimensions.
- Enter vector components dynamically.
- Display the resulting basis vectors in LaTeX format with proper annotations.


## Prerequisites


- Python 3.6+
- PyQt5
- PyQtWebEngine
- SymPy


## Installation


### Clone the Repository


```bash
git clone https://github.com/Karinkuto/Gram-Schmidt-Process-Calculator.git
cd gram-schmidt-calculator
```


### Set Up a Virtual Environment (Optional but Recommended)


```bash
python3 -m venv venv
source venv/bin/activate
```


### Install Dependencies


```bash
pip install -r requirements.txt
```


### System Dependencies (Ubuntu 24)


Ensure you have the necessary system dependencies:


```bash
sudo apt update
sudo apt install python3-pyqt5 python3-pyqt5.qtwebengine libxcb-xinerama0
```


## Usage


Run the application:


```bash
python gram_schmidt_calculator.py
```


## Project Structure


```
.
├── gram_schmidt_calculator.py
├── requirements.txt
└── README.md
```


## Screenshots


![image](https://github.com/user-attachments/assets/d1b3b365-8f9e-45c0-85fe-b19a2b96be99)


## Contributing


Contributions are welcome! Please create an issue or submit a pull request.
