## Description
This code implements the 2D Vicsek model that simulates swarming behavior in active matter.

## Installation

First make sure that python 3.9 is installed. Newer versions might work, but are not tested.

Clone the repository and install the requirements:

```bash
git clone https://github.com/QuantxAmpere/activemattersim
cd activemattersim
pip install -r requirements.txt
```

## Usage

If pyenv is installed you should be able to just execute the script

```bash
./Vicsek2D.py
```

Otherwise you can run it with python

```bash
python Vicsek2D.py
```

The script will ask for additional parameters.
Once they are entered, the simulation will start and the positions and velocities of the particles will be shown in a matplotlib figure.

