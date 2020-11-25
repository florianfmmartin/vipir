# vipir
Virtual environment Integrated with Pip Install Requirements

## Requirements
- Works on Linux. MacOS not tested.
- You will need to have *virtualenv* and *pip* installed.

## Commands
```
vipir setup
```
Sets up a vipir project by creating a **.vipir** directory. Also appends the created directory if a **.gitignore** file is present.

```
vipir un/install
```
Un/installs a package.

```
vipir env
```
Leaves or enters the virtual environment.

```
vipir graph
```
Shows the installed packages.

```
vipir freeze
```
Freezes installed packages by creating a **requirements.txt** in the current folder.

```
vipir require
```
Installs all packages required specified in **./requirements.txt**.

