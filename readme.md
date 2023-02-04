# Cleaner

**Use with caution! With wrong configuration it can delete lot of files**

Cleans common metadata files (configurable) from configured paths recursively

## Usage
```bash
# Performs cleaning
./cleaner
```

## Configuration
See `base_config.sh` for basic configuration example. Create `config.sh` in cleaner folder and place your custom configuration to it.

**The runtime path is the path where the cleaner is placed. Use relative paths to that directory or use absolute paths.**

## Installation
You need to have installed GIT before running this command. To install run:
```bash
git clone https://github.com/tomasklement/cleaner.git
```
This will create directory "cleaner" and clone the latest version from github.

## Upgrade
To upgrade to the latest version simply run:
```bash
git pull
```
in cleaner folder.