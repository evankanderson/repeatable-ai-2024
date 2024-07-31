# Example for a talk on repeatable data science using PyTorch as an example

[Slides](https://docs.google.com/presentation/d/1sPgSq7Cy6h6rLQQnex6Z5LgwhF1dI7ZxdOLn3XUXjIc/edit)

This repo contains a [notebook](./tutorial.ipynb) derived from the [PyTorch Quickstart Tutorial](https://pytorch.org/tutorials/beginner/basics/quickstart_tutorial.html), designed for reproducibility.

When running on Windows 11 with Python 3.9 and CPU drivers, the output `model-cpu.pth` file should have a SHA-256 checksum of `138C6491DE96384AE1471C7F0AA89FEF3775154891F42C029737B670C43C5D53`.

Installation instructions:

(Linux)
```
python -m venv .venv
./.venv/scripts/activate
pip install -r requirements-frozen.txt
```

(Windows, Powershell)
```
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements-frozen.txt
```

And then open the notebook (I used Visual Studio) and execute it in the virtual environment.