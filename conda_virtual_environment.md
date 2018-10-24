# Conda virtual environment

## 1. Create virtual environment

Create an environment called **myEnv**, initialled with **django** (default to the latest version).

```
> conda create --name myEnv django
```

To specify the version. For example:

```
> conda create --name myEnv python=3.5
```
We can then install **Django** of certain version in this environment (**activated**). 

## 2. activate and deactivate

### Activate

```
> activate myEnv
```

On some computers (Mac), you need to use `source`. 

```
> source activate myEnv
```


### Deactivate

```
> deactivate myEnv
```

## 3. info

To check the available/existing virtual environment we have created:

```
> conda info --envs
```

The `*` marks the currently activated environment.


