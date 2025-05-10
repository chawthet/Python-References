# Managing Multiple Python Versions with Conda

Managing multiple python versions
## Why Do We Need Multiple Python Versions?
There are many reasons for working with different python versions
We want to try out the latest versions of Python out of curiosity of its new features.
Our reference repos have different Python versions, sometimes the same Python version with different requirements.
We don’t want to worry about messing up our current development environment.

## How to Handle Multiple Python Versions
Before that, If there is no Python installation, install Python first.
### For Windows
For downloading and installation conda, reference here

## Managing Conda Environments
### Check Python Version



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