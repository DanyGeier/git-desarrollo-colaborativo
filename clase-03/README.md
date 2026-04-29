# Clase 03 - Git Desarrollo Colaborativo

## Borrando una rama

```sh
git branch -d <nombre-de-la-rama> # Si la rama ya esta en alguna otra rama fusionada
gir branch -D <nombre-de-la-rama> # Fuerzo el borrado a pesar de que el contenido de esa rama no este en otro lado
```

## Clonado de un repositorio
Si quiero que la carpeta .git exista en mi local, necesito clonar el repositorio.

```sh
git clone <url-del-repositorio>
```

# Arreglar un mensaje de commit o agregar en un comit un archivo que me olvide

```sh
git commit --amend -m "mensaje-descriptivo"
```

# Trabajando colaborativamente
Una persona va a tener que crear el repositorio y agregar a todos los colaboradores en ese repositorio

## Traer la metadata (actualizar la carpeta .git)

```sh
git fetch
```

## Traer metadata y cambios

```sh
git pull
git pull origin dani
```

## Ver ramas locales y remotas

```sh
git branch -av
```

# Alias en Git

```sh
git config --global alias.l "log --oneline"
git config --global alias.s "status --short"
git config --global alias.c "commit -m"
git config --global alias.ll "log --oneline --decorate --all --graph"
```

# Git Resets
Es una forma de borrar commits, tengo 3 tipo de resets

## Resets Softs
En este caso si hago un resets de tipo de soft los cambios que están dentro del commits pasan a la área de staging area

```sh
git reset --soft <numero-hash>
```

## Reset Mixed (Default)
En este caso si hago un resets de tipo mixed (default) los cambios que están dentro del commits pasan al working directory

```sh
git reset --mixed <numero-hash>
git reset <numero-hash>
```

