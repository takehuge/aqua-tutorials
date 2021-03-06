# Qiskit AQUA Tutorials


## Guide for Installation and Setup

### 1. Download the Qiskit AQUA Tutorials and Samples

The easiest way is to [download](https://github.com/Qiskit/aqua-tutorials/archive/master.zip) the tutorials. 
Unzip the archive in the directory of your choice.

More advanced users may choose to use `git`. If you have `git` installed, run

```
git clone https://github.com/Qiskit/aqua-tutorials.git
```

If you need to install `git` follow the instructions [here](https://help.github.com/articles/set-up-git/).


### 2. Refer to Qiskit installation

Qiskit AQUA depends on Qiskit Core. While installation of Qiskit AQUA will automatically install Qiskit
we encourage you to read the
[Qiskit tutorial installation](https://github.com/Qiskit/qiskit-tutorial/blob/master/INSTALL.md#2-install-qiskit)
and follow the recommendation there for setting up a virtual environment.


### 3. Install Qiskit AQUA

_**Note**: If you plan to run the Qiskit AQUA Chemistry you may like to skip
to step 4 below, since that will automatically install Qiskit AQUA as its dependency._

The latest release version of Qiskit AQUA should be the one installed.

The latest release can be installed using

```
pip install qiskit-aqua
```

If you have an older version pre-installed then it can be updated using

```
pip install -U qiskit-aqua
```

### 4. Install Qiskit AQUA Chemistry

If you plan to run the Qiskit AQUA Chemistry notebooks or samples then this needs to
be installed as well. This will automatically install Qiskit AQUA as a 
dependency, so in this case manually carrying out step 3 above is not necessary. 

The latest release version of Qiskit AQUA Chemistry should be the one installed.

The latest release can be installed using

```
pip install qiskit-aqua-chemistry
```

If you have an older version pre-installed then it can be updated using

```
pip install -U qiskit-aqua-chemistry
```

## 5. Explore the tutorials

In step 2 above, if you followed the Qiskit recommendation of a virtual environment then please refer to
[Qiskit explore the tutorials](https://github.com/Qiskit/qiskit-tutorial/blob/master/INSTALL.md#4-explore-the-tutorials)
for information on how to activate the environment.

You can now **start Jupyter with the index notebook**

```
jupyter notebook index.ipynb
```
