# Flappy Bird Workshop
UCI AI Club Flappy Bird  

## Download

Use the "Clone or download" and click "Download ZIP".

Save the folder to your computer.

Open a Terminal (OSX/LINUX) or CMD (WINDOWS) and follow the below instructions.

## Prerequisites

**Has to be python3.6.8, other tensorflow will not install**

Anaconda: https://www.anaconda.com/products/distribution

Anaconda helps us manage multiple versions of Python. You could also install python 3.6.8 directly, but we recommend using Anaconda.

Python 3.6.8 Download.
https://www.python.org/downloads/release/python-368/?fbclid=IwAR2tjkyGDbWLivj2TVRRBYpB5hSFk7LmKcCpCKJU9ASrmq2CNcdxwsSZKxg

Change directories to flappy bird folder
```
cd /path/to/flappy/folder/
```

If on Windows, open Anaconda Prompt (easiest way is to look it up on the start menu by pressing the windows key).
Otherwise, open any terminal.

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


