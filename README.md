# Flappy Bird Workshop
UCI AI Club Flappy Bird  

## Download

Click "Code", "SSH", "Download ZIP".

Save the folder to your computer.

## Prerequisites

Install conda.
https://conda.io/projects/conda/en/latest/user-guide/install/index.html
- "regular installation", choose your OS, download the installer (anaconda not miniconda)

We have provided a requirements.txt for you to setup your **python3.6.8 conda environment.**


If on Windows, open Anaconda Prompt (easiest way is to look it up on the start menu by pressing the windows key).
Otherwise, open any terminal.
- [Win] Anaconda prompt will be automatically installed when you install conda.

Change directories to flappy bird folder
```
cd /path/to/flappy/folder/
```

Then run these to install python 3.6.8 and all the dependencies.

```
conda create -n flappy python=3.6.8
conda activate flappy
python -m pip install -r requirements.txt
```


### RUN

Once you have got your venv activated, run the following command

```
python flappy.py
```

### References
https://github.com/sourabhv/FlapPyBird
https://github.com/erilyth/Flappy-Bird-Genetic-Algorithms


