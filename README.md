# project-template
TODO
## Setup python environment

Load an existing environment
```sh
conda env create -f environment.yml
```
or
```sh
mamba create --name TODO


```
add the envrionment to jupyter
```
mamba install -c anaconda ipykernel
python -m ipykernel install --user --name=TODO
```
Finally, save your environment and commit it to the repo
```sh
mamba env export > environment.yml
```
