# YOLO Rock Paper Scissors
Trying to play rock paper scissors against my computer

# Project Setup

Before starting, be sure to create a virtual environment. I recommend using 'uv' to create and manage your virtual environment.

1. To install uv, follow the instructions [here](hthttps://docs.astral.sh/uv/getting-started/installation/).

2. Then, you can create the virtual environment:

```bash
uv venv .venv --python 3.10
```

3. Activate the virtual environment:
```bash
source .venv/bin/activate
```

4. Install the dependencies:
```bash
uv sync
```

Now you are ready to start playing rock paper scissors against your computer!

# Dataset
You can find the dataset used for this project [here](https://universe.roboflow.com/roroslab/rock-paper-scissors-sxsw-fzp8u/dataset/1). It's already splitted into train, validation and test sets.