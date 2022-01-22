# README
Please make sure Anaconda environment and git is available in your system

## Getting the source code from the git repository
In order to retrieve the source code, make sure you have git installed
```cmd
$ git clone https://github.com/git/git
```
Navigate to where you want the source code to be located and make a clone of
this repository by running the following command:
```cmd
$ cd <to/desired/location>
$ git clone https://github.com/yaswanthchoda/imdb_proj.git
```

or Download the zip file and and extract the file in you desired location

## Setting up a conda environment
```cmd
$ cd imdb_proj
$ conda env create -f environment.yml
```

once conda environment installed successfully run following command to activate conda env
```cmd
$ cd imdb_proj
$ conda activate imdb_env
```

## Open Jupyter Notebook
open jupyter notebook by running following command and the notebook will contain all required steps to execute.
```cmd
$ jupyter notebook
```

## About Project

- This is a simple notebook which is used to get movies information from IMDB site.
- Here I am using imdb library provided by python to get top 250 movies data from IMDB.
- And displaying scatter plots using this data.