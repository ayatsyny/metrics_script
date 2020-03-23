# Metrics collection script

# Description

This script to specify which metrics set to print:
* cpu - prints CPU metrics
* mem - prints RAM metrics

#### Warning: this script works with python3.6 version or higher

### Check the version of your python:
```bash
$ python -V
```

### Install packages:
```bash
pip install -Ur requirements.txt
```


### To run the script:
```bash
./metrics XXX
```

### Usage
```bash
Usage: metrics [OPTIONS] COMMAND [ARGS]...

Options:
  --install-completion [bash|zsh|fish|powershell|pwsh]
                                  Install completion for the specified shell.
  --show-completion [bash|zsh|fish|powershell|pwsh]
                                  Show completion for the specified shell, to
                                  copy it or customize the installation.

  --help                          Show this message and exit.

Commands:
  cpu
  mem
```
