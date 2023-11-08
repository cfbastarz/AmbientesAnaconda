# mpas-tools environment

Conda env file to create the mpas-tools environment.

## How to use

```
conda env create -f environment.yml
```

**Note:** this procedure may take a while.

## Versions

* conda 4.14.0
* KDE neon 5.27, Linux 6.2.0-36-generic

If conda takes too long (> 10min) checking dependencies, try tweaking your `~/.condarc` file. Mine looks like:

```
channel_priority: flexible
channels:
- conda-forge
- pyviz
- defaults
auto_activate_base: true
```

**Note:** You can also try running these instructions within the WSL Linux (Microsoft's Windows Subsystem for Linux).

carlos.bastarz@inpe.br (07/11/2023)
