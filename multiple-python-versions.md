# Managing Multiple Python Versions with Conda

## Why Do We Need Multiple Python Versions?

There are many reasons for working with different Python versions:

- To try out the latest versions of Python and explore new features.
- Reference repositories may require different Python versions (or the same version but with different dependencies).
- To avoid messing up our current development environment.

## How to Handle Multiple Python Versions

> 📌 If Python is not installed, install it first.

### For Windows:
Installing **Conda** is a convenient way to handle dependencies.

- Download and install Conda: [https://www.anaconda.com/download/success](https://www.anaconda.com/download/success)

## Managing Conda Environments

### Check Python Version
```bash
python --version
```
### Activate/ Deactivate Python
```bash
conda activate 
```
```bash
conda deactivate
```
### Create Conda Environments with Specific Python Versions
If you want to work with Python3.6, create as command

```bash
conda create -n py36 python=3.6
```

```bash
To activate py36 environment ⇒   conda activate py36
```
```bash
To deactivate py36 environment ⇒ conda deactivate
```

### Use Different Python Versions in `requirements.txt`

> 🎉 Enjoy using Python!
