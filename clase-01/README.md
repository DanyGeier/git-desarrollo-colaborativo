# Clase 01 - Git Desarrollo Colaborativo

## Crear un repositorio de GIT

```sh
git init
```

## Configurar opr primera vez y única a GIT

```sh
git config --global user.name "Daniel Geier"
git config --global user.email "danielgeier@hotmail.com"
```

## Listar configuraciones git para verificar si tengo o no esto configurado

```sh
git config --list
```

## Cambiar de acá en adelante como se va a llamar la rama principal por defecto

```sh
git config --global init.defaultBranch main
```

## Para pasar del working directory al staging area (index)

```sh
git add <nombre-archivo>
git add README.md
```

## Como ver el estado del archivo y en que área está

```sh
git status
```

