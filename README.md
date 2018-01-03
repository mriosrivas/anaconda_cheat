# Anaconda Cheat Sheet

This is a simple Anaconda Cheat Sheet for the most common instructions used:

### Create an environment variable:

```bash
conda create --name myenv
```

***define python version***
```bash
conda create -n myenv python=3.4
```

***define specific package***
```bash
conda create -n myenv scipy
```

***with all anaconda packages***
```bash
conda create -n myenv anaconda
```

***import from yml file***
```bash
conda env create -f test.yml
```

### Clone an environment variable:

```bash
conda create --name myclone --clone myenv
```

### Remove environment variable:

```bash
conda remove --name myenv --all
```

### Export environment variable to yml file:

```bash
conda env export --file myenv.yml
```
