# ECI21: 

This repository is meant to help ECI21 participants to set up a local work environment for the hands-on sessions of the course. However, it is **strongly recommended** to use Google Colaboratory instead. 

It is assumed that there exists a **working [anaconda3](https://www.anaconda.com/distribution/) installation** on the target machine. 

## Installation

Clone the repository:

```console
$ git clone https://github.com/nietootein/eci21.git
```
Change directory into the cloned repository:

```console
$ cd eci21
```
Create a new environment:

```console
$ conda env create -f eci21_env.yml
```
Activate the new environment:

```console
$ conda activate eci21
```
Verify that the new environment was correctly installed:

```console
$ conda env list
```
The name of the new environment, ```eci21```, should show up in the list. 

## Updating the installation

Should you need to update an already existing ```eci21``` environment with a newer ```eci21_env.yml``` version:

```console
$ conda env update --name eci21 -f eci21_env.yml --prune
```

## Removing the installation

### Removing the environment

```console
$ conda remove --name eci21 --all
```

### Removing Anaconda

See instructions [here](https://docs.anaconda.com/anaconda/install/uninstall/).

## Contact

In case of trouble with the installation please contact Daniel Nieto (d.nieto at ucm dot es) or open an issue [here](https://github.com/nietootein/eci21/issues).
