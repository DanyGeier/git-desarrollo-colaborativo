## Clase 02 - Git Desarollo Colaborativo

## .gitignore
Me permite indicar los archivos o carpetas que quiero que no formen parte del repositorio. Por ejemplo
archivos de log durante el desarrollo, archivos temporales, etc.

**Se crea el archivo .gitignore dentro de la raiz del proyecto.**

## .gitkeep
Ayuda a git a versioanr carpetas que quiero que sean parte del repositorio pero están vacías.

**Se crea el archivo -gitkeep dentro de la carpeta que quiero que git versione.**

## RAMAS (BRANCHES)
Las ramas me permiten trabajar en diferentes partes del proyecto de manera auxiliar sin afectar
las funcionalidades (código fuente que ya funciona)

## Listar ramas locales

```sh
git branch
```

## Listar ramas remotas

```sh
git branch -r
```

## Listar ramas locales y remotas

```sh
git branch -a
```