# Теория групп

[![GitHub Actions Status](https://github.com/rudenkornk/group_theory/actions/workflows/workflow.yml/badge.svg)](https://github.com/rudenkornk/group_theory/actions)

Конспект [курса МФТИ И. И. Богданова](https://www.youtube.com/playlist?list=PLyBWNG-pZKx6pWlAfPRo2X_kPWyzq1ebj)

## Build
### Option 1: Use container with all required packages installed
**Requirements:** `podman >= 3.4.4`, `GNU Make >= 4.3`  
```bash
make in_container
```

### Option 2: config your system manually
Determenistic list of requirements exists, but not specified. You can refer to the [container description](https://github.com/rudenkornk/latex_image) and install similar packages.
```bash
make
```

## Clean
```bash
make clean
make cclean # container clean
```
