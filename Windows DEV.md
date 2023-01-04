# Personal-Dev-Setup
A windows development guide for me

#### To install packages
Basic Chocolatey Commands
We use the choco command to run chocolatey. (Remember, you must use an administrative shell for it to work.)

Install a new package:
```
choco install filename
```
Remove a package:
```
choco uninstall filename
```
List all of the installed packages:
```
choco list
```
Update:
```
choco upgrade filename
```
or to update everything at once:
```
choco upgrade all
```
### Install WSL 
See Microsoft Documentations 
https://learn.microsoft.com/en-us/windows/wsl/install#change-the-default-Linux-distribution-installed

### Develop with python
> Linux comes with python2
> 
To upgrade to python3,use
```
sudo apt-get update
sudo apt install python3-pip
```
use `python3` to invoke python commands

It's a good approach to develop in python virtual environment, thus miscellaneous packages won't crash each other
To set up venv, use:
```
python3 -m venv /path/to/new/virtual/environment
```
After the creation, you need to activate venv, in Linux environment use:
```
source ~/path/to/virtual/environment/bin/activate
```
