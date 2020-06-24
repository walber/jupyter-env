# Containerized Jupyter Environment
If you already have installed **docker** and **docker-compose** in your system, instead of installing all of the common required python libraries or creating a virtual environment using **venv** package, build a containerized enviroment using a [jupyter docker image] by the following steps:

#### 1. Clone this repository:
```shell
git clone https://github.com/walber/jupyter-env.git
```
> It uses the [datascience] docker image and [jupyter themes] by default. You may edit the **Dockerfile** to replace the default image.
#### 2. Go to repository folder:
```shell
cd jupyter-env
```
#### 3. You may customize the *requirements.txt* file
#### 4. Create and start containers:
```shell
docker-compose up --build
```
#### 5. Access http://localhost:8000

[datascience]: https://jupyter-docker-stacks.readthedocs.io/en/latest/using/selecting.html#jupyter-datascience-notebook
[jupyter themes]: https://github.com/dunovank/jupyter-themes
[jupyter docker image]: https://hub.docker.com/u/jupyter
