
# HOW TO USE

This script is intended for for PHP and Laravel Project with Mysql.

## Installation

1. Download the [Docker](https://www.docker.com/) on your Local Machine.
2. Make sure that docker is set to Linux

3. on your local machine create a folder where the file will save.
4. Inside the folder you created open a cmd

```bash
  git init
```
```bash
  git remote add origin https://kenttroubleshooter@dev.azure.com/kenttroubleshooter/DockerScriptforLaravelDeve/_git/DockerScriptforLaravelDeve
```
```bash
  git pull origin master
```
```bash
  docker-composer build
```
```bash
  docker-composer up
```
## Run to your localmachine

1. Open the browser with localhost:8080 for Mysql PHPmyadmin GUI
2. Go to link localhost:8000
    phpinfo will load
3. All php project will be save inside the src folder

## Create a laravel project

show the running container
```bash
  docker ps
```
```bash
  docker exec -it laravel_app /bin/bash
```
```bash
  docker exec -it laravel_app /bin/bash
```
```bash
  composer create-project laravel/laravel:^10.0 example-app
```
## Run to your localmachine

1. Go to link localhost:8000/example-app/public/

-----------------------------------------------------
## Acknowledgements
PHP/Laravel & Fullstack Developer of RCC Colab Solutions

[Kent C. Cortiguerra](https://github.com/StriveForXyianoo)