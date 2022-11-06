# OncoPathwayDraw


## Installation

### System requirements
To use this repository, you must have the following set up on your system
- Python 3

### Download this software from GitHub
This package can be downloaded through GitHub on the website or by using terminal. To download on the website, navigate to the top of this page, click the green `Clone or download` button, and select `Download ZIP`. This will download this repository in a compressed format. To install using GitHub on terminal, type 

```bash
git clone https://github.com/vanallenlab/OncoPathwayDraw.git
cd OncoPathwayDraw
```

### Install Python dependencies
This repository uses Python 3.10. We recommend using a [virtual environment](https://docs.python.org/3/tutorial/venv.html) and running Python with either [Anaconda](https://www.anaconda.com/download/) or  [Miniconda](https://conda.io/miniconda.html). 

To create a virtual environment and install dependencies with Anaconda or Miniconda, run the following from this repository's directory:
```bash
conda create -y -n OncoPathwayDraw python=3.10
conda activate OncoPathwayDraw
pip install -r requirements.txt
```

If you are using base Python, you can create a virtual environment and install dependencies by running:
```bash
virtualenv OncoPathwayDraw
source activate OncoPathwayDraw/bin/activate
pip install -r requirements.txt
```
