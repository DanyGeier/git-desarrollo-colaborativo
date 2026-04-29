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
