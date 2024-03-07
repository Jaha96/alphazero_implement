# DeepReinforcementLearning
A replica of the AlphaZero methodology in Python

See this article for a summary of the algorithm and run instructions.

https://adsp.ai/blog/how-to-build-your-own-alphazero-ai-using-python-and-keras/


# Installation on Windows
1. Install Python 3.6.8 from https://www.python.org/downloads/release/python-368/

2. Ensure you have pip:
```bash
py -3.6 -m pip --version
```
3. Ensure pip, setuptools, and wheel are up to date:
```bash
py -3.6 -m pip install --upgrade pip setuptools wheel
```
4. Create a virtual environment:
```bash
py -3.6 -m venv .venv
```
5. Activate the virtual environment:
```bash
.venv\Scripts\activate
```

6. Download graphviz and install from: 
 https://gitlab.com/api/v4/projects/4207231/packages/generic/graphviz-releases/10.0.1/windows_10_cmake_Release_graphviz-install-10.0.1-win64.exe

7. Install the required packages:
```bash
pip install -r requirements.txt
```