

### Python Package managers


############################
1. conda - creates packages in conda/env folder

**Conda commands**

1. `conda info -e` : command to list conda environments.

2. `conda list`: list packages of current environment.

3. `conda create <my_env> --python=python3.5 `: create conda environement with name my_env and python version 3.5.

3. `conda activate <env_name>` : activate conda environement with name env_name (terminal prompt is modified)

4. `conda deactivate` : deactivate current conda environment, to start base conda environment


###########################
2. virtualenv

**virtualenv command**

1. `pip install virtualenv` : to install virtualenv package manager

2. `python3 -m venv my_env` : create virtual env with name my_env, this creates a folder with name my_env which has bin folder,

3. `source my_env/bin/activate` : to initialize my_env virtual environment.

############################
3. pipenv

**pipenv commands**

1. `pip install pipenv` : to install pipenv package

2. `pipenv shell` : this will create a  pip env file in current working directory.

3. `pipenv install flask` : to install package with pipenv, this is similar to pip install, except the different is it also modifies the pipfile that has package requirements of the environment.

###########################
4. pip

pip - 'pip install package' installs the package in current environment

command : 

1. `pip install <package-name>` :

2. `pip uninstall <package-name>` :

3. `pip install -u <package-name>` :

4. `pip freeze` : lists the pip installed packages of current environment.

5. `pip freeze > requirements.txt` : save packages list in requirements.txt

6. `pip install -r requirements.txt` : install packages from requirements.txt list.

###########################







