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

## Otre manera de hacer un commit 
Para agregar mas información sobre lo que se hizo dentro de ese commit (A partir de la tercera línea)

1. Muevo los archivos al staging area

```sh
git add <nombre/archivo>
```

2. Hago un commit

```sh
git commit # Eso abre el nano/vim/vsc para que escribamos el mensaje
```

3. Una vez escrito el mensaje para confirmar

Ctrl + O + Enter (guardar) | Ctrl + X

## Creando una rama (Creando una bifurcación)

```sh
# primera alternativa
git branch feature/ramas # Crea una rama
git switch feature/ramas # Me muevo a la rama que indico
# segunda alternativa
git switch -c feature/ramas # Crear una rama y moverse a esa rama
```

## Como saber la diferencia entre 2 ramas

```sh
git diff <nombre-rama> 
# En main y quiero ver la diferencia entre main y feature/ramas
git diff feature/ramas
```
